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
- [Oracle](https://education.oracle.com/buy-exam) sells an exam attempt (previously called a certification voucher) to take the exam
- Be sure to get an exam attempt for Oracle Technology Exams, which covers Java certification exams
- After getting the exam attempt, you can schedule to take the online proctored exam when they are ready at the [Oracle MyLearn portal](https://mylearn.oracle.com/)
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
- Using the Allotted Time
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
    - Indications on how well you did in each category within the goals. Candidates who fail the exam should pay close attention to this information. If you're planning to retake the exam, it may give a good indication of which topics need closer attention
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
        * [Key Features of Java](#key-features-of-java)
        * [Classes](#classes)
        * [Objects](#objects)
            * [Class Instantiation, Reference Values, and References](#class-instantiation-reference-values-and-references)
        * [Instance Members](#instance-members)
            * [Invoking Methods](#invoking-methods)
        * [Static Members](#static-members)
            * [Terminology for Class Members](#terminology-for-class-members)
        * [Inheritance](#inheritance)
        * [Aggregation](#aggregation)
        * [Sample Java Program](#sample-java-program)
            * [Essential Elements of a Java Program](#essential-elements-of-a-java-program)
            * [Compiling a Program](#compiling-a-program)
            * [Running a Program](#running-a-program)
            * [Running a Single-File Source-Code Program](#running-a-single-file-source-code-program)
        * [Program Output](#program-output)
            * [Formatted Output](#formatted-output)
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
        * [Exam Questions 🎯](#exam-questions-)
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
        * [Exam Questions 🎯](#exam-questions--1)
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
        * [Exam Questions 🎯](#exam-questions--2)
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
        * [Exam Questions 🎯](#exam-questions--3)
    * [Access Control 🎯](#access-control-)
        * [Design Principle: Encapsulation 🎯](#design-principle-encapsulation-)
        * [Java Source File Structure](#java-source-file-structure)
        * [Packages](#packages)
        * [Searching for Classes on the Class Path](#searching-for-classes-on-the-class-path)
        * [Access Modifiers](#access-modifiers)
        * [Scope Rules 🎯](#scope-rules-)
        * [Implementing Immutability 🎯](#implementing-immutability-)
        * [Exam Questions 🎯](#exam-questions--4)
    * [Exception Handling 🎯](#exception-handling-)
        * [Stack-Based Execution and Exception Propagation](#stack-based-execution-and-exception-propagation)
        * [Exception Types 🎯](#exception-types-)
        * [Exception Handling: `try`, `catch`, and `finally` 🎯](#exception-handling-try-catch-and-finally-)
        * [The `throw` Statement](#the-throw-statement)
        * [The `throws` Clause](#the-throws-clause)
        * [The Multi-`catch` Clause 🎯](#the-multi-catch-clause-)
        * [The `try`-with-resources Statement 🎯](#the-try-with-resources-statement-)
        * [Advantages of Exception Handling](#advantages-of-exception-handling)
        * [Exam Questions 🎯](#exam-questions--5)
    * [Selected API Classes 🎯](#selected-api-classes-)
        * [Overview of the `java.lang` Package](#overview-of-the-javalang-package)
        * [The `Object` Class](#the-object-class)
        * [The Wrapper Classes 🎯](#the-wrapper-classes-)
        * [The `String` Class 🎯](#the-string-class-)
        * [The `StringBuilder` Class 🎯](#the-stringbuilder-class-)
        * [The `Math` Class 🎯](#the-math-class-)
        * [The `Random` Class](#the-random-class)
        * [Using Big Numbers](#using-big-numbers)
        * [Exam Questions 🎯](#exam-questions--6)
    * [Nested Type Declarations 🎯](#nested-type-declarations-)
        * [Overview of Nested Type Declarations 🎯](#overview-of-nested-type-declarations-)
        * [Static Member Types 🎯](#static-member-types-)
        * [Non-Static Member Classes 🎯](#non-static-member-classes-)
        * [Local Classes 🎯](#local-classes-)
        * [Static Local Types 🎯](#static-local-types-)
        * [Anonymous Classes 🎯](#anonymous-classes-)
        * [Exam Questions 🎯](#exam-questions--7)
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
        * [Exam Questions 🎯](#exam-questions--8)
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
        * [Exam Questions 🎯](#exam-questions--9)
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
        * [Exam Questions 🎯](#exam-questions--10)
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
        * [Exam Questions 🎯](#exam-questions--11)
    * [`Object` Comparison 🎯](#object-comparison-)
        * [The `Objects` Class 🎯](#the-objects-class-)
        * [Implementing the `equals()` Method 🎯](#implementing-the-equals-method-)
        * [Implementing the `hashCode()` Method 🎯](#implementing-the-hashcode-method-)
        * [Implementing the `java.lang.Comparable<E>` Interface 🎯](#implementing-the-javalangcomparablee-interface-)
        * [Implementing the `java.util.Comparator<E>` Interface 🎯](#implementing-the-javautilcomparatore-interface-)
        * [Exam Questions 🎯](#exam-questions--12)
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
        * [Exam Questions 🎯](#exam-questions--13)
    * [Date and Time 🎯](#date-and-time-)
        * [Date and Time API Overview 🎯](#date-and-time-api-overview-)
        * [Working with Dates and Times 🎯](#working-with-dates-and-times-)
        * [Using Temporal Units and Temporal Fields 🎯](#using-temporal-units-and-temporal-fields-)
        * [Working with Instants 🎯](#working-with-instants-)
        * [Working with Periods 🎯](#working-with-periods-)
        * [Working with Durations 🎯](#working-with-durations-)
        * [Working with Time Zones and Daylight Savings 🎯](#working-with-time-zones-and-daylight-savings-)
        * [Converting Date and Time Values to Legacy Date](#converting-date-and-time-values-to-legacy-date)
        * [Exam Questions 🎯](#exam-questions--14)
    * [Localization 🎯](#localization-)
        * [Using Locales 🎯](#using-locales-)
        * [Properties Files 🎯](#properties-files-)
        * [Bundling Resources 🎯](#bundling-resources-)
        * [Core API for Formatting and Parsing of Values 🎯](#core-api-for-formatting-and-parsing-of-values-)
        * [Formatting and Parsing Number, Currency, and Percentage Values 🎯](#formatting-and-parsing-number-currency-and-percentage-values-)
        * [Formatting and Parsing Date and Time 🎯](#formatting-and-parsing-date-and-time-)
        * [Formatting and Parsing Messages 🎯](#formatting-and-parsing-messages-)
        * [Exam Questions 🎯](#exam-questions--15)
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
        * [Exam Questions 🎯](#exam-questions--16)
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
        * [Exam Questions 🎯](#exam-questions--17)
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
        * [Exam Questions 🎯](#exam-questions--18)
    * [Database Connectivity 🎯](#database-connectivity-)
        * [Introduction to Relational Databases 🎯](#introduction-to-relational-databases-)
        * [Introduction to JDBC 🎯](#introduction-to-jdbc-)
        * [Establishing a Database Connection 🎯](#establishing-a-database-connection-)
        * [Creating and Executing SQL Statements 🎯](#creating-and-executing-sql-statements-)
        * [Processing Query Results 🎯](#processing-query-results-)
        * [Customizing Result Sets 🎯](#customizing-result-sets-)
        * [Discovering Database and ResultSet Metadata 🎯](#discovering-database-and-resultset-metadata-)
        * [Implementing Transaction Control 🎯](#implementing-transaction-control-)
        * [Exam Questions 🎯](#exam-questions--19)
    * [Annotations 🎯](#annotations-)
        * [Basics of Annotations 🎯](#basics-of-annotations-)
        * [Declaring Annotation Types 🎯](#declaring-annotation-types-)
        * [Applying Annotations 🎯](#applying-annotations-)
        * [Meta-Annotations 🎯](#meta-annotations-)
        * [Selected Standard Annotations 🎯](#selected-standard-annotations-)
        * [Processing Annotations 🎯](#processing-annotations-)
        * [Exam Questions 🎯](#exam-questions--20)
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
        * [Java Logging Best Practices](#java-logging-best-practices)
    * [How to Write Doc Comments for the Javadoc Tool](#how-to-write-doc-comments-for-the-javadoc-tool)
        * [Introduction](#introduction)
            * [Principles](#principles)
            * [Terminology](#terminology)
            * [Source Files](#source-files)
        * [Writing Doc Comments](#writing-doc-comments)
            * [Format of a Doc Comment](#format-of-a-doc-comment)
            * [Doc Comment Checking Tool](#doc-comment-checking-tool)
            * [Descriptions](#descriptions)
            * [A Style Guide](#a-style-guide)
            * [Tag Conventions (`@tag`)](#tag-conventions-tag)
            * [Documenting Default Constructors](#documenting-default-constructors)
            * [Documenting Exceptions with `@throws` Tag](#documenting-exceptions-with-throws-tag)
            * [Package-Level Comments](#package-level-comments)
            * [Documenting Anonymous Inner Classes](#documenting-anonymous-inner-classes)
            * [Including Images](#including-images)
            * [Examples of Doc Comments](#examples-of-doc-comments)
            * [Troubleshooting Curly Quotes (Microsoft Word)](#troubleshooting-curly-quotes-microsoft-word)

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
        - The Java Card platform allows development of embedded applications that have a very tiny memory footprint, focusing on devices like smart cards.
        - designed for tiny memory footprint devices, such as smart cards
- Java program developed for one Java platform will not necessarily run under the JVM of another Java platform. The JVM must be compatible with the Java platform used to develop the application.
- The API and the tools for developing and running Java applications are bundled together as the JDK
- One needs to install the JDK to both develop and run Java programs, Starting with Java 11, JRE (Java Runtime Environment) is no longer available as a stand-alone bundle providing runtime support for execution of Java programs, but it continues to be a subset of the now modular JDK
- However, to deploy Java programs, the JDK tool _**jlink**_ can be used to create a runtime image that includes the program code and the necessary runtime support to run the program

### Key Features of Java

- **_Multi-paradigm Programming:_**
    - Java supports **_object-oriented programming paradigm_** in which the properties (fields) of an object and its behavior (methods) are encapsulated in the object
    - The objects communicate through method calls in a procedural manner, so Java also incorporates the **_procedural programming paradigm_**.
    - Encapsulation ensures that objects are immune to tampering except when manipulated through their public interface
    - Encapsulation exposes only **_what_** an object does and not **_how_** it does it, so that its implementation can be changed with minimal impact on its clients
    - Java has also evolved to support the **_functional-style programming paradigm_** with the introduction of lambda expressions and their implementation using functional interfaces
- **_Bytecode Interpreted by the JVM:_**
    - Java programs are compiled to bytecode that is interpreted by the JVM
    - Various optimization technologies (e.g., just-in-time [JIT] delivery) have led to the JVM becoming a lean and mean virtual machine with regard to performance, stability, and security.
    - Many other languages, such as Scala, Groovy, and Clojure, now compile to bytecode and seamlessly execute on the JVM
- **_Architecture-Neutral and Portable Bytecode:_**
    - The often-cited slogan **_"Write once, run everywhere"_** is true only if a compatible JVM is available for the hardware and software platform
    - The specification of the bytecode is architecture neutral, meaning it is independent of any hardware architecture.
    - It is executed by a readily available hardware and operating system–specific JVM
- **_Simplicity:_**
    - Although Java borrows heavily from the C++ programming language, certain features deemed problematic were not incorporated into its design.
    - Java does not have a preprocessor, and it does not allow pointer handling, user-defined operator overloading, or multiple class inheritance
    - Java opted for automatic garbage collection, which frees the programmer from dealing with many issues related to memory management, such as memory leaks
- **_Dynamic and Distributed:_**
    - The JVM can dynamically load class libraries from the local file system as well as from machines on the network, when those libraries are needed at runtime. This feature facilitates linking the code as and when necessary during the execution of a program.
    - It is also possible to programmatically query a class or an object at runtime about its meta-information, such as its methods and fields (Reflection)
    - Objects are able to communicate across networks using various communication protocols and technologies, such as Remote Method Invocation (RMI) and socket connections
- **_Robust and Secure:_**
    - The compiler guarantees runtime execution if the code compiles without errors
    - Runtime index checks for arrays and strings, automatic garbage collection, and elimination of pointers are some of the features of Java that promote reliability
    - The module system further enhances encapsulation and configuration
    - Java provides multilevel protection from malicious code
        - The language does not allow direct access to memory
        - A bytecode verifier determines whether any untrusted code loaded in the JVM is safe
        - The sandbox model is used to confine and execute any untrusted code, limiting the damage that such code can cause
- **_High Performance and Multithreaded:_**
    - The performance of Java programs has improved significantly with various optimizations that are applied to bytecode at runtime by the JVM.
    - JIT feature monitors the program at runtime to identify performance-critical bytecode (called hotspots) that can be optimized. Such code is usually translated to machine code to boost performance
    - The performance achieved by the JVM is a balance between native code execution and interpretation of fully scripted languages
    - Java brings elements of functional-style programming into the language, providing language constructs
      (lambda expressions and functional interfaces) and API support (through its Concurrent and Stream APIs) to efficiently use the many cores to process large amounts of data in parallel

### Classes

- One of the fundamental ways in which we handle complexity is by using **_abstractions_**, OOP is modeling abstractions, using classes and objects
- An abstraction denotes the essential properties and behaviors of an object that differentiate it from other objects.
- A `class` denotes a category of objects, and acts as a blueprint for creating objects
- A class models an abstraction by defining the properties and behaviors of the objects representing the abstraction
- An `object` exhibits the **_properties_** and **_behaviors_** defined by its class
- The properties of an object of a class are also called _attributes_, and are defined by _fields_ in Java
- A _field_ in a class is a variable that can store a value that represents a particular _property_ of an object
- The behaviors of an object of a class are also known as _operations_, and are defined using methods in Java
- Fields and methods in a class declaration are collectively called _members_.
- An important distinction is made between the **_contract_** and **_the implementation_** that a class provides for its objects
- The contract defines **_which_** services are provided, and the implementation defines **_how_** the class provides these services
- Clients (i.e., other objects) need only know the contract of an object, and not its implementation, to avail themselves of the object’s services
- a constructor is executed when an object is created from the class

### Objects

#### Class Instantiation, Reference Values, and References

- The process of creating objects from a class is called **_instantiation_**
- An object is an instance of a class
- The object is constructed using the class as a blueprint and is a concrete instance of the abstraction that the class represents
- An object must be created before it can be used in a program.
- A **_reference_** value is returned when an object is created
- A reference value **_uniquely_** denotes a particular object
- A **_variable_** denotes a location in memory where a value can be stored.
- An object reference (or simply reference) is a variable that can store a reference value.
- Thus, a reference provides a handle to an object, as it can indirectly denote an object whose reference value it holds
- In Java, an object can only be manipulated by a reference that holds its reference value
- Direct access to the reference value is not permitted like the case in c++
- This setup for manipulating objects requires that a reference be declared, a class be instantiated to create an object, and the reference value of the object created be stored in the reference
    - `Point2D p1 = new Point2D(10, 20);`
    - the left-hand side of the assignment operator (`=`) declares that `p1` is a reference of class `Point2D`
    - The reference `p1`, therefore, can refer to objects of class `Point2D`
    - The right-hand side of the assignment operator creates an **_object_** of class `Point2D`
    - This step involves using the `new` operator in conjunction with a call to a **_constructor_** of the class (new Point2D(10, 20))
    - The `new` operator creates an instance of the `Point2D` class and returns the reference value of this instance
    - The arguments passed in the constructor call are used to initialize the x and the y fields, respectively
    - The assignment operator stores the reference value in the reference p1 declared on the left-hand side of the assignment operator.
    - The reference p1 can now be used to manipulate the object whose reference value it holds
- The fields of an object are also called instance variables. The values of the instance variables in an object constitute its state
- Two distinct objects can have the same state if their instance variables have the same values
- Objects in Java do not have names, but rather are denoted by references

### Instance Members

- The methods of an object define its behavior; such methods are called instance methods.
- The **_implementation_** of the methods is shared by all instances of the class
- Instance variables and instance methods, which belong to objects, are collectively called instance members, to distinguish them from static members, which only belong to the class
- Use of the dot notation is governed by the **_accessibility_** of the member
    - If The methods of the class are `public` then they can be called by the clients of the class
    - If the fields of the class are `private` then they can't be called by the clients of the class

#### Invoking Methods

- Objects communicate by calling methods on each other
- Trying to invoke a method that's not defined in the class results in a compile-time error.
- Typically, a class provides public methods to access values in its private fields,

### Static Members

- In some cases, certain members should belong only to the class; that is, they should not be part of any instance of the class
- Such members are called `static` **_members_**
- Fields and methods that are static members are easily distinguishable in a class declaration as they must always be declared with the keyword `static`
- Clients can access static members in the class by using the class name
- Static members can also be accessed via **_object references_**, although doing so **_is not encouraged_**
- Static members in a class can be accessed both by the class name and via object references, but instance members can be accessed only by object references

![Members of a Class](./images/Members%20of%20a%20Class.png "Members of a Class")

#### Terminology for Class Members

|    Terminology    | Definition                                                                                                                                                                                      |
|:-----------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Instance members  | The instance variables and instance methods of an object. They can be accessed or invoked only through an object reference                                                                      |
| Instance variable | A field that is allocated when the class is instantiated (i.e., when an object of the class is created). Also called **_a non-static field_** or just a **_field_** when the context is obvious |
|  Instance method  | A method that belongs to an instance of the class. Objects of the same class share its implementation                                                                                           |
|  Static members   | The static variables and static methods of a class. They can be accessed or invoked either by using the class name or through an object reference                                               |
|  Static variable  | A field that is allocated when the class is loaded. It belongs to the class, and not to any specific object of the class. Also called a static field or a class variable                        |
|   Static method   | A method that belongs to the class, and not to any object of the class. Also called a **_class method_**                                                                                        |

### Inheritance

- There are two fundamental mechanisms for building new classes from existing ones: **_inheritance_** and **_aggregation_**
- It makes sense to inherit from an existing class `Vehicle` to define a class `Car`, since a car **_is a_** vehicle
- The class `Vehicle` **_has_** several parts; therefore, it makes sense to define a **_composite_** object of the class `Vehicle` that has _**constituent**_ objects of such classes as `Engine`, `Axle`, and `GearBox`, which _**make up**_ a vehicle.
- The inherited classes are called **_subclass_** and the parent classes are called **_superclass_**
- The **_superclass_** is the **_generalization_** and the **_subclass_** is the **_specialization_**
- In Java, deriving a new class from an existing class requires the use of the `extends` clause in the subclass declaration
- A subclass can extend only one superclass
- Note that the subclass reference can invoke the inherited methods in the superclass

### Aggregation

- An **_association_** defines a static relationship between objects of two classes
- One such **_association_**, called **_aggregation_** (also known as **_composition_**), expresses how an object uses other objects
- Java supports aggregation of objects by reference, since objects cannot contain other objects explicitly
- By default, Java uses aggregation when fields denoting objects are declared in a class declaration
- Typically, an aggregate object delegates its tasks to its constituent objects

### Sample Java Program

- The term **_program_** and **application** refers to source code that is compiled and directly executed
- To create a program in Java, the program must have a class that defines a method named `main`, which is invoked at runtime to start the execution of the program.
- The class with this `main()` method is known as the **_entry point of the program_**

#### Essential Elements of a Java Program

- The method header of this `main()` method must be declared as shown in the following method stub

```java
public static void main(String[] args) // Method header
{ /* Implementation */ }
```

- The `main()` method has `public` access—that is, it is accessible from any class
- The keyword `static` means the method belongs to the class
- The keyword `void` indicates that the method does not return any value
- The parameter `args` is an array of strings that can be used to pass information to the `main()` method when execution starts

#### Compiling a Program

- The JDK provides tools for compiling and running programs
- The classes in the Java SE Platform API are already compiled, and the JDK tools know where to find them
- Java source files can be compiled using the **_Java Language Compiler_**, javac, which is part of the JDK.
- Each source file name has the extension `.java`
- Each class declaration in a source file is compiled into a separate **_class_** file, containing its **_Java bytecode_**
- The name of this file comprises the name of the class with **_.class_** as its extension
- This `javac` command creates the class files that contain Java bytecode
    - `> javac ClassA.java ClassB.java ClassC.java` -> `ClassA.class`, `ClassB.class` and `ClassC.class`
- Although a Java source file can contain more than one class declaration, the Java compiler enforces the rule that there can only be at the most one class in the source file that has `public` access
- If there is a `public` class in the source file, the name of the source file must be the name of the `public` class with `.java` as its extension
- In the absence of a public class in the source file, the name of the file can be arbitrary, but still with the `.java` extension
- Regardless, each class declaration in a source file is compiled into a separate .class file.

#### Running a Program

- It is the bytecode in the class files executed when a Java program is run—the source code is immaterial in this regard
- A Java program is run by the **_Java Application Launcher_**, `java`, which is also part of the JDK
- The `java` command creates an instance of the JVM that executes the bytecode.
    - `> java ClassA`
- Note that only the name of the class that is the entry point of the program is specified, resulting in the execution starting in the `main()` method of the specified class
- The program terminates when the execution of the `main()` method is completed

#### Running a Single-File Source-Code Program

- Typically, Java source code is first compiled by the `javac` command to Java bytecode in class files and then the bytecode in the class files is executed by the `java` command.
- The compilation step can be omitted if the complete source code of the program is contained in a **_single_** source file, meaning that all class declarations that comprise the program are declared in one source file
    - `> java ClassA.java`
- Note that no class files are created. The source code is compiled fully in memory and executed
- To run a single-file source-code program, the following conditions must be met:
    - The single source file must contain **_all_** source code for the program
    - Although there can be several class declarations in the source file, the **_first_** class declaration in the source file must provide the `main()` method; that is, it must be the entry point of the program.
    - There must not exist **_class_** files corresponding to the class declarations in the single source file that are accessible by the `java` command
- Unlike the `javac` command, the name of the single source file (e.g., Demo-App.java) need not be a valid class name, **but it must have the `.java` extension**
- Also unlike the `javac` command, the `java` command allows several `public` classes in the single source file **_(only `public` classes in the Demo-App.java file)._**

### Program Output

- Data produced by a program is called **_output_**. This output can be sent to different devices.
- A Java program can send its output to the terminal window using an object called **_standard out_**
- This object, which can be accessed using the `public static final` field out in the `System` class, is an object of the class `java.io.PrintStream`
    - These methods convert values to their text representation and print the resulting string
    - The print methods convert a `primitive` value to a string that represents its **_literal value_**, and then print the resulting string
    - An object is first converted to its text representation by calling its `toString()` method implicitly, if it is not already called explicitly on the object
- The `toString()` method called on a `String` object returns the `String` object itself
- As string literals are String objects, the following statements will print the same result:
    - `System.out.println("Stranger Strings".toString()); // Stranger Strings`
    - `System.out.println("Stranger Strings"); // Stranger Strings`
- The `println()` method always terminates the current line, which results in the cursor being moved to the beginning of the next line.
    - The `print()` method prints its argument to the terminal window, but it does not terminate the current line
- To terminate a line without printing any values, we can use the no-argument `println()` method: `System.out.println();`

#### Formatted Output

- For more control over how the values are printed, we can format the output. The following method of the java.io.PrintStream class can be used for this purpose:
    - `PrintStream printf(String format, Object... args)`
        - The `String` parameter format specifies how formatting will be done
        - It contains **_format specifications_** that determine how each later value in the parameter args will be formatted and printed
        - The parameter declaration `Object... args` represents an array of zero or more arguments to be formatted and printed.
        - The resulting string from the formatting will be printed to the **_destination stream_**. (`System.out` will print to the **_standard out_** object.)
        - **_Any error in the format string will result in a runtime exception_**
        - This method returns the `PrintStream` on which the method is invoked, and **_can be ignored_**
        - `System.out.printf("Formatted values|%5d|%8.3f|%5s|%n",2016, Math.PI, "Hi");`
            - At runtime, the following line is printed in the terminal window: `Formatted values| 2016| 3.142| Hi|`
        - The letter in the format specifier indicates the type of value to format.
            - `%d` -> Integer
            - `%f` -> Float
            - `%s` -> String or Any Object
            - `%n` -> Line separator
- Format Specifier Examples

|   Parameter value    | Format spec | Example value | String printed |                                                                 Description                                                                  |
|:--------------------:|:-----------:|:-------------:|:--------------:|:--------------------------------------------------------------------------------------------------------------------------------------------:|
|    Integer Value     |   `"%d"`    |      123      |     "123"      |                                                Occupies as many character positions as needed                                                |
|    Integer Value     |   `"%6d"`   |      123      |    "   123"    |           Occupies six character positions and is right-justified. The printed string is padded with leading spaces, if necessary            |
| Floating-point value |   `"%f"`    |     4.567     |   "4.567000"   |                            Occupies as many character positions as needed, but always includes six decimal places                            |
| Floating-point value |  `"%.2f"`   |     4.567     |     "4.57"     |    Occupies as many character positions as needed, but includes only two decimal places. The value is rounded in the output, if necessary    |
| Floating-point value |  `"%6.2f"`  |     4.567     |   "   4.57"    | Occupies six character positions, including the decimal point, and uses two decimal places. The value is rounded in the output, if necessary |
|      Any object      |   `"%s"`    |     "Hi!"     |     "Hi!"      |                             The text representation of the object occupies as many character positions as needed                             |
|      Any object      |   `"%6s"`   |     "Hi!"     |    "   Hi!"    |                        The text representation of the object occupies six character positions and is right-justified                         |
|      Any object      |  `"%-6s"`   |     "Hi!"     |    "Hi!   "    |                         The text representation of the object occupies six character positions and is left-justified                         |

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

### Java Logging Best Practices

- Log the **_Why_** at the higher level, and the **_What_** at the lower level
    - Controller/Service Entry points → Log the intent or flow initiation — "what you're trying to do" (e.g., save wallet, start workflow)
    - Internal Methods → Log specific actions being taken or their outcome — e.g., "Persisting wallet," "Calculated X changes"

|                    Goal                    |                           Reason                            |
|:------------------------------------------:|:-----------------------------------------------------------:|
|  Describe the purpose of the method call   |             Tell *what* is being done and *why*             |
| Log before and after meaningful operations |    Change detection, approval list building, CR creation    |
|            Show decision points            |                e.g. “no approvable changes”                 |
|          Include business context          | `walletId`, `pageName`, `componentName`, `entityCode`, etc. |
|  Catch and log errors if something fails   |           Important for visibility in production            |

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