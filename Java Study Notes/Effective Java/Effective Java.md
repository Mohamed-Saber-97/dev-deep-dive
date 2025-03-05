# Effective Java

------------------------------------------------------------------------------------------------------------------

## Table Of Contents

<!-- TOC -->

* [Effective Java](#effective-java)
    * [Table Of Contents](#table-of-contents)
    * [Introduction](#introduction)
    * [Creating and Destroying Objects](#creating-and-destroying-objects)
        * [Item 1: Consider static factory methods instead of constructors](#item-1-consider-static-factory-methods-instead-of-constructors)
        * [Item 2: Consider a builder when faced with many constructor parameters](#item-2-consider-a-builder-when-faced-with-many-constructor-parameters)
        * [Item 3: Enforce the singleton property with a private constructor or an enum type](#item-3-enforce-the-singleton-property-with-a-private-constructor-or-an-enum-type)
        * [Item 4: Enforce non-instantiability with a private constructor](#item-4-enforce-non-instantiability-with-a-private-constructor)
        * [Item 5: Prefer dependency injection to hard-wiring resources](#item-5-prefer-dependency-injection-to-hard-wiring-resources)
        * [Item 6: Avoid creating unnecessary objects](#item-6-avoid-creating-unnecessary-objects)
        * [Item 7: Eliminate obsolete object references](#item-7-eliminate-obsolete-object-references)
        * [Item 8: Avoid finalizers and cleaners](#item-8-avoid-finalizers-and-cleaners)
        * [Item 9: Prefer try-with-resources to try-finally](#item-9-prefer-try-with-resources-to-try-finally)
    * [Methods Common to All Objects](#methods-common-to-all-objects)
        * [Item 10: Obey the general contract when overriding equals](#item-10-obey-the-general-contract-when-overriding-equals)
        * [Item 11: Always override hashCode when you override equals](#item-11-always-override-hashcode-when-you-override-equals)
        * [Item 12: Always override toString](#item-12-always-override-tostring)
        * [Item 13: Override clone judiciously](#item-13-override-clone-judiciously)
        * [Item 14: Consider implementing Comparable](#item-14-consider-implementing-comparable)
    * [Classes and Interfaces](#classes-and-interfaces)
        * [Item 15: Minimize the accessibility of classes and members](#item-15-minimize-the-accessibility-of-classes-and-members)
        * [Item 16: In public classes, use accessor methods, not public fields](#item-16-in-public-classes-use-accessor-methods-not-public-fields)
        * [Item 17: Minimize mutability](#item-17-minimize-mutability)
        * [Item 18: Favor composition over inheritance](#item-18-favor-composition-over-inheritance)
        * [Item 19: Design and document for inheritance or else prohibit it](#item-19-design-and-document-for-inheritance-or-else-prohibit-it)
        * [Item 20: Prefer interfaces to abstract classes](#item-20-prefer-interfaces-to-abstract-classes)
        * [Item 21: Design interfaces for posterity](#item-21-design-interfaces-for-posterity)
        * [Item 22: Use interfaces only to define types](#item-22-use-interfaces-only-to-define-types)
        * [Item 23: Prefer class hierarchies to tagged classes](#item-23-prefer-class-hierarchies-to-tagged-classes)
        * [Item 24: Favor static member classes over nonstatic](#item-24-favor-static-member-classes-over-nonstatic)
        * [Item 25: Limit source files to a single top-level class](#item-25-limit-source-files-to-a-single-top-level-class)
    * [Generics](#generics)
        * [Item 26: Don’t use raw types](#item-26-dont-use-raw-types)
        * [Item 27: Eliminate unchecked warnings](#item-27-eliminate-unchecked-warnings)
        * [Item 28: Prefer lists to arrays](#item-28-prefer-lists-to-arrays)
        * [Item 29: Favor generic types](#item-29-favor-generic-types)
        * [Item 30: Favor generic methods](#item-30-favor-generic-methods)
        * [Item 31: Use bounded wildcards to increase API flexibility](#item-31-use-bounded-wildcards-to-increase-api-flexibility)
        * [Item 32: Combine generics and varargs judiciously](#item-32-combine-generics-and-varargs-judiciously)
        * [Item 33: Consider typesafe heterogeneous containers](#item-33-consider-typesafe-heterogeneous-containers)
    * [Enums and Annotations](#enums-and-annotations)
        * [Item 34: Use enums instead of int constants](#item-34-use-enums-instead-of-int-constants)
        * [Item 35: Use instance fields instead of ordinals](#item-35-use-instance-fields-instead-of-ordinals)
        * [Item 36: Use EnumSet instead of bit fields](#item-36-use-enumset-instead-of-bit-fields)
        * [Item 37: Use EnumMap instead of ordinal indexing](#item-37-use-enummap-instead-of-ordinal-indexing)
        * [Item 38: Emulate extensible enums with interfaces](#item-38-emulate-extensible-enums-with-interfaces)
        * [Item 39: Prefer annotations to naming patterns](#item-39-prefer-annotations-to-naming-patterns)
        * [Item 40: Consistently use the Override annotation](#item-40-consistently-use-the-override-annotation)
        * [Item 41: Use marker interfaces to define types](#item-41-use-marker-interfaces-to-define-types)
    * [Lambdas and Streams](#lambdas-and-streams)
        * [Item 42: Prefer lambdas to anonymous classes](#item-42-prefer-lambdas-to-anonymous-classes)
        * [Item 43: Prefer method references to lambdas](#item-43-prefer-method-references-to-lambdas)
        * [Item 44: Favor the use of standard functional interfaces](#item-44-favor-the-use-of-standard-functional-interfaces)
        * [Item 45: Use streams judiciously](#item-45-use-streams-judiciously)
        * [Item 46: Prefer side-effect-free functions in streams](#item-46-prefer-side-effect-free-functions-in-streams)
        * [Item 47: Prefer Collection to Stream as a return type](#item-47-prefer-collection-to-stream-as-a-return-type)
        * [Item 48: Use caution when making streams parallel](#item-48-use-caution-when-making-streams-parallel)
    * [Methods](#methods)
        * [Item 49: Check parameters for validity](#item-49-check-parameters-for-validity)
        * [Item 50: Make defensive copies when needed](#item-50-make-defensive-copies-when-needed)
        * [Item 51: Design method signatures carefully](#item-51-design-method-signatures-carefully)
        * [Item 52: Use overloading judiciously](#item-52-use-overloading-judiciously)
        * [Item 53: Use varargs judiciously](#item-53-use-varargs-judiciously)
        * [Item 54: Return empty collections or arrays, not nulls](#item-54-return-empty-collections-or-arrays-not-nulls)
        * [Item 55: Return optionals judiciously](#item-55-return-optionals-judiciously)
        * [Item 56: Write doc comments for all exposed API elements](#item-56-write-doc-comments-for-all-exposed-api-elements)
    * [General Programming](#general-programming)
        * [Item 57: Minimize the scope of local variables](#item-57-minimize-the-scope-of-local-variables)
        * [Item 58: Prefer for-each loops to traditional for loops](#item-58-prefer-for-each-loops-to-traditional-for-loops)
        * [Item 59: Know and use the libraries](#item-59-know-and-use-the-libraries)
        * [Item 60: Avoid float and double if exact answers are required](#item-60-avoid-float-and-double-if-exact-answers-are-required)
        * [Item 61: Prefer primitive types to boxed primitives](#item-61-prefer-primitive-types-to-boxed-primitives)
        * [Item 62: Avoid strings where other types are more appropriate](#item-62-avoid-strings-where-other-types-are-more-appropriate)
        * [Item 63: Beware the performance of string concatenation](#item-63-beware-the-performance-of-string-concatenation)
        * [Item 64: Refer to objects by their interfaces](#item-64-refer-to-objects-by-their-interfaces)
        * [Item 65: Prefer interfaces to reflection](#item-65-prefer-interfaces-to-reflection)
        * [Item 66: Use native methods judiciously](#item-66-use-native-methods-judiciously)
        * [Item 67: Optimize judiciously](#item-67-optimize-judiciously)
        * [Item 68: Adhere to generally accepted naming conventions](#item-68-adhere-to-generally-accepted-naming-conventions)
    * [Exceptions](#exceptions)
        * [Item 69: Use exceptions only for exceptional conditions](#item-69-use-exceptions-only-for-exceptional-conditions)
        * [Item 70: Use checked exceptions for recoverable conditions and runtime exceptions for programming errors](#item-70-use-checked-exceptions-for-recoverable-conditions-and-runtime-exceptions-for-programming-errors)
        * [Item 71: Avoid unnecessary use of checked exceptions](#item-71-avoid-unnecessary-use-of-checked-exceptions)
        * [Item 72: Favor the use of standard exceptions](#item-72-favor-the-use-of-standard-exceptions)
        * [Item 73: Throw exceptions appropriate to the abstraction](#item-73-throw-exceptions-appropriate-to-the-abstraction)
        * [Item 74: Document all exceptions thrown by each method](#item-74-document-all-exceptions-thrown-by-each-method)
        * [Item 75: Include failure-capture information in detail messages](#item-75-include-failure-capture-information-in-detail-messages)
        * [Item 76: Strive for failure atomicity](#item-76-strive-for-failure-atomicity)
        * [Item 77: Don’t ignore exceptions](#item-77-dont-ignore-exceptions)
    * [Concurrency](#concurrency)
        * [Item 78: Synchronize access to shared mutable data](#item-78-synchronize-access-to-shared-mutable-data)
        * [Item 79: Avoid excessive synchronization](#item-79-avoid-excessive-synchronization)
        * [Item 80: Prefer executors, tasks, and streams to threads](#item-80-prefer-executors-tasks-and-streams-to-threads)
        * [Item 81: Prefer concurrency utilities to wait and notify](#item-81-prefer-concurrency-utilities-to-wait-and-notify)
        * [Item 82: Document thread safety](#item-82-document-thread-safety)
        * [Item 83: Use lazy initialization judiciously](#item-83-use-lazy-initialization-judiciously)
        * [Item 84: Don’t depend on the thread scheduler](#item-84-dont-depend-on-the-thread-scheduler)
    * [Serialization](#serialization)
        * [Item 85: Prefer alternatives to Java serialization](#item-85-prefer-alternatives-to-java-serialization)
        * [Item 86: Implement Serializable with great caution](#item-86-implement-serializable-with-great-caution)
        * [Item 87: Consider using a custom serialized form](#item-87-consider-using-a-custom-serialized-form)
        * [Item 88: Write readObject methods defensively](#item-88-write-readobject-methods-defensively)
        * [Item 89: For instance control, prefer enum types to readResolve](#item-89-for-instance-control-prefer-enum-types-to-readresolve)
        * [Item 90: Consider serialization proxies instead of serialized instances](#item-90-consider-serialization-proxies-instead-of-serialized-instances)

<!-- TOC -->

------------------------------------------------------------------------------------------------------------------

## Introduction

------------------------------------------------------------------------------------------------------------------

## Creating and Destroying Objects

### Item 1: Consider static factory methods instead of constructors

### Item 2: Consider a builder when faced with many constructor parameters

### Item 3: Enforce the singleton property with a private constructor or an enum type

### Item 4: Enforce non-instantiability with a private constructor

### Item 5: Prefer dependency injection to hard-wiring resources

### Item 6: Avoid creating unnecessary objects

### Item 7: Eliminate obsolete object references

### Item 8: Avoid finalizers and cleaners

### Item 9: Prefer try-with-resources to try-finally

------------------------------------------------------------------------------------------------------------------

## Methods Common to All Objects

### Item 10: Obey the general contract when overriding equals

### Item 11: Always override hashCode when you override equals

### Item 12: Always override toString

### Item 13: Override clone judiciously

### Item 14: Consider implementing Comparable

------------------------------------------------------------------------------------------------------------------

## Classes and Interfaces

### Item 15: Minimize the accessibility of classes and members

### Item 16: In public classes, use accessor methods, not public fields

### Item 17: Minimize mutability

### Item 18: Favor composition over inheritance

### Item 19: Design and document for inheritance or else prohibit it

### Item 20: Prefer interfaces to abstract classes

### Item 21: Design interfaces for posterity

### Item 22: Use interfaces only to define types

### Item 23: Prefer class hierarchies to tagged classes

### Item 24: Favor static member classes over nonstatic

### Item 25: Limit source files to a single top-level class

------------------------------------------------------------------------------------------------------------------

## Generics

### Item 26: Don’t use raw types

### Item 27: Eliminate unchecked warnings

### Item 28: Prefer lists to arrays

### Item 29: Favor generic types

### Item 30: Favor generic methods

### Item 31: Use bounded wildcards to increase API flexibility

### Item 32: Combine generics and varargs judiciously

### Item 33: Consider typesafe heterogeneous containers

------------------------------------------------------------------------------------------------------------------

## Enums and Annotations

### Item 34: Use enums instead of int constants

### Item 35: Use instance fields instead of ordinals

### Item 36: Use EnumSet instead of bit fields

### Item 37: Use EnumMap instead of ordinal indexing

### Item 38: Emulate extensible enums with interfaces

### Item 39: Prefer annotations to naming patterns

### Item 40: Consistently use the Override annotation

### Item 41: Use marker interfaces to define types

------------------------------------------------------------------------------------------------------------------

## Lambdas and Streams

### Item 42: Prefer lambdas to anonymous classes

### Item 43: Prefer method references to lambdas

### Item 44: Favor the use of standard functional interfaces

### Item 45: Use streams judiciously

### Item 46: Prefer side-effect-free functions in streams

### Item 47: Prefer Collection to Stream as a return type

### Item 48: Use caution when making streams parallel

------------------------------------------------------------------------------------------------------------------

## Methods

### Item 49: Check parameters for validity

### Item 50: Make defensive copies when needed

### Item 51: Design method signatures carefully

### Item 52: Use overloading judiciously

### Item 53: Use varargs judiciously

### Item 54: Return empty collections or arrays, not nulls

### Item 55: Return optionals judiciously

### Item 56: Write doc comments for all exposed API elements

------------------------------------------------------------------------------------------------------------------

## General Programming

### Item 57: Minimize the scope of local variables

### Item 58: Prefer for-each loops to traditional for loops

### Item 59: Know and use the libraries

### Item 60: Avoid float and double if exact answers are required

### Item 61: Prefer primitive types to boxed primitives

### Item 62: Avoid strings where other types are more appropriate

### Item 63: Beware the performance of string concatenation

### Item 64: Refer to objects by their interfaces

### Item 65: Prefer interfaces to reflection

### Item 66: Use native methods judiciously

### Item 67: Optimize judiciously

### Item 68: Adhere to generally accepted naming conventions

------------------------------------------------------------------------------------------------------------------

## Exceptions

### Item 69: Use exceptions only for exceptional conditions

### Item 70: Use checked exceptions for recoverable conditions and runtime exceptions for programming errors

### Item 71: Avoid unnecessary use of checked exceptions

### Item 72: Favor the use of standard exceptions

### Item 73: Throw exceptions appropriate to the abstraction

### Item 74: Document all exceptions thrown by each method

### Item 75: Include failure-capture information in detail messages

### Item 76: Strive for failure atomicity

### Item 77: Don’t ignore exceptions

------------------------------------------------------------------------------------------------------------------

## Concurrency

### Item 78: Synchronize access to shared mutable data

### Item 79: Avoid excessive synchronization

### Item 80: Prefer executors, tasks, and streams to threads

### Item 81: Prefer concurrency utilities to wait and notify

### Item 82: Document thread safety

### Item 83: Use lazy initialization judiciously

### Item 84: Don’t depend on the thread scheduler

------------------------------------------------------------------------------------------------------------------

## Serialization

### Item 85: Prefer alternatives to Java serialization

### Item 86: Implement Serializable with great caution

### Item 87: Consider using a custom serialized form

### Item 88: Write readObject methods defensively

### Item 89: For instance control, prefer enum types to readResolve

### Item 90: Consider serialization proxies instead of serialized instances