# OCP Oracle Certified Professional Java SE 17 Developer (Exam 1Z0-829) Programmer’s Guide

------------------------------------------------------------------------------------------------------------------

## Java Certification Exam Guide

*(For those preparing for the Java SE 17 Developer Exam)*

### Preparing for the Exam

- Regularly visit the [**exam website**](https://education.oracle.com/java-se-17-developer/pexam_1Z0-829), as Oracle is known to change practical information regarding the exam and the exam objectives intermittently
- The goal of the exams is to test practical knowledge and usage of the Java programming language and specific APIs
- The exams require a thorough understanding of both the syntax and the semantics of the language, including the use of its core APIs
- It's highly recommended joining an [online Java certification community](https://coderanch.com/f/24/java-programmer-OCPJP), such as [Code Ranch](https://coderanch.com), which has dedicated active forums for the different Java certifications
- [**Enthuware**](https://enthuware.com/) provides more practice tests for OCP Java SE Developer certification at a nominal price

### Registering for the Online Proctored Exam

- A certified Oracle account is required to log on to the [Oracle CertView certification portal](https://certview.oracle.com/)
- An [exam attempt](https://education.oracle.com/buy-exam) (previously called a certification voucher) to take the exam is sold by Oracle
- Be sure to obtain an exam attempt for Oracle Technology Exams, which covers Java certification exams
- After obtaining the exam attempt, you can schedule to take the online proctored exam when they are ready at the [Oracle MyLearn portal](https://mylearn.oracle.com/)
- Be sure to schedule for the right exam. you can reschedule an exam without penalty up to 48 hours before the appointment time.
- After taking the exam, you will receive an email from Oracle within 30 minutes informing them that their exam results are available in _CertView_
    - Candidates who pass the exam will receive an email informing them that an _eCertificate_ is available in _CertView_.
    - Instructions for requesting a printed copy of the certificate are included in this email.
    - Candidates who fail the exam can register to retake the exam after a 14-day waiting period

> Note that the exam attempt has an expiration date, which is usually six months after it is acquired. Oracle will not replace lost or expired exam attempts, neither will they offer refunds for unused exam attempts

### How the Online Proctored Exam Is Conducted

- Specific requirements are stipulated at the Oracle MyLearn portal for the computer equipment, required ID proofs, and test space in order to take the online exam, and a proctor will ensure that these requirements are met before the exam begins and during the exam, consult the Oracle MyLearn portal for the requirements that are in effect at any given time. The following is a short summary of these requirements
    - Computer equipment
        - Minimum requirements are spelled out for computer equipment (personal desktop/laptop) with regard to Internet connectivity, audio, and webcam capabilities
        - You will need to prepare your equipment in advance so that it meets the minimum requirements
    - Proof of identity
        - The Oracle MyLearn portal states the exact requirements regarding two forms of government-issued identifications that may be required to take the exam
    - Testing space
        - Apart from checking in 30 minutes before the exam and taking it in a quiet, distraction-free room, there are strict requirements as to what is not allowed during the exam.
        - Considering the mode of exam delivery, these restrictions are not surprising as they create a test space where the only communication allowed is that between you and the exam delivery software
- The Exam Program
    - The computer program used to conduct the exam will select a set of questions at random, and present them through a graphical user interface
    - The interface is designed in such a way that you are able to move back and forth through the questions for reviewing purposes.
    - Questions can be temporarily left unanswered, and yoi can return to them later
    - You can also mark questions for later review during the exam.
    - Before the exam starts, You're allowed a test run with the test interface
    - A demo test that has nothing to do with the Java exam is used. Its sole purpose is to acquaint you with the program being used to conduct the exam
- Utilizing the Allotted Time
    - The exam consists of a fixed number of questions that must be answered within the allocated time
    - **_As you have limited time to answer each question, you cannot afford to get stuck on a question_**
    - **_If the answer does not become apparent within a reasonable time, it is advisable to move on to the next question_**
    - **_wrong answer and a blank answer carry the same penalty: loss of points_** Therefore, it is better to guess an answer and hope that it is correct rather than leaving blank
    - The process of elimination can sometimes be useful in narrowing down the answer to a question
    - Eliminating obvious incorrect choices increases the chances of arriving at the right answer
- The Exam Result
    - The exam results are presented on the screen after the exam. Afterward, you should log on to the CertView certification portal to see details about your performance
    - An indication of whether you've passed or failed.
    - The total score. All the scored questions are weighted equally, and the score is calculated based on the percentage of correct answers. No credit is given for partially correct answers for the scored questions
    - Indications on how well you did in each category within the objectives. Candidates who fail the exam should pay close attention to this information. If you're planning to retake the exam, it may give a good indication of which topics need closer attention
    - The result will not divulge which questions were answered correctly.

### The Questions

- Assumptions About the Exam Questions
    - **Missing package and import statements:** Unless explicitly provided, stated, or referred to in the question, assume that the code is in the same package/module and all necessary import statements are given
    - **No file or directory path names for classes:** In this case, assume that either all classes are in the same file or each class is in a separate file and these files are in the same directory
    - **Unintended line breaks:** Line breaks that make the code lines appear to be wrapped unintentionally should be ignored, and the code should be assumed to compile without errors.
    - **Code fragments:** Assume that the necessary context exists to compile and execute the code, if such context is not explicitly specified by the question
    - **Descriptive comments:** Such comments should be taken at their face value, providing the intent described in the comment
- Types of Questions Asked
    - Analyzing program code. The question provides some source code, and asks a specific question pertaining to the code
        - Will running the program provide the expected result?
        - What will be written to the standard output when the program is run?
        - Will the code compile?
        - Choosing a code snippet to insert in the given code in order for it to exhibit specific behavior
    - Identifying true or false statements
- **The wording of the questions is precise, and the responses selected in multiple-choice questions are likewise expected to be precise**
- **None of the questions is intentionally meant to be a trick question. Exam questions have been reviewed by both Java experts and language experts to remove as much ambiguity from their wording as possible.**
- Since the program used in the exam will select and present the questions in a random fashion
    - there is no point in trying to guess the form of the questions
    - The order of the answers in multiple-choice questions has been randomized, and therefore, has no significance
- Types of Answers Expected
    - All exam questions are multiple choice. The correct number of alternatives to select is designated in the question, and all must be selected for the question as a whole to be considered correctly answered
    - For multiple-choice questions, the program will ask you to select a specific number of answers from a list
    - Where a single correct answer is expected, radio buttons will allow selection of only one answer
    - The most appropriate response should be selected.
- In questions where all appropriate responses should be selected, check boxes will allow the selection of each response individually.
    - In this case, all choices should be considered on their own merits; that is, responses should not be weighed against each other.
    - It can be helpful to think of each of the choices as an individual true–false question
- Topics Covered by the Questions
    - Not all topics may appear on an actual exam session due to the limited number of questions comprising the exam
    - Many of the questions will require intimate knowledge of core Java APIs
    - **The Java SE Platform API documentation should be consulted, as it is essential that candidates familiarize themselves with the relevant parts of the API documentation**

### Exam Topics: Java SE 17 Developer

> **Important Note:**  
> Items marked with 🎯 indicate the core exam topics.  
> If a parent (or header) item is marked with 🎯, then one or more of its submenu items are also marked.

### Why This Section?

This section is dedicated to helping those preparing for Java certification exams. If you are not interested in certification, you can skip this section and focus on other Java topics.

### Table Of Contents

<!-- TOC -->

* [OCP Oracle Certified Professional Java SE 17 Developer (Exam 1Z0-829) Programmer’s Guide](#ocp-oracle-certified-professional-java-se-17-developer-exam-1z0-829-programmers-guide)
    * [Java Certification Exam Guide](#java-certification-exam-guide)
        * [Preparing for the Exam](#preparing-for-the-exam)
        * [Registering for the Online Proctored Exam](#registering-for-the-online-proctored-exam)
        * [How the Online Proctored Exam Is Conducted](#how-the-online-proctored-exam-is-conducted)
        * [The Questions](#the-questions)
        * [Exam Topics: Java SE 17 Developer](#exam-topics-java-se-17-developer)
        * [Why This Section?](#why-this-section)
        * [Table Of Contents](#table-of-contents)
    * [Basics of Java Programming](#basics-of-java-programming)
        * [The Java Ecosystem](#the-java-ecosystem)
        * [Classes](#classes)
        * [Objects](#objects)
        * [Instance Members](#instance-members)
        * [Static Members](#static-members)
        * [Inheritance](#inheritance)
        * [Aggregation](#aggregation)
        * [Sample Java Program](#sample-java-program)
        * [Program Output](#program-output)
        * [Exam Questions 🎯](#exam-questions-)
    * [Basic Elements, Primitive Data Types, and Operators 🎯](#basic-elements-primitive-data-types-and-operators-)
        * [Basic Language Elements](#basic-language-elements)
        * [Primitive Data Types 🎯](#primitive-data-types-)
        * [Conversions 🎯](#conversions-)
        * [Type Conversion Contexts 🎯](#type-conversion-contexts-)
        * [Precedence and Associativity Rules `for` Operators 🎯](#precedence-and-associativity-rules-for-operators-)
        * [Evaluation Order of Operands 🎯](#evaluation-order-of-operands-)
        * [The Simple Assignment Operator `=` 🎯](#the-simple-assignment-operator--)
        * [Arithmetic Operators: `*`, `/`, `%`, `+`, `-` 🎯](#arithmetic-operators-------)
        * [The Binary String Concatenation Operator `+` 🎯](#the-binary-string-concatenation-operator--)
        * [Variable Increment and Decrement Operators: `++`,`--` 🎯](#variable-increment-and-decrement-operators----)
        * [Boolean Expressions 🎯](#boolean-expressions-)
        * [Relational Operators: `<`, `<=,` `>`, `>=` 🎯](#relational-operators-----)
        * [Equality 🎯](#equality-)
        * [Boolean Logical Operators: `!`, `^`, `&`, `|` 🎯](#boolean-logical-operators-----)
        * [Conditional Operators: `&&`, `||` 🎯](#conditional-operators---)
        * [Integer Bitwise Operators: `~`, `&`, `|`, `^` 🎯](#integer-bitwise-operators-----)
        * [Shift Operators: `<<`, `>>`, `>>>` 🎯](#shift-operators----)
        * [The Conditional Operator `?:` 🎯](#the-conditional-operator--)
        * [Other Operators: `new`, `[]`, `instanceof`, `-`> 🎯](#other-operators-new--instanceof---)
        * [Exam Questions 🎯](#exam-questions--1)
    * [Declarations 🎯](#declarations-)
        * [Class Declarations 🎯](#class-declarations-)
        * [Method Declarations 🎯](#method-declarations-)
        * [Statements 🎯](#statements-)
        * [Variable Declarations 🎯](#variable-declarations-)
        * [Instance Methods and the Object Reference `this` 🎯](#instance-methods-and-the-object-reference-this-)
        * [Method Overloading 🎯](#method-overloading-)
        * [Constructors 🎯](#constructors-)
        * [Static Member Declarations 🎯](#static-member-declarations-)
        * [Arrays 🎯](#arrays-)
        * [Parameter Passing](#parameter-passing)
        * [Variable Arity Methods 🎯](#variable-arity-methods-)
        * [The `main()` Method](#the-main-method)
        * [Local Variable Type Inference 🎯](#local-variable-type-inference-)
        * [Exam Questions 🎯](#exam-questions--2)
    * [Control Flow 🎯](#control-flow-)
        * [Selection Statements 🎯](#selection-statements-)
        * [The `switch` Statement 🎯](#the-switch-statement-)
        * [The `switch` Expression 🎯](#the-switch-expression-)
        * [Iteration Statements 🎯](#iteration-statements-)
        * [The `while` Statement 🎯](#the-while-statement-)
        * [The `do`-`while` Statement 🎯](#the-do-while-statement-)
        * [The `for(;;)` Statement 🎯](#the-for-statement-)
        * [The `for(:)` Statement 🎯](#the-for-statement--1)
        * [Transfer Statements 🎯](#transfer-statements-)
        * [Labeled Statements 🎯](#labeled-statements-)
        * [The `break` Statement 🎯](#the-break-statement-)
        * [The `continue` Statement 🎯](#the-continue-statement-)
        * [The `return` Statement 🎯](#the-return-statement-)
        * [Exam Questions 🎯](#exam-questions--3)
    * [Object-Oriented Programming 🎯](#object-oriented-programming-)
        * [Implementing Inheritance 🎯](#implementing-inheritance-)
        * [The Object Reference super 🎯](#the-object-reference-super-)
        * [Chaining Constructors Using `this()` and `super()` 🎯](#chaining-constructors-using-this-and-super-)
        * [Abstract Classes and Methods 🎯](#abstract-classes-and-methods-)
        * [Final Declarations](#final-declarations)
        * [Interfaces 🎯](#interfaces-)
        * [Arrays and Subtyping](#arrays-and-subtyping)
        * [Reference Values and Conversions](#reference-values-and-conversions)
        * [Reference Value Assignment Conversions](#reference-value-assignment-conversions)
        * [Method Invocation Conversions Involving References](#method-invocation-conversions-involving-references)
        * [Reference Casting and the instanceof Operator 🎯](#reference-casting-and-the-instanceof-operator-)
        * [Polymorphism 🎯](#polymorphism-)
        * [Enum Types 🎯](#enum-types-)
        * [Record Classes 🎯](#record-classes-)
        * [Sealed Classes and Interfaces 🎯](#sealed-classes-and-interfaces-)
        * [Exam Questions 🎯](#exam-questions--4)
    * [Access Control 🎯](#access-control-)
        * [Design Principle: Encapsulation 🎯](#design-principle-encapsulation-)
        * [Java Source File Structure](#java-source-file-structure)
        * [Packages](#packages)
        * [Searching for Classes on the Class Path](#searching-for-classes-on-the-class-path)
        * [Access Modifiers](#access-modifiers)
        * [Scope Rules 🎯](#scope-rules-)
        * [Implementing Immutability 🎯](#implementing-immutability-)
        * [Exam Questions 🎯](#exam-questions--5)
    * [Exception Handling 🎯](#exception-handling-)
        * [Stack-Based Execution and Exception Propagation](#stack-based-execution-and-exception-propagation)
        * [Exception Types 🎯](#exception-types-)
        * [Exception Handling: `try`, `catch`, and `finally` 🎯](#exception-handling-try-catch-and-finally-)
        * [The `throw` Statement](#the-throw-statement)
        * [The `throws` Clause](#the-throws-clause)
        * [The Multi-`catch` Clause 🎯](#the-multi-catch-clause-)
        * [The `try`-with-resources Statement 🎯](#the-try-with-resources-statement-)
        * [Advantages of Exception Handling](#advantages-of-exception-handling)
        * [Exam Questions 🎯](#exam-questions--6)
    * [Selected API Classes 🎯](#selected-api-classes-)
        * [Overview of the `java.lang` Package](#overview-of-the-javalang-package)
        * [The `Object` Class](#the-object-class)
        * [The Wrapper Classes 🎯](#the-wrapper-classes-)
        * [The `String` Class 🎯](#the-string-class-)
        * [The `StringBuilder` Class 🎯](#the-stringbuilder-class-)
        * [The `Math` Class 🎯](#the-math-class-)
        * [The `Random` Class](#the-random-class)
        * [Using Big Numbers](#using-big-numbers)
        * [Exam Questions 🎯](#exam-questions--7)
    * [Nested Type Declarations 🎯](#nested-type-declarations-)
        * [Overview of Nested Type Declarations 🎯](#overview-of-nested-type-declarations-)
        * [Static Member Types 🎯](#static-member-types-)
        * [Non-Static Member Classes 🎯](#non-static-member-classes-)
        * [Local Classes 🎯](#local-classes-)
        * [Static Local Types 🎯](#static-local-types-)
        * [Anonymous Classes 🎯](#anonymous-classes-)
        * [Exam Questions 🎯](#exam-questions--8)
    * [Object Lifetime 🎯](#object-lifetime-)
        * [Garbage Collection 🎯](#garbage-collection-)
        * [Reachable Objects 🎯](#reachable-objects-)
        * [Facilitating Garbage Collection 🎯](#facilitating-garbage-collection-)
        * [Invoking Garbage Collection Programmatically 🎯](#invoking-garbage-collection-programmatically-)
        * [Initializers 🎯](#initializers-)
        * [Field Initializer Expressions 🎯](#field-initializer-expressions-)
        * [Static Initializer Blocks 🎯](#static-initializer-blocks-)
        * [Instance Initializer Blocks 🎯](#instance-initializer-blocks-)
        * [Constructing Initial Object State 🎯](#constructing-initial-object-state-)
        * [Exam Questions 🎯](#exam-questions--9)
    * [Generics 🎯](#generics-)
        * [Introducing Generics 🎯](#introducing-generics-)
        * [Generic Types and Parameterized Types 🎯](#generic-types-and-parameterized-types-)
        * [Collections and Generics 🎯](#collections-and-generics-)
        * [Wildcards 🎯](#wildcards-)
        * [Using References of Wildcard Parameterized Types 🎯](#using-references-of-wildcard-parameterized-types-)
        * [Bounded Type Parameters 🎯](#bounded-type-parameters-)
        * [Generic Methods and Constructors 🎯](#generic-methods-and-constructors-)
        * [Implementing a Simplified Generic Stack 🎯](#implementing-a-simplified-generic-stack-)
        * [Wildcard Capture 🎯](#wildcard-capture-)
        * [Flexibility with Wildcard Parameterized Types 🎯](#flexibility-with-wildcard-parameterized-types-)
        * [Type Erasure 🎯](#type-erasure-)
        * [Implications for Overloading and Overriding 🎯](#implications-for-overloading-and-overriding-)
        * [Limitations and Restrictions on Generic Types 🎯](#limitations-and-restrictions-on-generic-types-)
        * [Exam Questions 🎯](#exam-questions--10)
    * [Collections 🎯](#collections-)
        * [The Java Collections Framework 🎯](#the-java-collections-framework-)
        * [Collections 🎯](#collections--1)
        * [The `Collections` Class 🎯](#the-collections-class-)
        * [Lists 🎯](#lists-)
        * [Declaring References and Constructing ArrayLists 🎯](#declaring-references-and-constructing-arraylists-)
        * [Modifying an `ArrayList<E>` 🎯](#modifying-an-arrayliste-)
        * [Querying an `ArrayList<E>` 🎯](#querying-an-arrayliste-)
        * [Iterating Over an `ArrayList<E>` 🎯](#iterating-over-an-arrayliste-)
        * [Converting an `ArrayList<E>` to an `Array` 🎯](#converting-an-arrayliste-to-an-array-)
        * [Creating `List` Views 🎯](#creating-list-views-)
        * [`Arrays` versus `ArrayLists` 🎯](#arrays-versus-arraylists-)
        * [The `Arrays` Class 🎯](#the-arrays-class-)
        * [Sets 🎯](#sets-)
        * [Sorted Sets and Navigable Sets 🎯](#sorted-sets-and-navigable-sets-)
        * [Queues 🎯](#queues-)
        * [Deques 🎯](#deques-)
        * [Maps 🎯](#maps-)
        * [Map Implementations 🎯](#map-implementations-)
        * [Sorted Maps and Navigable Maps 🎯](#sorted-maps-and-navigable-maps-)
        * [Exam Questions 🎯](#exam-questions--11)
    * [Functional-Style Programming 🎯](#functional-style-programming-)
        * [Functional Interfaces 🎯](#functional-interfaces-)
        * [Lambda Expressions 🎯](#lambda-expressions-)
        * [Lambda Expressions and Anonymous Classes 🎯](#lambda-expressions-and-anonymous-classes-)
        * [Overview of Built-In Functional Interfaces 🎯](#overview-of-built-in-functional-interfaces-)
        * [Suppliers 🎯](#suppliers-)
        * [Predicates 🎯](#predicates-)
        * [Consumers 🎯](#consumers-)
        * [Functions 🎯](#functions-)
        * [Two-Arity Specialization of `Function<T, R>`: `BiFunction<T, U, R>` 🎯](#two-arity-specialization-of-functiont-r-bifunctiont-u-r-)
        * [Extending `Function<T,T>`: `UnaryOperator<T>` 🎯](#extending-functiontt-unaryoperatort-)
        * [Extending `BiFunction<T,T,T>`: `BinaryOperator<T>` 🎯](#extending-bifunctionttt-binaryoperatort-)
        * [Currying Functions 🎯](#currying-functions-)
        * [Method and Constructor References 🎯](#method-and-constructor-references-)
        * [Contexts for Defining Lambda Expressions 🎯](#contexts-for-defining-lambda-expressions-)
        * [Exam Questions 🎯](#exam-questions--12)
    * [`Object` Comparison 🎯](#object-comparison-)
        * [The `Objects` Class 🎯](#the-objects-class-)
        * [Implementing the `equals()` Method 🎯](#implementing-the-equals-method-)
        * [Implementing the `hashCode()` Method 🎯](#implementing-the-hashcode-method-)
        * [Implementing the `java.lang.Comparable<E>` Interface 🎯](#implementing-the-javalangcomparablee-interface-)
        * [Implementing the `java.util.Comparator<E>` Interface 🎯](#implementing-the-javautilcomparatore-interface-)
        * [Exam Questions 🎯](#exam-questions--13)
    * [Streams 🎯](#streams-)
        * [Introduction to Streams](#introduction-to-streams)
        * [Running Example: The CD Record Class](#running-example-the-cd-record-class)
        * [Stream Basics 🎯](#stream-basics-)
        * [Building Streams 🎯](#building-streams-)
        * [Intermediate Stream Operations 🎯](#intermediate-stream-operations-)
        * [The `Optional` Class 🎯](#the-optional-class-)
        * [Terminal Stream Operations 🎯](#terminal-stream-operations-)
        * [Collectors 🎯](#collectors-)
        * [Parallel Streams 🎯](#parallel-streams-)
        * [Exam Questions 🎯](#exam-questions--14)
    * [Date and Time 🎯](#date-and-time-)
        * [Date and Time API Overview 🎯](#date-and-time-api-overview-)
        * [Working with Dates and Times 🎯](#working-with-dates-and-times-)
        * [Using Temporal Units and Temporal Fields 🎯](#using-temporal-units-and-temporal-fields-)
        * [Working with Instants 🎯](#working-with-instants-)
        * [Working with Periods 🎯](#working-with-periods-)
        * [Working with Durations 🎯](#working-with-durations-)
        * [Working with Time Zones and Daylight Savings 🎯](#working-with-time-zones-and-daylight-savings-)
        * [Converting Date and Time Values to Legacy Date](#converting-date-and-time-values-to-legacy-date)
        * [Exam Questions 🎯](#exam-questions--15)
    * [Localization 🎯](#localization-)
        * [Using Locales 🎯](#using-locales-)
        * [Properties Files 🎯](#properties-files-)
        * [Bundling Resources 🎯](#bundling-resources-)
        * [Core API for Formatting and Parsing of Values 🎯](#core-api-for-formatting-and-parsing-of-values-)
        * [Formatting and Parsing Number, Currency, and Percentage Values 🎯](#formatting-and-parsing-number-currency-and-percentage-values-)
        * [Formatting and Parsing Date and Time 🎯](#formatting-and-parsing-date-and-time-)
        * [Formatting and Parsing Messages 🎯](#formatting-and-parsing-messages-)
        * [Exam Questions 🎯](#exam-questions--16)
    * [Java Module System 🎯](#java-module-system-)
        * [Making the Case for Modules 🎯](#making-the-case-for-modules-)
        * [The Modular JDK 🎯](#the-modular-jdk-)
        * [Module Basics 🎯](#module-basics-)
        * [Overview of Module Directives 🎯](#overview-of-module-directives-)
        * [Creating a Modular Application 🎯](#creating-a-modular-application-)
        * [Compiling and Running a Modular Application 🎯](#compiling-and-running-a-modular-application-)
        * [Creating JAR Files 🎯](#creating-jar-files-)
        * [Open Modules and the open Directive 🎯](#open-modules-and-the-open-directive-)
        * [Services 🎯](#services-)
        * [Creating Runtime Images 🎯](#creating-runtime-images-)
        * [Categories of Modules 🎯](#categories-of-modules-)
        * [Migrating to Modules 🎯](#migrating-to-modules-)
        * [Exploring Modules 🎯](#exploring-modules-)
        * [Summary of Selected Operations with the JDK Tools 🎯](#summary-of-selected-operations-with-the-jdk-tools-)
        * [Exam Questions 🎯](#exam-questions--17)
    * [Java I/O 🎯](#java-io-)
        * [Input and Output 🎯](#input-and-output-)
        * [Byte Streams: Input Streams and Output Streams 🎯](#byte-streams-input-streams-and-output-streams-)
        * [Character Streams: Readers and Writers 🎯](#character-streams-readers-and-writers-)
        * [The `Console` Class 🎯](#the-console-class-)
        * [Object Serialization 🎯](#object-serialization-)
        * [Characteristics of a Hierarchical File System 🎯](#characteristics-of-a-hierarchical-file-system-)
        * [Creating Path Objects 🎯](#creating-path-objects-)
        * [Working with Path Objects 🎯](#working-with-path-objects-)
        * [Operations on Directory Entries 🎯](#operations-on-directory-entries-)
        * [Reading and Writing Files Using Paths 🎯](#reading-and-writing-files-using-paths-)
        * [Managing File Attributes 🎯](#managing-file-attributes-)
        * [Creating Directory Entries 🎯](#creating-directory-entries-)
        * [Stream Operations on Directory Entries 🎯](#stream-operations-on-directory-entries-)
        * [Exam Questions 🎯](#exam-questions--18)
    * [Concurrency 🎯](#concurrency-)
        * [Threads and Concurrency 🎯](#threads-and-concurrency-)
        * [Runtime Organization for Thread Execution 🎯](#runtime-organization-for-thread-execution-)
        * [Creating Threads 🎯](#creating-threads-)
        * [Thread Lifecycle 🎯](#thread-lifecycle-)
        * [Thread Issues 🎯](#thread-issues-)
        * [Utility Classes `TimeUnit` and `ThreadLocalRandom`](#utility-classes-timeunit-and-threadlocalrandom)
        * [The Executor Framework 🎯](#the-executor-framework-)
        * [The Fork/Join Framework 🎯](#the-forkjoin-framework-)
        * [Writing Thread-Safe Code 🎯](#writing-thread-safe-code-)
        * [Special-Purpose Synchronizers 🎯](#special-purpose-synchronizers-)
        * [Synchronized Collections and Maps 🎯](#synchronized-collections-and-maps-)
        * [Concurrent Collections and Maps 🎯](#concurrent-collections-and-maps-)
        * [Exam Questions 🎯](#exam-questions--19)
    * [Database Connectivity 🎯](#database-connectivity-)
        * [Introduction to Relational Databases 🎯](#introduction-to-relational-databases-)
        * [Introduction to JDBC 🎯](#introduction-to-jdbc-)
        * [Establishing a Database Connection 🎯](#establishing-a-database-connection-)
        * [Creating and Executing SQL Statements 🎯](#creating-and-executing-sql-statements-)
        * [Processing Query Results 🎯](#processing-query-results-)
        * [Customizing Result Sets 🎯](#customizing-result-sets-)
        * [Discovering Database and ResultSet Metadata 🎯](#discovering-database-and-resultset-metadata-)
        * [Implementing Transaction Control 🎯](#implementing-transaction-control-)
        * [Exam Questions 🎯](#exam-questions--20)
    * [Annotations 🎯](#annotations-)
        * [Basics of Annotations 🎯](#basics-of-annotations-)
        * [Declaring Annotation Types 🎯](#declaring-annotation-types-)
        * [Applying Annotations 🎯](#applying-annotations-)
        * [Meta-Annotations 🎯](#meta-annotations-)
        * [Selected Standard Annotations 🎯](#selected-standard-annotations-)
        * [Processing Annotations 🎯](#processing-annotations-)
        * [Exam Questions 🎯](#exam-questions--21)
    * [Secure Coding](#secure-coding)
        * [Application Security Overview](#application-security-overview)
        * [Security Threat Categories](#security-threat-categories)
        * [Java Security Policies](#java-security-policies)
        * [Additional Security Guidelines](#additional-security-guidelines)
    * [Java Logging API Overview](#java-logging-api-overview)
        * [Purpose of the Logging API](#purpose-of-the-logging-api)
        * [Configuring Logging](#configuring-logging)
        * [Writing Log Messages](#writing-log-messages)
        * [Applying Guarded Logging](#applying-guarded-logging)
    * [How to Write Doc Comments for the Javadoc Tool](#how-to-write-doc-comments-for-the-javadoc-tool)

<!-- TOC -->


------------------------------------------------------------------------------------------------------------------

## Basics of Java Programming

### The Java Ecosystem

- There are different Java platforms each one provides a hardware/operating system – specific JVM and an API (application programming interface) to develop applications for that platform, each targeting different application domains:
    - **Java SE (Standard Edition)**:
        - The Java SE platform provides the core functionality of the language.
        - designed for developing desktop and server environments
        - **Java EE, also known as Jakarta EE (Enterprise Edition)**:
            - The Java EE platform is a superset of the Java SE platform and, as the most extensive of the three platforms, targets enterprise application development
            - designed for developing enterprise applications
    - **Java ME (Micro Edition)**:
        - The Java ME platform is a subset of the Java SE platform, having a small footprint, and is suitable for developing mobile and embedded applications
        - designed for embedded systems, such as mobile devices and set-top boxes
    - **Java Card**:
        - The Java Card platform allows development of embedded applications that have a very tiny memory footprint, targeting devices like smart cards.
        - designed for tiny memory footprint devices, such as smart cards
-
-

### Classes

### Objects

### Instance Members

### Static Members

### Inheritance

### Aggregation

### Sample Java Program

### Program Output

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Basic Elements, Primitive Data Types, and Operators 🎯

### Basic Language Elements

### Primitive Data Types 🎯

### Conversions 🎯

### Type Conversion Contexts 🎯

### Precedence and Associativity Rules `for` Operators 🎯

### Evaluation Order of Operands 🎯

### The Simple Assignment Operator `=` 🎯

### Arithmetic Operators: `*`, `/`, `%`, `+`, `-` 🎯

### The Binary String Concatenation Operator `+` 🎯

### Variable Increment and Decrement Operators: `++`,`--` 🎯

### Boolean Expressions 🎯

### Relational Operators: `<`, `<=,` `>`, `>=` 🎯

### Equality 🎯

### Boolean Logical Operators: `!`, `^`, `&`, `|` 🎯

### Conditional Operators: `&&`, `||` 🎯

### Integer Bitwise Operators: `~`, `&`, `|`, `^` 🎯

### Shift Operators: `<<`, `>>`, `>>>` 🎯

### The Conditional Operator `?:` 🎯

### Other Operators: `new`, `[]`, `instanceof`, `-`> 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Declarations 🎯

### Class Declarations 🎯

### Method Declarations 🎯

### Statements 🎯

### Variable Declarations 🎯

### Instance Methods and the Object Reference `this` 🎯

### Method Overloading 🎯

### Constructors 🎯

### Static Member Declarations 🎯

### Arrays 🎯

### Parameter Passing

### Variable Arity Methods 🎯

### The `main()` Method

### Local Variable Type Inference 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Control Flow 🎯

### Selection Statements 🎯

### The `switch` Statement 🎯

### The `switch` Expression 🎯

### Iteration Statements 🎯

### The `while` Statement 🎯

### The `do`-`while` Statement 🎯

### The `for(;;)` Statement 🎯

### The `for(:)` Statement 🎯

### Transfer Statements 🎯

### Labeled Statements 🎯

### The `break` Statement 🎯

### The `continue` Statement 🎯

### The `return` Statement 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Object-Oriented Programming 🎯

### Implementing Inheritance 🎯

### The Object Reference super 🎯

### Chaining Constructors Using `this()` and `super()` 🎯

### Abstract Classes and Methods 🎯

### Final Declarations

### Interfaces 🎯

### Arrays and Subtyping

### Reference Values and Conversions

### Reference Value Assignment Conversions

### Method Invocation Conversions Involving References

### Reference Casting and the instanceof Operator 🎯

### Polymorphism 🎯

### Enum Types 🎯

### Record Classes 🎯

### Sealed Classes and Interfaces 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Access Control 🎯

### Design Principle: Encapsulation 🎯

### Java Source File Structure

### Packages

### Searching for Classes on the Class Path

### Access Modifiers

### Scope Rules 🎯

### Implementing Immutability 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Exception Handling 🎯

### Stack-Based Execution and Exception Propagation

### Exception Types 🎯

### Exception Handling: `try`, `catch`, and `finally` 🎯

### The `throw` Statement

### The `throws` Clause

### The Multi-`catch` Clause 🎯

### The `try`-with-resources Statement 🎯

### Advantages of Exception Handling

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Selected API Classes 🎯

### Overview of the `java.lang` Package

### The `Object` Class

### The Wrapper Classes 🎯

### The `String` Class 🎯

### The `StringBuilder` Class 🎯

### The `Math` Class 🎯

### The `Random` Class

### Using Big Numbers

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Nested Type Declarations 🎯

### Overview of Nested Type Declarations 🎯

### Static Member Types 🎯

### Non-Static Member Classes 🎯

### Local Classes 🎯

### Static Local Types 🎯

### Anonymous Classes 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Object Lifetime 🎯

### Garbage Collection 🎯

### Reachable Objects 🎯

### Facilitating Garbage Collection 🎯

### Invoking Garbage Collection Programmatically 🎯

### Initializers 🎯

### Field Initializer Expressions 🎯

### Static Initializer Blocks 🎯

### Instance Initializer Blocks 🎯

### Constructing Initial Object State 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Generics 🎯

### Introducing Generics 🎯

### Generic Types and Parameterized Types 🎯

### Collections and Generics 🎯

### Wildcards 🎯

### Using References of Wildcard Parameterized Types 🎯

### Bounded Type Parameters 🎯

### Generic Methods and Constructors 🎯

### Implementing a Simplified Generic Stack 🎯

### Wildcard Capture 🎯

### Flexibility with Wildcard Parameterized Types 🎯

### Type Erasure 🎯

### Implications for Overloading and Overriding 🎯

### Limitations and Restrictions on Generic Types 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Collections 🎯

### The Java Collections Framework 🎯

### Collections 🎯

### The `Collections` Class 🎯

### Lists 🎯

### Declaring References and Constructing ArrayLists 🎯

### Modifying an `ArrayList<E>` 🎯

### Querying an `ArrayList<E>` 🎯

### Iterating Over an `ArrayList<E>` 🎯

### Converting an `ArrayList<E>` to an `Array` 🎯

### Creating `List` Views 🎯

### `Arrays` versus `ArrayLists` 🎯

### The `Arrays` Class 🎯

### Sets 🎯

### Sorted Sets and Navigable Sets 🎯

### Queues 🎯

### Deques 🎯

### Maps 🎯

### Map Implementations 🎯

### Sorted Maps and Navigable Maps 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Functional-Style Programming 🎯

### Functional Interfaces 🎯

### Lambda Expressions 🎯

### Lambda Expressions and Anonymous Classes 🎯

### Overview of Built-In Functional Interfaces 🎯

### Suppliers 🎯

### Predicates 🎯

### Consumers 🎯

### Functions 🎯

### Two-Arity Specialization of `Function<T, R>`: `BiFunction<T, U, R>` 🎯

### Extending `Function<T,T>`: `UnaryOperator<T>` 🎯

### Extending `BiFunction<T,T,T>`: `BinaryOperator<T>` 🎯

### Currying Functions 🎯

### Method and Constructor References 🎯

### Contexts for Defining Lambda Expressions 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## `Object` Comparison 🎯

### The `Objects` Class 🎯

### Implementing the `equals()` Method 🎯

### Implementing the `hashCode()` Method 🎯

### Implementing the `java.lang.Comparable<E>` Interface 🎯

### Implementing the `java.util.Comparator<E>` Interface 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Streams 🎯

### Introduction to Streams

### Running Example: The CD Record Class

### Stream Basics 🎯

### Building Streams 🎯

### Intermediate Stream Operations 🎯

### The `Optional` Class 🎯

### Terminal Stream Operations 🎯

### Collectors 🎯

### Parallel Streams 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Date and Time 🎯

### Date and Time API Overview 🎯

### Working with Dates and Times 🎯

### Using Temporal Units and Temporal Fields 🎯

### Working with Instants 🎯

### Working with Periods 🎯

### Working with Durations 🎯

### Working with Time Zones and Daylight Savings 🎯

### Converting Date and Time Values to Legacy Date

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Localization 🎯

### Using Locales 🎯

### Properties Files 🎯

### Bundling Resources 🎯

### Core API for Formatting and Parsing of Values 🎯

### Formatting and Parsing Number, Currency, and Percentage Values 🎯

### Formatting and Parsing Date and Time 🎯

### Formatting and Parsing Messages 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Java Module System 🎯

### Making the Case for Modules 🎯

### The Modular JDK 🎯

### Module Basics 🎯

### Overview of Module Directives 🎯

### Creating a Modular Application 🎯

### Compiling and Running a Modular Application 🎯

### Creating JAR Files 🎯

### Open Modules and the open Directive 🎯

### Services 🎯

### Creating Runtime Images 🎯

### Categories of Modules 🎯

### Migrating to Modules 🎯

### Exploring Modules 🎯

### Summary of Selected Operations with the JDK Tools 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Java I/O 🎯

### Input and Output 🎯

### Byte Streams: Input Streams and Output Streams 🎯

### Character Streams: Readers and Writers 🎯

### The `Console` Class 🎯

### Object Serialization 🎯

### Characteristics of a Hierarchical File System 🎯

### Creating Path Objects 🎯

### Working with Path Objects 🎯

### Operations on Directory Entries 🎯

### Reading and Writing Files Using Paths 🎯

### Managing File Attributes 🎯

### Creating Directory Entries 🎯

### Stream Operations on Directory Entries 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Concurrency 🎯

### Threads and Concurrency 🎯

### Runtime Organization for Thread Execution 🎯

### Creating Threads 🎯

### Thread Lifecycle 🎯

### Thread Issues 🎯

### Utility Classes `TimeUnit` and `ThreadLocalRandom`

### The Executor Framework 🎯

### The Fork/Join Framework 🎯

### Writing Thread-Safe Code 🎯

### Special-Purpose Synchronizers 🎯

### Synchronized Collections and Maps 🎯

### Concurrent Collections and Maps 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Database Connectivity 🎯

### Introduction to Relational Databases 🎯

### Introduction to JDBC 🎯

### Establishing a Database Connection 🎯

### Creating and Executing SQL Statements 🎯

### Processing Query Results 🎯

### Customizing Result Sets 🎯

### Discovering Database and ResultSet Metadata 🎯

### Implementing Transaction Control 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Annotations 🎯

### Basics of Annotations 🎯

### Declaring Annotation Types 🎯

### Applying Annotations 🎯

### Meta-Annotations 🎯

### Selected Standard Annotations 🎯

### Processing Annotations 🎯

### Exam Questions 🎯

------------------------------------------------------------------------------------------------------------------

## Secure Coding

### Application Security Overview

### Security Threat Categories

### Java Security Policies

### Additional Security Guidelines

------------------------------------------------------------------------------------------------------------------

## Java Logging API Overview

### Purpose of the Logging API

### Configuring Logging

### Writing Log Messages

### Applying Guarded Logging

------------------------------------------------------------------------------------------------------------------

## [How to Write Doc Comments for the Javadoc Tool](https://www.oracle.com/technical-resources/articles/java/javadoc-tool.html)

### Introduction

#### Principles

#### Terminology

#### Source Files

### Writing Doc Comments

#### Format of a Doc Comment

#### Doc Comment Checking Tool

#### Descriptions

#### A Style Guide

#### Tag Conventions (`@tag`)

#### Documenting Default Constructors

#### Documenting Exceptions with `@throws` Tag

#### Package-Level Comments

#### Documenting Anonymous Inner Classes

#### Including Images

#### Examples of Doc Comments

#### Troubleshooting Curly Quotes (Microsoft Word)