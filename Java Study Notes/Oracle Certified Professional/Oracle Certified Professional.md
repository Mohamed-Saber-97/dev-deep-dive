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
      * [Lexical Tokens](#lexical-tokens)
      * [Identifiers](#identifiers)
      * [Keywords](#keywords)
        * [Keywords in Java](#keywords-in-java)
        * [Contextual Keywords](#contextual-keywords)
        * [Reserved Keywords Not Currently in Use](#reserved-keywords-not-currently-in-use)
        * [Reserved Literals in Java](#reserved-literals-in-java)
      * [Separators](#separators)
      * [Literals](#literals)
      * [Integer Literals](#integer-literals)
      * [Floating-Point Literals](#floating-point-literals)
      * [Underscores in Numerical Literals](#underscores-in-numerical-literals)
      * [Character Literals](#character-literals)
      * [Escape Sequences](#escape-sequences)
      * [String Literals](#string-literals)
      * [Whitespace](#whitespace)
      * [Comments](#comments)
    * [Primitive Data Types 🎯](#primitive-data-types-)
      * [The Integer Types](#the-integer-types)
      * [The `char` Type](#the-char-type)
      * [The Floating-Point Types](#the-floating-point-types)
      * [The `boolean` Type](#the-boolean-type)
    * [Conversions 🎯](#conversions-)
      * [Widening and Narrowing Primitive Conversions](#widening-and-narrowing-primitive-conversions)
      * [Widening and Narrowing Reference Conversions](#widening-and-narrowing-reference-conversions)
      * [Boxing and Unboxing Conversions](#boxing-and-unboxing-conversions)
      * [Other Conversions](#other-conversions)
    * [Type Conversion Contexts 🎯](#type-conversion-contexts-)
      * [Conversion categories](#conversion-categories)
        * [Assignment Context](#assignment-context)
        * [Method Invocation Context](#method-invocation-context)
        * [Casting Context of the Unary Type Cast Operator (_type_)](#casting-context-of-the-unary-type-cast-operator-_type_)
        * [Numeric Promotion Context](#numeric-promotion-context)
    * [Precedence and Associativity Rules for Operators 🎯](#precedence-and-associativity-rules-for-operators-)
      * [Operator Summary](#operator-summary)
    * [Evaluation Order of Operands 🎯](#evaluation-order-of-operands-)
      * [Left-Hand Operand Evaluation First](#left-hand-operand-evaluation-first)
      * [Operand Evaluation before Operation Execution](#operand-evaluation-before-operation-execution)
    * [The Simple Assignment Operator `=` 🎯](#the-simple-assignment-operator--)
      * [Type Conversions in an Assignment Context](#type-conversions-in-an-assignment-context)
    * [Arithmetic Operators: `*`, `/`, `%`, `+`, `-` 🎯](#arithmetic-operators-------)
      * [Division Operator: `/`](#division-operator-)
      * [Remainder Operator: `%`](#remainder-operator-)
      * [Numeric Promotions in Arithmetic Expressions](#numeric-promotions-in-arithmetic-expressions)
      * [Arithmetic Compound Assignment Operators: `*=`, `/=`, `%=`, `+=`, `-=`](#arithmetic-compound-assignment-operators------)
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
    - `> javac ClassA.java ClassB.java ClassC.java` → `ClassA.class`, `ClassB.class` and `ClassC.class`
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
            - `%d` → Integer
            - `%f` → Float
            - `%s` → String or Any Object
            - `%n` → Line separator
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

#### Lexical Tokens

- The low-level language elements are called **_lexical tokens_** (or just **_tokens_**) and are the building blocks for more complex constructs
- Identifiers, numbers, operators, and special characters are all examples of tokens that can be used to build high-level constructs like expressions, statements, methods, and classes

#### Identifiers

- A name in a program is called an **_identifier_**. Identifiers can be used to denote classes, methods, variables, and labels
- **_identifier_** is composed of a sequence of characters, where each character can be either a letter or a digit
    - the first character in an identifier must always be a letter
- Java programs are written in the Unicode character set so characters allowed in identifier names are interpreted according to this character set
    - characters A to Z and a to z are letters
    - characters 0 to 9 are digits -A connecting punctuation character (such as underscore _) and any currency symbol (such as $, ¢, ¥, or £) are also allowed
    - Note also that the underscore (_) on its own is not a legal identifier name, but a keyword
    - Identifiers in Java are case-sensitive
- Examples of Identifiers
    - Legal → `number`, `Number`, `sum_$`, `bingo`, `$$_100`, `_007`, `mål`, `grüß`
    - Illegal:
        - `48chevy` → it starts with a digit
        - `all@hands` → The character `@` is not a legal character in an identifier or operator, so `all@hands` cannot be interpreted as a legal expression with two operands
        - `grand-sum` → The character `-` is not a legal character in an identifier, but it is a legal operator; thus `grand-sum` could be interpreted as a legal expression with two operands
        - `_` → (`_`) by itself is not a legal identifier.

#### Keywords

- Keywords are reserved words or identifiers that are predefined in the language and cannot be used to denote other entities
- All Java keywords are lowercase, and incorrect usage results in compile-time errors
- The keyword `strictfp` is obsolete as of Java SE 17, and its use is discouraged in new code
- A **_contextual keyword_** cannot be used as an identifier in certain contexts
- `null`, `true` and `false` are the only three identifiers are reserved as predefined literals in the language
- A keyword cannot be used as an identifier

##### Keywords in Java

| `abstract` | `default` |     `if`     |  `private`  |      `this`      | `instanceof` |  `transient`   |
|:----------:|:---------:|:------------:|:-----------:|:----------------:|:------------:|:--------------:|
| `boolean`  | `double`  |   `import`   |  `public`   |     `throws`     |   `return`   |     `void`     |
|   `byte`   |  `enum`   |    `int`     |   `short`   |      `try`       |   `native`   |   `continue`   |
|  `catch`   |  `final`  |    `long`    | `strictfp`  |    `volatile`    | `interface`  |     `for`      |
|  `class`   |  `float`  |    `new`     |  `switch`   | `_` (underscore) |   `super`    |   `package`    |
|  `assert`  |   `do`    | `implements` | `protected` |     `throw`      |   `while`    | `synchronized` |
|  `break`   |  `case`   |    `else`    |  `extends`  |      `char`      |   `static`   |                |

##### Contextual Keywords

|  `exports`   |  `opens`   |  `requires`  | `uses`  |
|:------------:|:----------:|:------------:|:-------:|
|   `module`   | `permits`  |   `sealed`   |  `var`  |
| `non-sealed` | `provides` |     `to`     | `with`  |
|    `open`    |  `record`  | `transitive` | `yield` |

##### Reserved Keywords Not Currently in Use

- `const` and `goto`

##### Reserved Literals in Java

- `null`, `true` and `false`

#### Separators

- **_Separators_** (also known as **_punctuators_**) are tokens that have meaning depending on the context in which they are used
- they aid the compiler in performing syntax and semantic analysis of a program
- The semicolon (`;`) is used to terminate a statement.
- A pair of curly brackets, `{}`, can be used to group several statements

#### Literals

- A **_literal_** denotes a constant value; in other words, the value that a literal represents remains unchanged in the program
- Literals represent numerical (integer or floating-point), character, boolean, and string values.
- the literal null represents the `null` reference.
- Examples of Literals:
    - Integer → `2000`,`0` and `7`
    - Floating-point → `3.14`, `-3.14`, `.5` and `0.5`
    - Character → `'a'`, `'A'`, `'0'`, `':'`, `'-'` and `')'`
    - Boolean → `true` and `false`
    - String → `"abba"`, `"3.14"`, `"for"` and  `"a piece of the action"`

#### Integer Literals

- Integer data types in Java represent signed integer values, meaning both positive and negative integer values.
- **_The values of type `char` can effectively be regarded as unsigned 16-bit integers_**
- Integer data types comprise the following primitive data types:
    - `int`
        - The default data type of integer literal
    - `long`
        - Can be specified by appending the suffix `L` (or `l`) to the integer value
        - The suffix `L` is often preferred because the suffix `l` and the digit `1` can be hard to distinguish
        - Without the suffix, the long literals `2020L` and `0L` will be interpreted as `int` literals
    - `byte`
        - There is no direct way to specify a byte literal.
    - `short`
        - There is no direct way to specify a short literal.
- In addition to the decimal number system, integer literals can be specified in:
    - binary (base 2, digits 0–1) and specified with `0b` (or `0B`) prefix
    - octal (base 8, digits 0–7) and specified with `0` prefix
    - hexadecimal (base 16, digits 0–9 and a–f) number systems and specified with `0x` (or `0X`) prefix
        - The digits a to f in the hexadecimal system correspond to decimal values 10 to 15

#### Floating-Point Literals

- Floating-point data types come in two flavors:
    - `float`
        - It can also be specified to be a float by appending the suffix `F` (or `f`).
    - `double`
        - The default data type of a floating-point literal
        - It Can be explicitly designated by appending the suffix `D` (or `d`) to the value.
- Floating-point literals can also be specified in scientific notation, where `E` (or `e`) stands for exponent
    - `194.9E-2` → `94.9 × 10^-2`

#### Underscores in Numerical Literals

- The underscore character (`_`) can be used to improve the readability of numerical literals in the source code
- **_Any number_** of underscores can be inserted between the **digits** that make up the numerical literal
- This rules out underscores adjacent to:
    - the sign (`+`, `-`)
    - the radix prefix (`0b`, `0B`, `0x`, `0X`)
    - the decimal point (`.`)
    - the exponent (`e`, `E`),
    - the data type suffix (`l`, `L`, `d`, `D`, `f`, `F`)
    - before the first digit
        - Note that octal radix prefix `0` is part of the definition of an octal literal and is therefore considered the first digit of an octal literal
    - after the last digit
- Underscores in identifiers are treated as letters
    - the names `_XXL` and `_XXL_` are two distinct legal identifiers
- In contrast, underscores are used as a notational convenience for numerical literals and are ignored by the compiler when used in such literals
- Examples of Legal Use of Underscores in Numerical Literals
    - `0b0111_1111_1111_1111_1111_1111_1111_1111`
    - `0_377_777_777`
    - `0xff_ff_ff_ff`
    - `-123_456.00`
    - `1_2.345_678e1_2`
    - `2009__08__13`
    - `49_03_01d`
- Examples of Illegal Use of Underscores in Numerical Literals
    - `_0_b_01111111111111111111111111111111_`
    - `_0377777777_`
    - `+_123456_._00_`
    - `_20090813_`
    - `_0_x_ffffffff_`
    - `_12_._345678_e_12_`
    - `_490301_d_`

#### Character Literals

- A character literal is quoted in single quotes (`'`). All character literals have the primitive data type `char`.
- A character literal is represented according to the 16-bit Unicode character set, which subsumes the 8-bit ISO Latin-1 and the 7-bit ASCII characters
- **_The values of type `char` can effectively be regarded as unsigned 16-bit integers_**
- A Unicode character can always be specified as a four-digit hexadecimal number (i.e., 16 bits) with the prefix `\u`
    - `'A'` → `'\u0041'`
    - `'Z'` → `'\u005a'`
    - `'a'` → `'\u0061'`
    - `'z'` → `'\u007a'`

#### Escape Sequences

- Certain **_escape sequences_** define special characters that can be :
    - single-quoted to define character literals
    - included in string literals and text blocks
- However, the Unicode values `\u000a` and `\u000d` should not be used to represent a newline and a carriage return in the source code since These values are interpreted as line-terminator characters by the compiler and will cause compile-time errors.
- You should use the escape sequences `\n` and `\r`, respectively, for correct interpretation of these characters in the source code
- We can also use the escape sequence `\ddd` to specify a character literal as an octal value, where each digit d can be any octal digit (0–7)

|  Escape sequence   | Unicode value |                  Character                   |
|:------------------:|:-------------:|:--------------------------------------------:|
|        `\b`        |   `\u0008`    |                Backspace (BS)                |
|        `\t`        |   `\u0009`    |          Horizontal tab (HT or TAB)          |
|        `\n`        |   `\u000a`    |  Linefeed (LF), also known as newline (NL)   |
|        `\f`        |   `\u000c`    |                Form feed (FF)                |
|        `\r`        |   `\u000d`    |             Carriage return (CR)             |
|        `\s`        |   `\u0020`    |                  Space (SP)                  |
| `\Line terminator` |      `_`      |      Line continuation in a text block       |
|        `\'`        |   `\u0027`    | Apostrophe-quote, also known as single quote |
|        `\"`        |   `\u0022`    |  Quotation mark, also known as double quote  |
|        `\\`        |   `\u005c`    |                  Backslash                   |

#### String Literals

- A **_string literal_** is a sequence of characters that **_must_** be
    - enclosed in double quotes
    - occur on a single line
- All string literals are objects of the class `String`
- Escape sequences as well as Unicode values can appear in string literals:
    1. `"Here comes a tab.\t And here comes another one\u0009!"`
    2. `"What's on the menu?"`
        - the single quote need not be escaped in strings, but it would be if specified as a character literal ('`\'`')
    3. `"\"String literals are double-quoted.\""`
        1. the double quotes in the string must be escaped
    4. `"Left!\nRight!"`
        1. we use the escape sequence `\n` to insert a newline
    5. `"Don't split`
    6. `me up!"`
        1. (5) and (6) will generate a compile-time error, as the string literal is split over several lines.
        2. One should also use the escape sequences `\n` and `\r`, respectively, for correct interpretation of the characters `\u000a` (newline) and `\u000d` (form feed) in string literals

#### Whitespace

- Whitespace is a sequence of **spaces**, **tabs**, **form feeds**, and **line terminator characters** in a Java source file
- Line terminators include the **newline**, **carriage return**, and **carriage return** – newline sequence
- A Java program is a free-format sequence of characters that is **_tokenized_** by the compiler — that is, broken into a stream of tokens for further analysis
- Separators and operators help to distinguish tokens, but sometimes whitespace has to be inserted explicitly as a separator.
- For example, the identifier `classRoom` will be interpreted as a single token, unless whitespace is inserted to distinguish the keyword `class` from the identifier `Room`
- Whitespace aids not only in separating tokens, but also in formatting the program so that it is straightforward to read. The compiler ignores the whitespace once the tokens are identified

#### Comments

- A program can be documented by inserting comments at relevant places in the source code
- These comments are for documentation purposes only and are ignored by the compiler
- Java provides three types of comments that can be used to document a program:
    - single-line comment: `//` ... to the end of the line
    - multiple-line comment: `/* ... */`
    - documentation (Javadoc) comment: `/** ... */`
        - A documentation comment is a special-purpose multiple-line comment that is used by the `javadoc` tool to generate HTML documentation for the program
        - Documentation comments are usually placed in front of classes, interfaces, methods, and field definitions
        - Special tags can be used inside a documentation comment to provide more specific information. Such a comment starts with the sequence /** and ends with the sequence
- trying to nest multiple-line comments will result in a compile-time error like the below:

```java
/* Formula for alchemy.
Gold = wizard.makeGold(stone);
/* But it only works on Sundays. */
*/
```

- The second occurrence of the comment-start sequence /* is ignored. The last occurrence of the sequence */ in the code is now unmatched, resulting in a syntax error.
- [How to Write Doc Comments for the Javadoc Tool](https://www.oracle.com/eg/technical-resources/articles/java/javadoc-tool.html "How to Write Doc Comments for the Javadoc Tool")

### Primitive Data Types 🎯

- Primitive data types in Java can be divided into three main categories:
    - **_Integral types_** → represent signed integers (`byte`, `short`, `int`, `long`) and unsigned character values (`char`)
    - **_Floating-point types (`float`, `double`)_** → represent fractional signed numbers
    - **_`Boolean` type (`boolean`)_** → represents logical values

![Primitive Data Types in Java](./images/Primitive%20Data%20Types%20in%20Java.png "Primitive Data Types in Java")

- **_Primitive data values are not objects_**, but each primitive data type has a corresponding wrapper class that can be used to represent a primitive value as an object

#### The Integer Types

| Data type | Width (bits) |           Minimum value `MIN_VALUE`           |             Maximum value `MAX_VALUE`             | Wrapper class |
|:---------:|:------------:|:---------------------------------------------:|:-------------------------------------------------:|:-------------:|
|  `byte`   |      8       |          `–2`<sup>`7`</sup> (`–128`)          |          `2`<sup>`7`</sup> `-1` (`+127`)          |    `Byte`     |
|  `short`  |      16      |       `–2`<sup>`15`</sup> (`–13276828`)       |        `2`<sup>`15`</sup> `-1` (`+32767`)         |    `Short`    |
|   `int`   |      32      |      `–2`<sup>`31`</sup> (`–2147483648`)      |      `2`<sup>`31`</sup> `-1` (`+2147483647`)      |   `Integer`   |
|  `long`   |      64      | `–2`<sup>`63`</sup> (`–9223372036854775808L`) | `2`<sup>`63`</sup> `-1` (`+9223372036854775807L`) |    `Long`     |

#### The `char` Type

- Their values are unsigned integers that denote all of the `65,536` (2<sup>16</sup>) characters in the 16-bit Unicode character set. This set includes
    - letters
    - digits
    - special characters

| Data type | Width (bits) | Minimum Unicode value | Maximum Unicode value | Wrapper class |
|:---------:|:------------:|:---------------------:|:---------------------:|:-------------:|
|  `char`   |      16      |    `0x0`,`\u0000`     |   `0xffff`,`\uffff`   |  `Character`  |

- The **_integer_** types and the `char` type are collectively called **_integral types_**

#### The Floating-Point Types

- The Table shows the range of values for positive floating-point numbers, but these apply equally to negative floating-point numbers with the minus sign (`-`) as a prefix.
- Zero can be either `0.0` or `-0.0`. The range of values represented by the double data type is wider than that of the float data type.

| Data type | Width (bits) | Minimum positive value `MIN_VALUE` | Maximum positive value `MAX_VALUE` | Wrapper class |
|:---------:|:------------:|:----------------------------------:|:----------------------------------:|:-------------:|
|  `float`  |      32      |      `1.401298464324817E-45f`      |    `3.402823476638528860e+38f`     |    `Float`    |
| `double`  |      64      |     `4.94065645841246544e-324`     |     `1.79769313486231570e+308`     |   `Double`    |

- Since the size for representation is a finite number of bits, certain floating-point numbers can be represented only as approximations
- For example, the value of the expression (`1.0/3.0`) is represented as an approximation due to the finite number of bits used to represent floating-point numbers

#### The `boolean` Type

- The data type `boolean` represents the two logical values denoted by the literals `true` and `false` that results from the following operations:
    - relational
    - conditional
    - logical operators

| Data type |  Width (bits)  | True value literal | False value literal | Wrapper class |
|:---------:|:--------------:|:------------------:|:-------------------:|:-------------:|
| `boolean` | Not applicable |       `true`       |       `false`       |   `Boolean`   |

### Conversions 🎯

- Some type conversions must be **_explicitly_** stated in the program, while others are performed **_implicitly_**
- Some type conversions can be checked at **_compile time_** to guarantee their validity at **_runtime_**, while others will require an extra check at **_runtime_**.

#### Widening and Narrowing Primitive Conversions

[Widening Primitive Conversions](./images/Widening%20Primitive%20Conversions.png "Widening Primitive Conversions")

- For the primitive data types, the value of a **_narrower_** data type can be converted to a value of a **wider** data type, This is called a **_widening primitive conversion_**
- The conversions shown are transitive. For example, an `int` can be directly converted to a `double` without first having to convert it to a `long` and a `float`
- note that the target type of a widening primitive conversion has a wider range of values than the source type — for example, the range of the `long` type subsumes the range of the `int` type.
- In widening conversions between **_integral_** types, the source value remains intact, with **_no loss of magnitude information_**
- However, a widening conversion from an `int` or a `long` value to a `float` value, or from a `long` value to a `double` value, may result in a **_loss of precision_**
- The floating-point value in the target type is then a correctly rounded approximation of the integer value
- Note that precision relates to the number of significant bits in the value, and must not be confused with magnitude, which relates to how large the represented value can be
- Converting from a **_wider primitive type_** to a **_narrower primitive type_** is called a **_narrowing primitive conversion_**; it can result in a **_loss of magnitude information_**, and possibly in a **_loss of precision_** as well
- Any conversion that is not a _**widening primitive conversion,**_ according to the previous figure, is a **_narrowing primitive conversion_**
- The target type of a **_narrowing primitive conversion_** has a **_narrower range_** of values than the source type—for example, the range of the `int` type does not include all the values in the range of the `long` type.
- **_Note that all conversions between `char` and the two integer types `byte` and `short` are considered narrowing primitive conversions_**
    - conversions between the unsigned type `char` and the signed types `byte` and `short` can result in a **_loss of information_**.
- These narrowing conversions are done in two steps:
    - first converting the source value to the `int` type
    - then converting the `int` value to the target type.
- Widening primitive conversions is usually done implicitly, whereas narrowing primitive conversions usually require a **_cast_**
- It is not illegal to use a cast for a widening conversion. However, the compiler will flag any conversion that requires a cast if none has been specified
- Regardless of any loss of magnitude or precision, widening and narrowing primitive conversions **_never result in a runtime exception._**
- `long year = 2020; // (1) Implicit widening: long <----- int, assigned 2020L`
- `int pi = (int) 3.14; // (2) Narrowing requires cast: int <----- double, assigned 3`

#### Widening and Narrowing Reference Conversions

- The **_subtype–supertype_** relationship between reference types determines which conversions are permissible between them
- A subtype is a narrower type than its supertype in the sense that it is a specialization of its supertype.
- Conversions **_up_** the **_type hierarchy_** are called **_widening reference conversions_** (also called **_up-casting_**). Such a conversion converts from a **_subtype_** to a **_supertype_**:
    - `Object obj = "Upcast me"; // (1) Widening: Object <----- String`
    - usually done implicitly
    - do not require any runtime checks and never result in an exception during execution
- Conversions **_down_** the type hierarchy represent **_narrowing reference conversions_** (also called **_down-casting_**):
    - `String str = (String) obj; // (2) Narrowing requires cast: String <----- Object`
    - usually require a cast
    - The compiler will reject casts that are not legal or will issue an unchecked warning under certain circumstances if type-safety cannot be guaranteed
    - require a runtime check and can throw a `ClassCastException` if the conversion is not legal

#### Boxing and Unboxing Conversions

- Boxing and unboxing conversions allow interoperability between primitive values and their representation as objects of the wrapper types, Both boxing and unboxing conversion are applied implicitly in the right context
    - **_boxing conversion_** → converts the value of a primitive type to a corresponding value of its wrapper type
        - `Integer iRef = 10; // (1) Implicit boxing (autoboxing): Integer <----- int`
        - `Double dRef = Double.valueOf(3.14); // (2) Explicit boxing: Double <----- double`
    - **_unboxing conversion_** → converts the value of a wrapper type to a value of its corresponding primitive type
        - `int i = iRef; // (3) Implicit unboxing: int <----- Integer`
        - `double d = dRef.doubleValue(); // (4) Explicit unboxing: double <----- Double`
- wrapper classes also provide the `static` methods
    - `valueOf()` → explicitly box a primitive value in a wrapper object
    - `primitiveTypeValue()` → explicitly unbox the value in a wrapper object as a value of **_primitiveType_**
- both boxing and unboxing are done implicitly in the right context
- **_Unboxing a wrapper reference that has the null value results in a `NullPointerException`_**

#### Other Conversions

- Identity conversions allow conversions from a type to that same type. An identity conversion is always permitted
    - `int i = (int) 10; // int <---- int`
    - `String str = (String) "Hi"; // String <---- String`
- **_String conversions_** allow a value of **_any other type_** to be converted to a `String` type in the context of the string concatenation operator `+`
- **_Unchecked conversions_** are permitted to facilitate portability between legacy and generic code

### Type Conversion Contexts 🎯

#### Conversion categories

##### Assignment Context

- An expression (or its value) is assignable to the target variable
- if the type of the expression can be converted to the type of the target variable by an **_assignment conversion_**.
- Equivalently, the type of the expression assignment is compatible with the type of the target variable
- Note the special case where a narrowing conversion occurs when assigning a non-long integer constant expression:
    - `byte b = 10; // Narrowing conversion: byte <--- int`

##### Method Invocation Context

- Method invocation conversions do not include the implicit narrowing conversion performed for non-long integral constant expressions.
- A method invocation conversion involves converting each argument value in a method or constructor call to the type of the corresponding formal parameter in the method or constructor declaration

```java
// Assignment: (1) Implicit narrowing followed by (2) boxing.
Character space1 = 32; // Character <-(2)-- char <-(1)-- int
// Invocation of method with signature: valueOf(char)
Character space2 = Character.valueOf(32); // Compile-time error! Call signature: valueOf(int)
Character space3 = Character.valueOf((char) 32); // OK! Call signature: valueOf(char)
```

##### Casting Context of the Unary Type Cast Operator (_type_)

- Java, being a strongly typed language, checks for type compatibility (i.e., it checks whether a type can substitute for another type in a given context) at compile time
- However, some checks are possible only at runtime (e.g., which type of object a reference actually denotes during execution).
- In cases where an operator would have incompatible operands (e.g., assigning a double to an int), Java demands that a type cast be used to explicitly indicate the type conversion
- At runtime, a cast results in a new value of a type, which best represents the value of the expression in the old type. We use the term casting to mean applying the cast operator for **_explicit_** type conversion
- However, in the context of casting, implicit casting conversions can take place

```java
long l = (long) 10; // Widening primitive conversion: long <--- int
int i = (int) l; // (1) Narrowing primitive conversion: int <--- long
Object obj = (Object) "7Up"; // Widening ref conversion: Object <--- String
String str = (String) obj; // (2) Narrowing ref conversion: String <--- Object
Integer iRef = (Integer) i; // Boxing: Integer <--- int
i =(int)iRef; // Unboxing: int <--- Integer
```

- Casting between primitive data types and reference types is not permitted, except where boxing and unboxing are applicable
- Boolean values cannot be cast to other data values, and vice versa.
- The reference literal null can be cast to any reference type

##### Numeric Promotion Context

- Numeric operators allow only operands of certain types
- Permissible conversion categories are widening primitive conversions and unboxing conversions
- Unary Numeric Promotion
    - If the single operand is of type `Byte`, `Short`, `Character`, or `Integer`, it is unboxed. If the resulting value is narrower than `int`, it is promoted to a value of type `int` by a widening conversion
    - Otherwise, if the single operand is of type `Long`, `Float`, or `Double`, it is unboxed
    - Otherwise, if the single operand is of a type narrower than `int`, its value is promoted to a value of type `int` by a widening conversion
    - Otherwise, the operand remains unchanged
    - In other words, unary numeric promotion results in an operand value that is either `int` or wider
    - Unary numeric promotion is applied in the following expressions:
        - Operand of the unary arithmetic operators `+` and `-`
        - Array creation expression; for example, `new int[20]`, where the dimension expression (in this case, 20) must evaluate to an `int` value
        - Indexing array elements; for example, `objArray['a']`, where the index expression (in this case, `a`) must evaluate to an `int` value
- Binary Numeric Promotion
    - Binary numeric promotion implicitly applies appropriate widening primitive conversions so that the widest numeric type of a pair of operands is always at least `int`
    - If T is the widest numeric type of two operands after any unboxing conversions have been performed, the operands are promoted as follows during binary numeric promotion:
        - If `T` is wider than `int`, both operands are converted to `T`; otherwise, both operands are converted to `int`
    - This means that the resulting type of the operands is at least `int`
    - Binary numeric promotion is applied in the following expressions:
        - Operands of the arithmetic operators `*`, `/`, `%`, `+`, and `-`
        - Operands of the relational operators `<`, `<=`, `>`, and `>=`
        - Operands of the numerical equality operators `==` and `!=`
        - Operands of the conditional operator `? :`, under certain circumstances

### Precedence and Associativity Rules for Operators 🎯

- Precedence and associativity rules are necessary for deterministic evaluation of expressions
- The following remarks apply to the following table:
    - The operators are shown with decreasing precedence from the top of the table
    - Operators within the same row have the same precedence
    - Parentheses, `()`, can be used to override precedence and associativity
    - The unary operators, which require one operand, include the following:
        - The postfix increment (`++`) and decrement (`--`)
        - All the prefix operators (`+`, `-`, `++`, `--`, `~`, `!`)
        - The prefix operators (object creation operator `new`, cast operator `(type)`)
    - The conditional operator (`? :`) is ternary—that is, it requires three operands
    - Except for unary postfix increment and decrement operators, all unary operators, all assignment operators, and the ternary conditional operator associate from right to left
    - All operators not identified previously as **_unary_** or **_ternary_** are **_binary_** — that is, they require two operands.
    - All binary operators, except for the relational and assignment operators, associate from left to right.
        - The relational operators are non-associative
    - Depending on the context, brackets (`[]`), parentheses (`()`), the colon (`:`), and the dot operator (`.`) can also be interpreted as separators

#### Operator Summary

|                       Operator                        |                              Example                              |  Direction   |
|:-----------------------------------------------------:|:-----------------------------------------------------------------:|:------------:|
| Array element access,member access, method invocation |                 `[expression]`, `.` and `(args)`                  | Left → Right |
|                Unary postfix operators                |                 `expression++` and `expression--`                 | Left → Right |
|                Unary prefix operators                 | `~` `!` `++expression` `--expression` `+expression` `-expression` | Right → Left |
|            Unary prefix creation and cast             |                          `new` `(type)`                           | Right → Left |
|                    Multiplicative                     |                            `*` `/` `%`                            | Left → Right |
|                       Additive                        |                              `+` `-`                              | Left → Right |
|                         Shift                         |                          `<<` `>>` `>>>`                          | Left → Right |
|                      Relational                       |                  `<` `<=` `>` `>=` `instanceof`                   | Left → Right |
|                       Equality                        |                             `==` `!=`                             | Left → Right |
|                  Bitwise/logical AND                  |                                `&`                                | Left → Right |
|                  Bitwise/logical XOR                  |                                `^`                                | Left → Right |
|                  Bitwise/logical OR                   |                               `\|`                                | Left → Right |
|                    Conditional AND                    |                               `&&`                                | Left → Right |
|                    Conditional OR                     |                              `\|\|`                               | Left → Right |
|                      Conditional                      |                               `?:`                                | Right → Left |
|                    Arrow operator                     |                               `->`                                | Left → Right |
|                      Assignment                       |  `=` `+=` `-=` `*=` `/=` `%=` `<<=` `>>=` `>>>=` `&=` `^=` `\|=`  | Right → Left |

### Evaluation Order of Operands 🎯

#### Left-Hand Operand Evaluation First

- The left-hand operand of a binary operator is fully evaluated before the right-hand operand is evaluated
- The evaluation of the left-hand operand can have side effects that can influence the value of the right-hand operand
    - If evaluation of the left-hand operand of a binary operator throws an exception
    - we cannot rely on the presumption that the right-hand operand has been evaluated

#### Operand Evaluation before Operation Execution

- Java guarantees that all operands of an operator are fully evaluated before the actual operation is performed
- This rule does not apply to the short-circuit conditional operators `&&,` `||`, and `?:`
- This rule also applies to operators that throw an exception:
    - the integer division operator /
    - the integer remainder operator %
- The operation is performed only if the operands evaluate normally.

### The Simple Assignment Operator `=` 🎯

- The **_target_** variable and the source _**expression**_ must be assignment compatible
- The target variable must also have been declared.
- Since variables can store either primitive values or reference values, expression evaluates to either a primitive value or a reference value
- Copying reference values by assignment creates aliases
- `k = j = 10; // (k = (j = 10))`

#### Type Conversions in an Assignment Context

- If the target and the source have the same type in an assignment, then the source and the target assignment are compatible and the source value need not be converted.
- Otherwise, if a widening primitive conversion is permissible, then the widening conversion is applied implicitly; that is, the source type is converted to the target type in an assignment context

```java
// Widening Primitive Conversions
int smallOne = 1234; // No widening necessary.
long bigOne = 2020; // Widening: int to long.
double largeOne = bigOne; // Widening: long to double.
double hugeOne = (double) bigOne; // Cast redundant but allowed.
//A widening primitive conversion can result in loss of precision
long bigInteger = 98765432112345678L;
float fpNum = bigInteger; // Widening but loss of precision: 9.8765436E16
```

- **_implicit narrowing_** primitive conversions on assignment can occur in cases where all the following conditions are fulfilled:
    - The source is a constant expression of type `byte`, `short`, `char`, or `int`
    - The target type is of type `byte`, `short`, or `char`.
    - The value of the source is determined to be in the range of the target type at compile time
- A constant expression is an expression that denotes either a **_primitive_** or a `String` literal
    - it is composed of operands that can be only literals or constant variables
    - operators that can be evaluated only at compile time (e.g., arithmetic and numerical comparison operators, **_but not increment/decrement operators and method calls_**).
- A constant variable is a final variable of either a primitive type or the String type that is initialized with a constant expression

```java
int result = 100; // Not a constant variable. Not declared final.
final char finalGrade = 'A'; // Constant variable. ’A’
System.out.

printf("%d%n%s%n%d%n%.2f%n%b%n%d%n%d%n",
               2022, // Constant expression. 2022
               "Trust "+"me!", // Constant expression. "Trust me"
               2+3*4, // Constant expression. 14
       Math.PI *Math.PI*10.0, // Constant expression. 98.70
       finalGrade =='A', // Constant expression. true
       Math.min(2020, 2021), // Not constant expression. Method call.
                          ++result // Not constant expression. Increment operator.
);
```

- Here are some examples that illustrate how the conditions mentioned previously affect narrowing primitive conversions:

```java
// Conditions fulfilled for implicit narrowing primitive conversions.
short s1 = 10; // int value in range.
short s2 = 'a'; // char value in range.
char c1 = 32; // int value in range.
char c2 = (byte) 35; // byte value in range. (int value in range, without cast.)
byte b1 = 40; // int value in range.
byte b2 = (short) 40; // short value in range. (int value in range, without cast.)
final int i1 = 20; // Constant variable
byte b3 = i1; // final value of i1 in range.
```

- All other narrowing primitive conversions will produce a compile-time error on assignment and will explicitly require a cast. Here are some examples:

```java
// Conditions not fulfilled for implicit narrowing primitive conversions.
// A cast is required.
int i2 = -20; // i2 is not a constant variable. i2 is not final.
final int i3 = i2; // i3 is not a constant variable, since i2 is not.
final int i4 = 200; // i4 is a constant variable.
final int i5; // i5 is not a constant variable.
short s3 = (short) i2; // Not constant expression.
char c3 = (char) i3; // Final value of i3 not determinable at compile time.
char c4 = (char) i2; // Not constant expression.
byte b4 = (byte) 128; // int value not in range.
byte b5 = (byte) i4; // Value of constant variable i4 is not in range.
i5 =100; // Initialized at runtime.
short s4 = (short) i5; // Final value of i5 not determinable at compile time.
```

- Floating-point values are truncated when cast to integral values:

```java
// The value is truncated to fit the size of the target type.
float huge = (float) 1.7976931348623157d; // double to float.
long giant = (long) 4415961481999.03D; // (1) double to long.
int big = (int) giant; // (2) long to int.
short small = (short) big; // (3) int to short.
byte tiny = (byte) small; // (4) short to byte.
char symbol = (char) 112.5F; // (5) float to char.
```

- The following examples illustrate boxing and unboxing in an assignment context:

```java
Boolean boolRef = true; // Boxing.
Byte bRef = 2; // Constant in range: narrowing, then boxing.
// Byte bRef2 = 257; // Constant not in range. Compile-time error!
short s = 10; // Narrowing from int to short.
// Integer iRef1 = s; // short not assignable to Integer.
Integer iRef3 = (int) s; // Explicit widening with cast to int and boxing
boolean bv1 = boolRef; // Unboxing.
byte b1 = bRef; // Unboxing.
int iVal = bRef; // Unboxing and widening.
Integer iRefVal = null; // Always allowed.
// int j = iRefVal; // NullPointerException at runtime.
if(iRef3 !=null)iVal =iRef3; // Avoids exception at runtime.
```

### Arithmetic Operators: `*`, `/`, `%`, `+`, `-` 🎯

- Arithmetic operators are used to construct mathematical expressions as in algebra
- Their operands are of a numeric type (which includes the `char` type).
- Floating-point operations are now consistently **_strict_**
    - they are executed in accordance with the IEEE-754 32-bit (float) and 64-bit (double) standard formats
- This means that floating-point arithmetic operations give the same results on any JVM implementation
    - The keyword `strictfp` used to enforce strict behavior for floating-point arithmetic is now obsolete and should not be used in new code
- Arithmetic Operator Precedence and Associativity
    - Unary subtraction has higher precedence than multiplication
    - Binary multiplication, division, and remainder operators have the same precedence
    - The unary operators have right associativity
    - the binary operators have left associativity
- Evaluation Order in Arithmetic Expressions
    - Java guarantees that the operands are fully evaluated from left to right before an arithmetic binary operator is applied
    - If evaluation of an operand results in an error, the later operands will not be evaluated
- Range of Numeric Values
    - This range is given by the constants named `MAX_VALUE` and `MIN_VALUE`, which are defined in each numeric wrapper type.
    - The arithmetic operators are overloaded, meaning that the operation of an operator varies depending on the type of its operands.
    - Floating-point arithmetic is performed if any operand of an operator is of a floating-point type; otherwise, integer arithmetic is performed
    - Values that are out of range or are the results of invalid expressions are handled differently depending on whether integer or floating-point arithmetic is performed
- Integer Arithmetic
    - Integer arithmetic always returns a value in range, except `integer/0` or `integer%0` which cause an `ArithmeticException`
    - A valid value does not necessarily mean that the result is correct since it can be overflowed or underflow values
        - `int tooBig = Integer.MAX_VALUE + 1; // -2147483648 which is Integer.MIN_VALUE`
        - `int tooSmall = Integer.MIN_VALUE - 1; // 2147483647 which is Integer.MAX_VALUE`
    - To avoid wrapping around out-of-range values, programs should use either explicit checks or a wider type
- Floating-Point Arithmetic
    - Certain floating-point operations result in values that are out of range
    - Typically, adding or multiplying two huge floating-point numbers can result in an out-of-range value represented by **_infinity_**
    - Attempting floating-point division by zero also returns infinity.
        - `System.out.println( 4.0 / 0.0); // Prints: Infinity`
        - `System.out.println(-4.0 / 0.0); // Prints: -Infinity`
    - Both positive and negative infinity represents overflow to infinity; that is, the value is too large to be represented as a double or float
    - Signed infinity is represented by the named constants `POSITIVE_INFINITY` and `NEGATIVE_INFINITY` in the wrapper classes `java.lang.Float` and `java.lang.Double`

![Overflow and Underflow in Floating-Point Arithmetic.png](./images/Overflow%20and%20Underflow%20in%20Floating-Point%20Arithmetic.png)

- Floating-point arithmetic can also result in underflow to zero, when the value is too small to be represented as a `double` or `float`, Underflow occurs in the following situations:
    - The result is between `Double.MIN_VALUE` (or `Float.MIN_VALUE`) and zero, Underflow then returns positive zero `0.0`
      (or `0.0F`).
    - The result is between `-Double.MIN_VALUE` (or `-Float.MIN_VALUE`) and zero, Underflow then returns negative zero
      `-0.0` (or `-0.0F`).
    - Negative zero compares equal to positive zero; in other words, (`-0.0 == 0.0`) is `true`.
    - Certain operations have no mathematical result, and are represented by `NaN` (Not-a-Number).
        - calculating the square root of `–1` results in a `NaN`
        - (floating-point) dividing zero by zero → `System.out.println(0.0 / 0.0); // Prints: NaN`
    - `NaN` is represented by the constant named `NaN` in the wrapper classes `java.lang.Float` and `java.lang.Double`
        - Any operation involving `NaN` produces `NaN`
        - Any comparison (except inequality, `!=`) involving `NaN` and any other value (including `NaN`) returns `false`
        - An inequality comparison of `NaN` with another value (including `NaN`) always returns `true`
        - However, the recommended way of checking a value for `NaN` is to use the static method `isNaN()` defined in both wrapper classes, `java.lang.Float` and `java.lang.Double`
- Unary Arithmetic Operators: `-`, `+`
    - The unary operators have the highest precedence of all the arithmetic operators
    - The unary operator `-` negates the numeric value of its operand
    - The following example illustrates the right associativity of the unary operators:
        - `int value = - -10; // (-(-10)) is 10`
        - blank space needed to separate the unary operators; without the blank space, these would be interpreted as the decrement operator `--`
        - which would result in a compile-time error because a literal cannot be decremented.
        - The unary operator `+` has no effect on the evaluation of the operand value.

#### Division Operator: `/`

- The division operator `/` is overloaded. If its operands are integral, the operation results in integer division
- Integer division always returns the quotient as an integer value that is, the result is truncated toward zero.
- Note that the division performed is integer division if the operands have integral values, even if the result is stored in a floating-point type.
-

```java
int i1 = 4 / 5; // result: 0
int i2 = 8 / 8; // result: 1
double d1 = 12 / 8; // result: 1.0; integer division, then widening conversion
```

- The integer value is subjected to a widening conversion in the assignment context.
- An `ArithmeticException` is thrown when integer division with zero is attempted, meaning that integer division by zero is an illegal operation
- If any of the operands is a floating-point type, the operation performs floating-point division, where relevant operand values undergo binary numeric promotion:

```java
double d2 = 4.0 / 8; // result: 0.5
double d3 = 8 / 8.0; // result: 1.0
float d4 = 12.0F / 8; // result: 1.5F
double result1 = 12.0 / 4.0 * 3.0; // ((12.0 / 4.0) * 3.0) which is 9.0
double result2 = 12.0 * 3.0 / 4.0; // ((12.0 * 3.0) / 4.0) which is 9.0
```

#### Remainder Operator: `%`

- In mathematics, when we divide a number (the **_dividend_**) by another number (the **_divisor_**), the result can be expressed in terms of a **_quotient_** and a **_remainder_**
- An `ArithmeticException` is thrown if the divisor evaluates to zero
- The remainder operator % returns the remainder of the division performed on the operands
    - when 7 is divided by 5, the quotient is 1 and the remainder is 2

```java
int quotient = 7 / 5; // Integer division operation: 1
int remainder = 7 % 5; // Integer remainder operation: 2
```

- For integer remainder operation, where only integer operands are involved, evaluation of the expression (`x % y`) always satisfies the following relation:
    - `x == (x / y) * y + (x % y)`
    - In other words, the right-hand side yields a value that is always equal to the value of the dividend
- The following examples show how we can calculate the remainder so that this relation is satisfied:

```text
Calculating (7 % 5):
7   == (7 / 5)  * 5 + (7 % 5)
    ==  ( 1 )   * 5 + (7 % 5)
    ==            5 + (7 % 5)
2   ==                (7 % 5)        (7 % 5) is equal to 2

Calculating (7 % -5):
7   == (7 / -5)  * -5 + (7 % -5)
    ==  ( -1 )   * -5 + (7 % -5)
    ==              5 + (7 % -5)
2   ==                  (7 % -5)        (7 % -5) is equal to 2

Calculating (–7 % 5):
-7  == (-7 / 5) * 5 + (-7 % 5)
    ==  ( -1 )  * 5 + (-7 % 5)
    ==           -5 + (-7 % 5)
-2  ==                (-7 % 5)        (–7 % 5) is equal to –2

Calculating (–7 % –5):
-7  == (-7 / -5) * -5 + (-7 % -5)
    ==  ( 1 )    * -5 + (-7 % -5)
    ==             -5 + (-7 % -5)
-2  ==                  (-7 % -5)       (–7 % –5) is equal to –2
```

- The remainder can be negative only if the dividend is negative, and the sign of the divisor is irrelevant
- A shortcut to evaluating the remainder involving negative operands is the following:
    - Ignore the signs of the operands
    - calculate the remainder
    - negate the remainder if the dividend is negative

```java
int r0 = 7 % 7; // 0
int r1 = 7 % 5; // 2
long r2 = 7L % -5L; // 2L
int r3 = -7 % 5; // -2
long r4 = -7L % -5L; // -2L
boolean relation = -7L == (-7L / -5L) * -5L + r4; // true
```

- the remainder operator accepts not only integral operands but also floating-point operands. The floating-point remainder `r` is defined by the relation
    - `r == a – (b * q)`
    - where a and b are the **_dividend_** and the **_divisor_**, respectively, and `q` is the integer **_quotient_** of (`a/b`)

```java
double dr0 = 7.0 % 7.0; // 0.0
float fr1 = 7.0F % 5.0F; // 2.0F
double dr1 = 7.0 % -5.0; // 2.0
float fr2 = -7.0F % 5.0F; // -2.0F
double dr2 = -7.0 % -5.0; // -2.0
boolean fpRelation = dr2 == (-7.0) - (-5.0) * (long) (-7.0 / -5.0); // true
float fr3 = -7.0F % 0.0F; // NaN
```

#### Numeric Promotions in Arithmetic Expressions

- **_Unary_** numeric promotion is applied to the **_single operand_** of the **_unary arithmetic_** operators `-` and `+`
- When a unary arithmetic operator is applied to an operand whose type is narrower than `int`, the operand is promoted to a value of type `int`, with the operation resulting in an `int` value
- If the conditions for implicit narrowing conversion are not fulfilled, assigning the int result to a variable of a narrower type will require a cast
    - `byte b = 3; // int literal in range. Narrowing conversion`
    - `b = (byte) -b; // Cast required on assignment`
- Binary numeric promotion is applied to operands of binary arithmetic operators
- Its application leads to type promotion for the operands. The result is of the promoted type, which is always type int or wider

```java
public class NumPromotion {
    public static void main(String[] args) {
        byte b = 32;
        char c = 'z'; // Unicode value 122 (\u007a)
        short s = 256;
        int i = 10000;
        float f = 3.5F;
        double d = 0.5;
        double v = (d * i) + (f * -b) - (c / s); // (1) 4888.0D
        System.out.println("Value of v: " + v);// Value of v: 4888.0
    }
}
```

![Numeric Promotion in Arithmetic Expressions.png](./images/Numeric%20Promotion%20in%20Arithmetic%20Expressions.png)

- In addition to the binary numeric promotions in arithmetic expression evaluation, the resulting value can undergo an implicit widening conversion if assigned to a variable

```java
Byte b = 10; // Constant in range: narrowing and boxing on assignment.
Short s = 20; // Constant in range: narrowing and boxing on assignment.
char c = 'z'; // 122 (\u007a)
int i = s * b; // Values in s and b promoted to int: unboxing, widening.
long n = 20L + s; // Value in s promoted to long: unboxing, widening.
/*
 * Value in s is unboxed. This short value and the char
 * value in c are promoted to int, followed by implicit
 * widening conversion of int to float on assignment
 * */
float r = s + c;
/*
 * Value in i promoted to float, followed by implicit
 * widening conversion of float to double on assignment
 * */
double d = r + i;
```

- Binary numeric promotion for operands of binary operators implies that each operand of a binary operator is promoted to type int or a broader numeric type, if necessary
- As with unary operators, care must be exercised in assigning the value resulting from applying a binary operator to operands of these types

```java
short h = 40; // OK: int converted to short. Implicit narrowing.
h =h +2; // Error: cannot assign an int to short, result is in the range of short, this cannot be determined at compile time
h =(short)(h +2); // OK
h =(short)h +(short)2; // The resulting value should be cast, compile time error
h =(short)h +2; // The resulting value should be cast, compile time error
```

#### Arithmetic Compound Assignment Operators: `*=`, `/=`, `%=`, `+=`, `-=`

- A compound assignment operator has syntax `variable op= expression` and semantics `variable = (type) ((variable) op (expression))`
    - The type of the variable is type and the variable is evaluated only once
- Implicit narrowing conversions are also applied to increment and decrement operators

```java
int i = 2;
i *=i +4; // (1) Evaluated as i = (int) ((i) * (i + 4)).
Integer iRef = 2;
iRef *=iRef +4; // (2) Evaluated as iRef = (Integer) ((iRef) * (iRef + 4)).
byte b = 2;
b +=10; // (3) Evaluated as b = (byte) (b + 10).
b =b +10; // (4) Will not compile. Cast is required.
int[] a = new int[]{2020, 2030, 2040};
int i = 2;
a[i]+=1; // Evaluates as a[2] = a[2] + 1, and a[2] gets the value 2041
```

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