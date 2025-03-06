# Java Concurrency in Practice

------------------------------------------------------------------------------------------------------------------

## Table Of Contents

<!-- TOC -->

* [Java Concurrency in Practice](#java-concurrency-in-practice)
    * [Table Of Contents](#table-of-contents)
        * [Introduction](#introduction)
            * [A (very) brief history of concurrency](#a-very-brief-history-of-concurrency)
            * [Benefits of threads](#benefits-of-threads)
            * [Risks of threads](#risks-of-threads)
            * [Threads are everywhere](#threads-are-everywhere)
    * [Fundamentals](#fundamentals)
        * [Thread Safety](#thread-safety)
            * [What is thread safety?](#what-is-thread-safety)
            * [Atomicity](#atomicity)
            * [Locking](#locking)
            * [Guarding state with locks](#guarding-state-with-locks)
            * [Liveness and performance](#liveness-and-performance)
        * [Sharing Objects](#sharing-objects)
            * [Visibility](#visibility)
            * [Publication and escape](#publication-and-escape)
            * [Thread confinement](#thread-confinement)
            * [Immutability](#immutability)
            * [Safe publication](#safe-publication)
        * [Composing Objects](#composing-objects)
            * [Designing a thread-safe class](#designing-a-thread-safe-class)
            * [Instance confinement](#instance-confinement)
            * [Delegating thread safety](#delegating-thread-safety)
            * [Adding functionality to existing thread-safe classes](#adding-functionality-to-existing-thread-safe-classes)
            * [Documenting synchronization policies](#documenting-synchronization-policies)
        * [Building Blocks](#building-blocks)
            * [Synchronized collections](#synchronized-collections)
            * [Concurrent collections](#concurrent-collections)
            * [Blocking queues and the producer-consumer pattern](#blocking-queues-and-the-producer-consumer-pattern)
            * [Blocking and interruptible methods](#blocking-and-interruptible-methods)
            * [Synchronizers](#synchronizers)
            * [Building an efficient, scalable result cache](#building-an-efficient-scalable-result-cache)
    * [Structuring Concurrent Applications](#structuring-concurrent-applications)
        * [Task Execution](#task-execution)
            * [Executing tasks in threads](#executing-tasks-in-threads)
            * [The Executor framework](#the-executor-framework)
            * [Finding exploitable parallelism](#finding-exploitable-parallelism)
        * [Cancellation and Shutdown](#cancellation-and-shutdown)
            * [Task cancellation](#task-cancellation)
            * [Stopping a thread-based service](#stopping-a-thread-based-service)
            * [Handling abnormal thread termination](#handling-abnormal-thread-termination)
            * [JVM shutdown](#jvm-shutdown)
        * [Building Blocks](#building-blocks-1)
            * [Synchronized collections](#synchronized-collections-1)
            * [Concurrent collections](#concurrent-collections-1)
            * [Blocking queues and the producer-consumer pattern](#blocking-queues-and-the-producer-consumer-pattern-1)
            * [Blocking and interruptible methods](#blocking-and-interruptible-methods-1)
            * [Synchronizers](#synchronizers-1)
            * [Building an efficient, scalable result cache](#building-an-efficient-scalable-result-cache-1)
    * [Structuring Concurrent Applications](#structuring-concurrent-applications-1)
        * [Task Execution](#task-execution-1)
            * [Executing tasks in threads](#executing-tasks-in-threads-1)
            * [The Executor framework](#the-executor-framework-1)
            * [Finding exploitable parallelism](#finding-exploitable-parallelism-1)
        * [Cancellation and Shutdown](#cancellation-and-shutdown-1)
            * [Task cancellation](#task-cancellation-1)
            * [Stopping a thread-based service](#stopping-a-thread-based-service-1)
            * [Handling abnormal thread termination](#handling-abnormal-thread-termination-1)
            * [JVM shutdown](#jvm-shutdown-1)
        * [Applying Thread Pools](#applying-thread-pools)
            * [Implicit couplings between tasks and execution policies](#implicit-couplings-between-tasks-and-execution-policies)
            * [Sizing thread pools](#sizing-thread-pools)
            * [Configuring ThreadPoolExecutor](#configuring-threadpoolexecutor)
            * [Extending ThreadPoolExecutor](#extending-threadpoolexecutor)
            * [Parallelizing recursive algorithms](#parallelizing-recursive-algorithms)
        * [GUI Applications](#gui-applications)
            * [Why are GUIs single-threaded?](#why-are-guis-single-threaded)
            * [Short-running GUI tasks](#short-running-gui-tasks)
            * [Long-running GUI tasks](#long-running-gui-tasks)
            * [Shared data models](#shared-data-models)
            * [Other forms of single-threaded subsystems](#other-forms-of-single-threaded-subsystems)
    * [Liveness, Performance, and Testing](#liveness-performance-and-testing)
        * [Avoiding Liveness Hazards](#avoiding-liveness-hazards)
            * [Deadlock](#deadlock)
            * [Avoiding and diagnosing deadlocks](#avoiding-and-diagnosing-deadlocks)
            * [Other liveness hazards](#other-liveness-hazards)
        * [Performance and Scalability](#performance-and-scalability)
            * [Thinking about performance](#thinking-about-performance)
            * [Amdahl’s law](#amdahls-law)
            * [Costs introduced by threads](#costs-introduced-by-threads)
            * [Reducing lock contention](#reducing-lock-contention)
            * [Example: Comparing Map performance](#example-comparing-map-performance)
            * [Reducing context switch overhead](#reducing-context-switch-overhead)
        * [Testing Concurrent Programs](#testing-concurrent-programs)
            * [Testing for correctness](#testing-for-correctness)
            * [Testing for performance](#testing-for-performance)
            * [Avoiding performance testing pitfalls](#avoiding-performance-testing-pitfalls)
            * [Complementary testing approaches](#complementary-testing-approaches)
    * [Advanced Topics](#advanced-topics)
        * [Explicit Locks](#explicit-locks)
            * [Lock and ReentrantLock](#lock-and-reentrantlock)
            * [Performance considerations](#performance-considerations)
            * [Fairness](#fairness)
            * [Choosing between synchronized and ReentrantLock](#choosing-between-synchronized-and-reentrantlock)
            * [Read-write locks](#read-write-locks)
        * [Building Custom Synchronizers](#building-custom-synchronizers)
            * [Managing state dependence](#managing-state-dependence)
            * [Using condition queues](#using-condition-queues)
            * [Explicit condition objects](#explicit-condition-objects)
            * [Anatomy of a synchronizer](#anatomy-of-a-synchronizer)
            * [AbstractQueuedSynchronizer](#abstractqueuedsynchronizer)
            * [AQS in java.util.concurrent synchronizer classes](#aqs-in-javautilconcurrent-synchronizer-classes)
        * [Atomic Variables and Nonblocking Synchronization](#atomic-variables-and-nonblocking-synchronization)
            * [Disadvantages of locking](#disadvantages-of-locking)
            * [Hardware support for concurrency](#hardware-support-for-concurrency)
            * [Atomic variable classes](#atomic-variable-classes)
            * [Nonblocking algorithms](#nonblocking-algorithms)
        * [The Java Memory Model](#the-java-memory-model)
            * [What is a memory model, and why would I want one?](#what-is-a-memory-model-and-why-would-i-want-one)
            * [Publication](#publication)
            * [Initialization safety](#initialization-safety)
        * [Annotations for Concurrency](#annotations-for-concurrency)
            * [Class annotations](#class-annotations)
            * [Field and method annotations](#field-and-method-annotations)

<!-- TOC -->

------------------------------------------------------------------------------------------------------------------

### Introduction

#### A (very) brief history of concurrency

#### Benefits of threads

#### Risks of threads

#### Threads are everywhere

------------------------------------------------------------------------------------------------------------------


## Fundamentals

------------------------------------------------------------------------------------------------------------------


### Thread Safety

#### What is thread safety?

#### Atomicity

#### Locking

#### Guarding state with locks

#### Liveness and performance

------------------------------------------------------------------------------------------------------------------


### Sharing Objects

#### Visibility

#### Publication and escape

#### Thread confinement

#### Immutability

#### Safe publication

------------------------------------------------------------------------------------------------------------------


### Composing Objects

#### Designing a thread-safe class

#### Instance confinement

#### Delegating thread safety

#### Adding functionality to existing thread-safe classes

#### Documenting synchronization policies

------------------------------------------------------------------------------------------------------------------


### Building Blocks

#### Synchronized collections

#### Concurrent collections

#### Blocking queues and the producer-consumer pattern

#### Blocking and interruptible methods

#### Synchronizers

#### Building an efficient, scalable result cache

------------------------------------------------------------------------------------------------------------------


## Structuring Concurrent Applications

------------------------------------------------------------------------------------------------------------------


### Task Execution

#### Executing tasks in threads

#### The Executor framework

#### Finding exploitable parallelism

------------------------------------------------------------------------------------------------------------------


### Cancellation and Shutdown

#### Task cancellation

#### Stopping a thread-based service

#### Handling abnormal thread termination

#### JVM shutdown

------------------------------------------------------------------------------------------------------------------


### Building Blocks

#### Synchronized collections

#### Concurrent collections

#### Blocking queues and the producer-consumer pattern

#### Blocking and interruptible methods

#### Synchronizers

#### Building an efficient, scalable result cache

------------------------------------------------------------------------------------------------------------------


## Structuring Concurrent Applications

------------------------------------------------------------------------------------------------------------------


### Task Execution

#### Executing tasks in threads

#### The Executor framework

#### Finding exploitable parallelism

------------------------------------------------------------------------------------------------------------------


### Cancellation and Shutdown

#### Task cancellation

#### Stopping a thread-based service

#### Handling abnormal thread termination

#### JVM shutdown

------------------------------------------------------------------------------------------------------------------


### Applying Thread Pools

#### Implicit couplings between tasks and execution policies

#### Sizing thread pools

#### Configuring ThreadPoolExecutor

#### Extending ThreadPoolExecutor

#### Parallelizing recursive algorithms

------------------------------------------------------------------------------------------------------------------


### GUI Applications

#### Why are GUIs single-threaded?

#### Short-running GUI tasks

#### Long-running GUI tasks

#### Shared data models

#### Other forms of single-threaded subsystems

------------------------------------------------------------------------------------------------------------------


## Liveness, Performance, and Testing

------------------------------------------------------------------------------------------------------------------


### Avoiding Liveness Hazards

#### Deadlock

#### Avoiding and diagnosing deadlocks

#### Other liveness hazards

------------------------------------------------------------------------------------------------------------------


### Performance and Scalability

#### Thinking about performance

#### Amdahl’s law

#### Costs introduced by threads

#### Reducing lock contention

#### Example: Comparing Map performance

#### Reducing context switch overhead

------------------------------------------------------------------------------------------------------------------


### Testing Concurrent Programs

#### Testing for correctness

#### Testing for performance

#### Avoiding performance testing pitfalls

#### Complementary testing approaches

------------------------------------------------------------------------------------------------------------------

## Advanced Topics

------------------------------------------------------------------------------------------------------------------


### Explicit Locks

#### Lock and ReentrantLock

#### Performance considerations

#### Fairness

#### Choosing between synchronized and ReentrantLock

#### Read-write locks

------------------------------------------------------------------------------------------------------------------


### Building Custom Synchronizers

#### Managing state dependence

#### Using condition queues

#### Explicit condition objects

#### Anatomy of a synchronizer

#### AbstractQueuedSynchronizer

#### AQS in java.util.concurrent synchronizer classes

------------------------------------------------------------------------------------------------------------------


### Atomic Variables and Nonblocking Synchronization

#### Disadvantages of locking

#### Hardware support for concurrency

#### Atomic variable classes

#### Nonblocking algorithms

------------------------------------------------------------------------------------------------------------------


### The Java Memory Model

#### What is a memory model, and why would I want one?

#### Publication

#### Initialization safety

------------------------------------------------------------------------------------------------------------------


### Annotations for Concurrency

#### Class annotations

#### Field and method annotations