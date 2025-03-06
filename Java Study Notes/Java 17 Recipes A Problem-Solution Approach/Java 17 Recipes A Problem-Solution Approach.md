# Java 17 Recipes A Problem-Solution Approach

------------------------------------------------------------------------------------------------------------------

## Table of Contents

<!-- TOC -->

* [Java 17 Recipes A Problem-Solution Approach](#java-17-recipes-a-problem-solution-approach)
    * [Table of Contents](#table-of-contents)
    * [Getting Started with Java 17](#getting-started-with-java-17)
        * [Installing Java](#installing-java)
            * [Problem](#problem)
            * [Solution](#solution)
            * [How It Works](#how-it-works)
        * [Configuring the PATH](#configuring-the-path)
            * [Problem](#problem-1)
            * [Solution](#solution-1)
            * [How It Works](#how-it-works-1)
        * [Testing Java](#testing-java)
            * [Problem](#problem-2)
            * [Solution](#solution-2)
            * [How It Works](#how-it-works-2)
        * [Installing Eclipse](#installing-eclipse)
            * [Problem](#problem-3)
            * [Solution](#solution-3)
            * [How It Works](#how-it-works-3)
        * [Getting to “Hello, World”](#getting-to-hello-world)
            * [Problem](#problem-4)
            * [Solution](#solution-4)
            * [How It Works](#how-it-works-4)
        * [Configuring the CLASSPATH](#configuring-the-classpath)
            * [Problem](#problem-5)
            * [Solution](#solution-5)
            * [How It Works](#how-it-works-5)
        * [Organizing Code with Packages](#organizing-code-with-packages)
            * [Problem](#problem-6)
            * [Solution](#solution-6)
            * [How It Works](#how-it-works-6)
        * [Declaring Variables and Access Modifiers](#declaring-variables-and-access-modifiers)
            * [Problem](#problem-7)
            * [Solution](#solution-7)
            * [How It Works](#how-it-works-7)
        * [Converting to and from a String](#converting-to-and-from-a-string)
            * [Problem](#problem-8)
            * [Solution](#solution-8)
            * [How It Works](#how-it-works-8)
        * [Passing Arguments via Command-Line Execution](#passing-arguments-via-command-line-execution)
            * [Problem](#problem-9)
            * [Solution](#solution-9)
            * [How It Works](#how-it-works-9)
        * [Accepting Input from the Keyboard](#accepting-input-from-the-keyboard)
            * [Problem](#problem-10)
            * [Solution](#solution-10)
            * [How It Works](#how-it-works-10)
        * [Documenting Your Code](#documenting-your-code)
            * [Problem](#problem-11)
            * [Solution](#solution-11)
            * [How It Works](#how-it-works-11)
        * [Reading Environment Variables](#reading-environment-variables)
            * [Problem](#problem-12)
            * [Solution](#solution-12)
            * [How It Works](#how-it-works-12)
            * [Summary](#summary)
    * [Enhancements from Java 9 Through Java 17](#enhancements-from-java-9-through-java-17)
        * [Introduction to the var Keyword](#introduction-to-the-var-keyword)
            * [Problem](#problem-13)
            * [Solution](#solution-13)
            * [How It Works](#how-it-works-13)
        * [Reading the Contents of Files](#reading-the-contents-of-files)
            * [Problem](#problem-14)
            * [Solution](#solution-14)
            * [How It Works](#how-it-works-14)
        * [Writing a Text Block](#writing-a-text-block)
            * [Problem](#problem-15)
            * [Solution](#solution-15)
            * [How It Works](#how-it-works-15)
        * [The Enhancement of NullPointerException](#the-enhancement-of-nullpointerexception)
            * [Problem](#problem-16)
            * [Solution](#solution-16)
            * [How It Works](#how-it-works-16)
        * [Pattern Matching for instanceof](#pattern-matching-for-instanceof)
            * [Problem](#problem-17)
            * [Solution](#solution-17)
            * [How It Works](#how-it-works-17)
        * [Using Record](#using-record)
            * [Problem](#problem-18)
            * [Solution](#solution-18)
            * [How It Works](#how-it-works-18)
        * [Restore Always-Strict Floating-Point Semantics](#restore-always-strict-floating-point-semantics)
            * [Problem](#problem-19)
            * [Solution](#solution-19)
            * [How It Works](#how-it-works-19)
        * [Pseudorandom Number Generators](#pseudorandom-number-generators)
            * [Problem](#problem-20)
            * [Solution](#solution-20)
            * [How It Works](#how-it-works-20)
        * [Sealed Classes](#sealed-classes)
            * [Problem](#problem-21)
            * [Solution](#solution-21)
            * [How It Works](#how-it-works-21)
        * [The Vector API](#the-vector-api)
            * [Problem](#problem-22)
            * [Solution](#solution-22)
            * [How It Works](#how-it-works-22)
        * [Avoiding Redundancy in Interface Code](#avoiding-redundancy-in-interface-code)
            * [Problem](#problem-23)
            * [Solution](#solution-23)
            * [How It Works](#how-it-works-23)
        * [Easily Retrieving Information on OS Processes](#easily-retrieving-information-on-os-processes)
            * [Problem](#problem-24)
            * [Solution](#solution-24)
            * [How It Works](#how-it-works-24)
        * [Handling try-with-resources Construct](#handling-try-with-resources-construct)
            * [Problem](#problem-25)
            * [Solution](#solution-25)
            * [How It Works](#how-it-works-25)
        * [Filtering Data Before and After a Condition with Streams](#filtering-data-before-and-after-a-condition-with-streams)
            * [Problem](#problem-26)
            * [Solution](#solution-26)
            * [How It Works](#how-it-works-26)
        * [Utilizing Factory Methods to Create Immutable Collections](#utilizing-factory-methods-to-create-immutable-collections)
            * [Problem](#problem-27)
            * [Solution](#solution-27)
            * [How It Works](#how-it-works-27)
        * [Pattern Matching for switch (Preview)](#pattern-matching-for-switch-preview)
            * [Problem](#problem-28)
            * [Solution](#solution-28)
            * [How It Works](#how-it-works-28)
            * [Summary](#summary-1)
    * [Strings](#strings)
        * [Compact Strings](#compact-strings)
        * [Obtaining a Subsection of a String](#obtaining-a-subsection-of-a-string)
            * [Problem](#problem-29)
            * [Solution](#solution-29)
            * [How It Works](#how-it-works-29)
        * [Comparing Strings](#comparing-strings)
            * [Problem](#problem-30)
            * [Solution](#solution-30)
            * [How It Works](#how-it-works-30)
        * [Trimming Whitespace](#trimming-whitespace)
            * [Problem](#problem-31)
            * [Solution](#solution-31)
            * [How It Works](#how-it-works-31)
        * [Discovering Blank Strings](#discovering-blank-strings)
            * [Problem](#problem-32)
            * [Solution](#solution-32)
            * [How It Works](#how-it-works-32)
        * [Stripping Whitespace](#stripping-whitespace)
            * [Problem](#problem-33)
            * [Solution](#solution-33)
            * [How It Works](#how-it-works-33)
        * [Breaking String Lines](#breaking-string-lines)
            * [Problem](#problem-34)
            * [Solution](#solution-34)
            * [How It Works](#how-it-works-34)
        * [Repeating Strings](#repeating-strings)
            * [Problem](#problem-35)
            * [Solution](#solution-35)
            * [How It Works](#how-it-works-35)
        * [Changing the Case of a String](#changing-the-case-of-a-string)
            * [Problem](#problem-36)
            * [Solution](#solution-36)
            * [How It Works](#how-it-works-36)
        * [Concatenating Strings](#concatenating-strings)
            * [Problem](#problem-37)
            * [Solution 1](#solution-1)
            * [Solution 2](#solution-2)
            * [Solution 3](#solution-3)
            * [How It Works](#how-it-works-37)
        * [Converting Strings to Numeric Values](#converting-strings-to-numeric-values)
            * [Problem](#problem-38)
            * [Solution 1](#solution-1-1)
            * [Solution 2](#solution-2-1)
            * [How It Works](#how-it-works-38)
        * [Iterating Over the Characters of a String](#iterating-over-the-characters-of-a-string)
            * [Problem](#problem-39)
            * [Solution](#solution-37)
            * [How It Works](#how-it-works-39)
        * [Finding Text Matches](#finding-text-matches)
            * [Problem](#problem-40)
            * [Solution 1](#solution-1-2)
            * [Solution 2](#solution-2-2)
            * [How It Works](#how-it-works-40)
        * [Replacing All Text Matches](#replacing-all-text-matches)
            * [Problem](#problem-41)
            * [Solution](#solution-38)
            * [How It Works](#how-it-works-41)
            * [Solution 2](#solution-2-3)
            * [How It Works](#how-it-works-42)
        * [Randomly Generating Values](#randomly-generating-values)
            * [Problem](#problem-42)
            * [Solution 1](#solution-1-3)
            * [Solution 2](#solution-2-4)
            * [How It Works](#how-it-works-43)
        * [Obtaining the Current Date Without Time](#obtaining-the-current-date-without-time)
            * [Problem](#problem-43)
            * [Solution](#solution-39)
            * [How It Works](#how-it-works-44)
        * [Obtaining a Date Object Given Date Criteria](#obtaining-a-date-object-given-date-criteria)
            * [Problem](#problem-44)
            * [Solution](#solution-40)
            * [How It Works](#how-it-works-45)
        * [Obtaining a Year-Month-Day Date Combination](#obtaining-a-year-month-day-date-combination)
            * [Problem](#problem-45)
            * [Solution 1](#solution-1-4)
            * [Solution 2](#solution-2-5)
            * [How It Works](#how-it-works-46)
        * [Obtaining and Calculating Times Based on the Current Time](#obtaining-and-calculating-times-based-on-the-current-time)
            * [Problem](#problem-46)
            * [Solution](#solution-41)
            * [How It Works](#how-it-works-47)
        * [Obtaining and Using the Date and Time Together](#obtaining-and-using-the-date-and-time-together)
            * [Problem](#problem-47)
            * [Solution 1](#solution-1-5)
            * [Solution 2](#solution-2-6)
            * [Solution 3](#solution-3-1)
            * [How It Works](#how-it-works-48)
        * [Obtaining a Machine Timestamp](#obtaining-a-machine-timestamp)
            * [Problem](#problem-48)
            * [Solution](#solution-42)
            * [How It Works](#how-it-works-49)
        * [Converting Dates and Times Based on the Time Zone](#converting-dates-and-times-based-on-the-time-zone)
            * [Problem](#problem-49)
            * [Solution](#solution-43)
            * [How It Works](#how-it-works-50)
        * [Comparing Two Dates](#comparing-two-dates)
            * [Problem](#problem-50)
            * [Solution](#solution-44)
            * [How It Works](#how-it-works-51)
        * [Finding the Interval Between Dates and Times](#finding-the-interval-between-dates-and-times)
            * [Problem](#problem-51)
            * [Solution 1](#solution-1-6)
            * [Solution 2](#solution-2-7)
            * [How It Works](#how-it-works-52)
        * [Obtaining Date-Time from a Specified String](#obtaining-date-time-from-a-specified-string)
            * [Problem](#problem-52)
            * [Solution](#solution-45)
            * [How It Works](#how-it-works-53)
        * [Formatting Dates for Display](#formatting-dates-for-display)
            * [Problem](#problem-53)
            * [Solution 1](#solution-1-7)
            * [Solution 2](#solution-2-8)
            * [How It Works](#how-it-works-54)
        * [Writing Readable Numeric Literals](#writing-readable-numeric-literals)
            * [Problem](#problem-54)
            * [Solution](#solution-46)
            * [How It Works](#how-it-works-55)
        * [Declaring Binary Literals](#declaring-binary-literals)
            * [Problem](#problem-55)
            * [Solution](#solution-47)
            * [How It Works](#how-it-works-56)
        * [Period of Day](#period-of-day)
            * [Problem](#problem-56)
            * [Solution](#solution-48)
            * [How It Works](#how-it-works-57)
            * [Summary](#summary-2)
    * [Object-Oriented Java](#object-oriented-java)
        * [Controlling Access to Members of a Class](#controlling-access-to-members-of-a-class)
            * [Problem](#problem-57)
            * [Solution](#solution-49)
            * [How It Works](#how-it-works-58)
        * [Making Private Fields Accessible to Other Classes](#making-private-fields-accessible-to-other-classes)
            * [Problem](#problem-58)
            * [Solution](#solution-50)
            * [How It Works](#how-it-works-59)
        * [Creating a Class with a Single Instance](#creating-a-class-with-a-single-instance)
            * [Problem](#problem-59)
            * [Solution 1](#solution-1-8)
            * [Solution 2](#solution-2-9)
            * [How It Works](#how-it-works-60)
        * [Generating Instances of a Class](#generating-instances-of-a-class)
            * [Problem](#problem-60)
            * [Solution](#solution-51)
            * [How It Works](#how-it-works-61)
        * [Creating Reusable Objects](#creating-reusable-objects)
            * [Problem](#problem-61)
            * [Solution](#solution-52)
            * [How It Works](#how-it-works-62)
        * [Defining an Interface for a Class](#defining-an-interface-for-a-class)
            * [Problem](#problem-62)
            * [Solution](#solution-53)
            * [How It Works](#how-it-works-63)
        * [Modifying Interfaces Without Breaking Existing Code](#modifying-interfaces-without-breaking-existing-code)
            * [Problem](#problem-63)
            * [Solution](#solution-54)
            * [How It Works](#how-it-works-64)
        * [Constructing Instances of the Same Class with Different Values](#constructing-instances-of-the-same-class-with-different-values)
            * [Problem](#problem-64)
            * [Solution](#solution-55)
            * [How It Works](#how-it-works-65)
        * [Interacting with a Class via Interfaces](#interacting-with-a-class-via-interfaces)
            * [Problem](#problem-65)
            * [Solution](#solution-56)
            * [How It Works](#how-it-works-66)
        * [Making a Class Cloneable](#making-a-class-cloneable)
            * [Problem](#problem-66)
            * [Solution](#solution-57)
            * [How It Works](#how-it-works-67)
        * [Comparing Objects](#comparing-objects)
            * [Problem](#problem-67)
            * [Solution 1](#solution-1-9)
            * [Solution 2](#solution-2-10)
            * [How It Works](#how-it-works-68)
        * [Extending the Functionality of a Class](#extending-the-functionality-of-a-class)
            * [Problem](#problem-68)
            * [Solution](#solution-58)
            * [How It Works](#how-it-works-69)
        * [Defining a Template for Classes to Extend](#defining-a-template-for-classes-to-extend)
            * [Problem](#problem-69)
            * [Solution](#solution-59)
            * [How It Works](#how-it-works-70)
        * [Increasing Class Encapsulation](#increasing-class-encapsulation)
            * [Problem](#problem-70)
            * [Solution](#solution-60)
            * [How It Works](#how-it-works-71)
            * [Summary](#summary-3)
    * [Lambda Expressions](#lambda-expressions)
        * [Writing a Simple Lambda Expression](#writing-a-simple-lambda-expression)
            * [Problem](#problem-71)
            * [Solution](#solution-61)
            * [How It Works](#how-it-works-72)
        * [Enabling the Use of Lambda Expressions](#enabling-the-use-of-lambda-expressions)
            * [Problem](#problem-72)
            * [Solution 1](#solution-1-10)
            * [Solution 2](#solution-2-11)
            * [How It Works](#how-it-works-73)
        * [Invoking Existing Methods by Name](#invoking-existing-methods-by-name)
            * [Problem](#problem-73)
            * [Solution](#solution-62)
            * [How It Works](#how-it-works-74)
        * [Sorting with Fewer Lines of Code](#sorting-with-fewer-lines-of-code)
            * [Problem](#problem-74)
            * [Solution 1](#solution-1-11)
            * [Solution 2](#solution-2-12)
            * [How It Works](#how-it-works-75)
        * [Filtering a Collection of Data](#filtering-a-collection-of-data)
            * [Problem](#problem-75)
            * [Solution](#solution-63)
            * [How It Works](#how-it-works-76)
        * [Implementing Runnable](#implementing-runnable)
            * [Problem](#problem-76)
            * [Solution](#solution-64)
            * [How It Works](#how-it-works-77)
        * [Accessing Class Variables from a Lambda Expression](#accessing-class-variables-from-a-lambda-expression)
            * [Problem](#problem-77)
            * [Solution](#solution-65)
            * [How It Works](#how-it-works-78)
        * [Passing Lambda Expressions to Methods](#passing-lambda-expressions-to-methods)
            * [Problem](#problem-78)
            * [Solution](#solution-66)
            * [How It Works](#how-it-works-79)
        * [Local Variable](#local-variable)
            * [Problem](#problem-79)
            * [Solution](#solution-67)
            * [How It Works](#how-it-works-80)
        * [Switch Expressions](#switch-expressions)
            * [Problem](#problem-80)
            * [Solution](#solution-68)
            * [How It Works](#how-it-works-81)
            * [Summary](#summary-4)
    * [Data Sources and Collections](#data-sources-and-collections)
        * [Defining a Fixed Set of Related Constants](#defining-a-fixed-set-of-related-constants)
            * [Problem](#problem-81)
            * [Solution](#solution-69)
            * [How It Works](#how-it-works-82)
        * [Designing Intelligent Constants](#designing-intelligent-constants)
            * [Problem](#problem-82)
            * [Solution](#solution-70)
            * [How It Works](#how-it-works-83)
        * [Executing Code Based on a Specified Value](#executing-code-based-on-a-specified-value)
            * [Problem](#problem-83)
            * [Solution](#solution-71)
            * [How It Works](#how-it-works-84)
        * [Working with Fix-Sized Arrays](#working-with-fix-sized-arrays)
            * [Problem](#problem-84)
            * [Solution](#solution-72)
            * [How It Works](#how-it-works-85)
        * [Safely Enabling Types or Methods to Operate on Objects of Various Types](#safely-enabling-types-or-methods-to-operate-on-objects-of-various-types)
            * [Problem](#problem-85)
            * [Solution](#solution-73)
            * [How It Works](#how-it-works-86)
        * [Working with Dynamic Arrays](#working-with-dynamic-arrays)
            * [Problem](#problem-86)
            * [Solution](#solution-74)
            * [How It Works](#how-it-works-87)
        * [Making Your Objects Iterable](#making-your-objects-iterable)
            * [Problem](#problem-87)
            * [Solution](#solution-75)
            * [How It Works](#how-it-works-88)
        * [Iterating Collections](#iterating-collections)
            * [Problem](#problem-88)
            * [Solution](#solution-76)
            * [How It Works](#how-it-works-89)
        * [Iterating Over a Map](#iterating-over-a-map)
            * [Problem](#problem-89)
            * [Solution](#solution-77)
            * [How It Works](#how-it-works-90)
        * [Executing Streams in Parallel](#executing-streams-in-parallel)
            * [Problem](#problem-90)
            * [Solution](#solution-78)
            * [How It Works](#how-it-works-91)
            * [Summary](#summary-5)
    * [Input and Output](#input-and-output)
        * [Serializing Java Objects](#serializing-java-objects)
            * [Problem](#problem-91)
            * [Solution](#solution-79)
            * [How It Works](#how-it-works-92)
        * [Serializing Java Objects More Efficiently](#serializing-java-objects-more-efficiently)
            * [Problem](#problem-92)
            * [Solution](#solution-80)
            * [How It Works](#how-it-works-93)
        * [Serializing Java Objects as XML](#serializing-java-objects-as-xml)
            * [Problem](#problem-93)
            * [Solution](#solution-81)
            * [How It Works](#how-it-works-94)
        * [Creating a Socket Connection and Sending Serializable Objects Across the Wire](#creating-a-socket-connection-and-sending-serializable-objects-across-the-wire)
            * [Problem](#problem-94)
            * [Solution](#solution-82)
            * [How It Works](#how-it-works-95)
        * [Obtaining the Java Execution Path](#obtaining-the-java-execution-path)
            * [Problem](#problem-95)
            * [Solution](#solution-83)
            * [How It Works](#how-it-works-96)
        * [Copying a File](#copying-a-file)
            * [Problem](#problem-96)
            * [Solution](#solution-84)
            * [How It Works](#how-it-works-97)
        * [Moving a File](#moving-a-file)
            * [Problem](#problem-97)
            * [Solution](#solution-85)
            * [How It Works](#how-it-works-98)
        * [Iterating Over Files in a Directory](#iterating-over-files-in-a-directory)
            * [Problem](#problem-98)
            * [Solution](#solution-86)
            * [How It Works](#how-it-works-99)
        * [Querying (and Setting) File Metadata](#querying-and-setting-file-metadata)
            * [Problem](#problem-99)
            * [Solution](#solution-87)
            * [How It Works](#how-it-works-100)
        * [Monitoring a Directory for Content Changes](#monitoring-a-directory-for-content-changes)
            * [Problem](#problem-100)
            * [Solution](#solution-88)
            * [How It Works](#how-it-works-101)
        * [Reading Property Files](#reading-property-files)
            * [Problem](#problem-101)
            * [Solution](#solution-89)
            * [How It Works](#how-it-works-102)
        * [Uncompressing Files](#uncompressing-files)
            * [Problem](#problem-102)
            * [Solution](#solution-90)
            * [How It Works](#how-it-works-103)
            * [Summary](#summary-6)
    * [Exceptions and Logging](#exceptions-and-logging)
        * [Catching Exceptions](#catching-exceptions)
            * [Problem](#problem-103)
            * [Solution](#solution-91)
            * [How It Works](#how-it-works-104)
        * [Guaranteeing a Block of Code Is Executed](#guaranteeing-a-block-of-code-is-executed)
            * [Problem](#problem-104)
            * [Solution](#solution-92)
            * [How It Works](#how-it-works-105)
        * [Throwing Exceptions](#throwing-exceptions)
            * [Problem](#problem-105)
            * [Solution](#solution-93)
            * [How It Works](#how-it-works-106)
        * [Catching Multiple Exceptions](#catching-multiple-exceptions)
            * [Problem](#problem-106)
            * [Solution 1](#solution-1-12)
            * [Solution 2](#solution-2-13)
            * [How It Works](#how-it-works-107)
        * [Catching the Uncaught Exceptions](#catching-the-uncaught-exceptions)
            * [Problem](#problem-107)
            * [Solution 1](#solution-1-13)
            * [Solution 2](#solution-2-14)
            * [How It Works](#how-it-works-108)
        * [Managing Resources with try/catch Blocks](#managing-resources-with-trycatch-blocks)
            * [Problem](#problem-108)
            * [Solution](#solution-94)
            * [How It Works](#how-it-works-109)
        * [Creating an Exception Class](#creating-an-exception-class)
            * [Problem](#problem-109)
            * [Solution 1](#solution-1-14)
            * [Solution 2](#solution-2-15)
            * [How It Works](#how-it-works-110)
        * [Logging Events Within Your Application](#logging-events-within-your-application)
            * [Problem](#problem-110)
            * [Solution](#solution-95)
            * [How It Works](#how-it-works-111)
        * [Rotating and Purging Logs](#rotating-and-purging-logs)
            * [Problem](#problem-111)
            * [Solution](#solution-96)
            * [How It Works](#how-it-works-112)
        * [Logging Exceptions](#logging-exceptions)
            * [Problem](#problem-112)
            * [Solution](#solution-97)
            * [How It Works](#how-it-works-113)
            * [Summary](#summary-7)
    * [Concurrency](#concurrency)
        * [Starting a Background Task](#starting-a-background-task)
            * [Problem](#problem-113)
            * [Solution](#solution-98)
            * [How It Works](#how-it-works-114)
        * [Updating (and Iterating) a Map](#updating-and-iterating-a-map)
            * [Problem](#problem-114)
            * [Solution](#solution-99)
            * [How It Works](#how-it-works-115)
        * [Inserting a Key into a Map Only If the Key Is Not Already Present](#inserting-a-key-into-a-map-only-if-the-key-is-not-already-present)
            * [Problem](#problem-115)
            * [Solution](#solution-100)
            * [How It Works](#how-it-works-116)
        * [Iterating Through a Changing Collection](#iterating-through-a-changing-collection)
            * [Problem](#problem-116)
            * [Solution 1](#solution-1-15)
            * [Solution 2](#solution-2-16)
            * [How It Works](#how-it-works-117)
        * [Coordinating Different Collections](#coordinating-different-collections)
            * [Problem](#problem-117)
            * [Solution 1](#solution-1-16)
            * [Solution 2](#solution-2-17)
            * [How It Works](#how-it-works-118)
        * [Splitting Work into Separate Threads](#splitting-work-into-separate-threads)
            * [Problem](#problem-118)
            * [Solution](#solution-101)
            * [How It Works](#how-it-works-119)
        * [Coordinating Threads](#coordinating-threads)
            * [Problem](#problem-119)
            * [Solution 1](#solution-1-17)
            * [Solution 2](#solution-2-18)
            * [Solution 3](#solution-3-2)
            * [How It Works](#how-it-works-120)
        * [Creating Thread-Safe Objects](#creating-thread-safe-objects)
            * [Problem](#problem-120)
            * [Solution 1](#solution-1-18)
            * [Solution 2](#solution-2-19)
            * [How It Works](#how-it-works-121)
        * [Implementing Thread-Safe Counters](#implementing-thread-safe-counters)
            * [Problem](#problem-121)
            * [Solution](#solution-102)
            * [How It Works](#how-it-works-122)
        * [Updating a Common Value Across Multiple Threads](#updating-a-common-value-across-multiple-threads)
            * [Problem](#problem-122)
            * [Solution](#solution-103)
            * [How It Works](#how-it-works-123)
        * [Executing Multiple Tasks Asynchronously](#executing-multiple-tasks-asynchronously)
            * [Problem](#problem-123)
            * [Solution](#solution-104)
            * [How It Works](#how-it-works-124)
            * [Summary](#summary-8)
    * [Unicode, Internationalization, and Currency Codes](#unicode-internationalization-and-currency-codes)
        * [Converting Unicode Characters to Digits](#converting-unicode-characters-to-digits)
            * [Problem](#problem-124)
            * [Solution](#solution-105)
            * [How It Works](#how-it-works-125)
        * [Creating and Working with Locales](#creating-and-working-with-locales)
            * [Problem](#problem-125)
            * [Solution](#solution-106)
            * [How It Works](#how-it-works-126)
        * [Matching and Filtering Locales](#matching-and-filtering-locales)
            * [Problem](#problem-126)
            * [Solution](#solution-107)
            * [How It Works](#how-it-works-127)
        * [Searching Unicode with Regular Expressions](#searching-unicode-with-regular-expressions)
            * [Problem](#problem-127)
            * [Solution 1](#solution-1-19)
            * [Solution 2](#solution-2-20)
            * [How It Works](#how-it-works-128)
        * [Overriding the Default Currency](#overriding-the-default-currency)
            * [Problem](#problem-128)
            * [Solution](#solution-108)
            * [How It Works](#how-it-works-129)
        * [Converting Byte Arrays to and from Strings](#converting-byte-arrays-to-and-from-strings)
            * [Problem](#problem-129)
            * [Solution](#solution-109)
            * [How It Works](#how-it-works-130)
        * [Converting Character Streams and Buffers](#converting-character-streams-and-buffers)
            * [Problem](#problem-130)
            * [Solution 1](#solution-1-20)
            * [Solution 2](#solution-2-21)
            * [How It Works](#how-it-works-131)
            * [Summary](#summary-9)
    * [Working with Databases](#working-with-databases)
        * [Installing MySQL](#installing-mysql)
            * [Problem](#problem-131)
            * [Solution](#solution-110)
            * [How It Works](#how-it-works-132)
        * [Connecting to a Database](#connecting-to-a-database)
            * [Problem](#problem-132)
            * [Solution](#solution-111)
            * [How It Works](#how-it-works-133)
        * [Handling Connection and SQL Exceptions](#handling-connection-and-sql-exceptions)
            * [Problem](#problem-133)
            * [Solution](#solution-112)
            * [How It Works](#how-it-works-134)
        * [Querying a Database and Retrieving Results](#querying-a-database-and-retrieving-results)
            * [Problem](#problem-134)
            * [Solution](#solution-113)
            * [How It Works](#how-it-works-135)
        * [Performing CRUD Operations](#performing-crud-operations)
            * [Problem](#problem-135)
            * [Solution](#solution-114)
            * [How It Works](#how-it-works-136)
        * [Simplifying Connection Management](#simplifying-connection-management)
            * [Problem](#problem-136)
            * [Solution](#solution-115)
            * [How It Works](#how-it-works-137)
        * [Guarding Against SQL Injection](#guarding-against-sql-injection)
            * [Problem](#problem-137)
            * [Solution](#solution-116)
            * [How It Works](#how-it-works-138)
        * [Performing Transactions](#performing-transactions)
            * [Problem](#problem-138)
            * [Solution](#solution-117)
            * [How It Works](#how-it-works-139)
        * [Creating a Scrollable ResultSet](#creating-a-scrollable-resultset)
            * [Problem](#problem-139)
            * [Solution](#solution-118)
            * [How It Works](#how-it-works-140)
        * [Creating an Updatable ResultSet](#creating-an-updatable-resultset)
            * [Problem](#problem-140)
            * [Solution](#solution-119)
            * [How It Works](#how-it-works-141)
        * [Caching Data for Use When Disconnected](#caching-data-for-use-when-disconnected)
            * [Problem](#problem-141)
            * [Solution](#solution-120)
            * [How It Works](#how-it-works-142)
        * [Obtaining Dates for Database Use](#obtaining-dates-for-database-use)
            * [Problem](#problem-142)
            * [Solution](#solution-121)
            * [How It Works](#how-it-works-143)
        * [Closing Resources Automatically](#closing-resources-automatically)
            * [Problem](#problem-143)
            * [Solution](#solution-122)
            * [How It Works](#how-it-works-144)
            * [Summary](#summary-10)
    * [Java Web Applications](#java-web-applications)
        * [Installing Tomcat](#installing-tomcat)
            * [Problem](#problem-144)
            * [Solution](#solution-123)
            * [How It Works](#how-it-works-145)
        * [Creating an HTML Page](#creating-an-html-page)
            * [Problem](#problem-145)
            * [Solution](#solution-124)
            * [How It Works](#how-it-works-146)
        * [Creating a JSP Page](#creating-a-jsp-page)
            * [Problem](#problem-146)
            * [Solution](#solution-125)
            * [How It Works](#how-it-works-147)
        * [Listing the HTML-Request Parameters](#listing-the-html-request-parameters)
            * [Problem](#problem-147)
            * [Solution](#solution-126)
            * [How It Works](#how-it-works-148)
        * [Creating and Configuring a Web Project](#creating-and-configuring-a-web-project)
            * [Problem](#problem-148)
            * [Solution](#solution-127)
            * [How It Works](#how-it-works-149)
        * [Creating a Servlet](#creating-a-servlet)
            * [Problem](#problem-149)
            * [Solution](#solution-128)
            * [How It Works](#how-it-works-150)
        * [Using a Servlet for Representing Values](#using-a-servlet-for-representing-values)
            * [Problem](#problem-150)
            * [Solution](#solution-129)
            * [How It Works](#how-it-works-151)
            * [Summary](#summary-11)
    * [Email](#email)
        * [Installing JavaMail](#installing-javamail)
            * [Problem](#problem-151)
            * [Solution](#solution-130)
            * [How It Works](#how-it-works-152)
        * [Sending an Email](#sending-an-email)
            * [Problem](#problem-152)
            * [Solution](#solution-131)
            * [How It Works](#how-it-works-153)
        * [Attaching Files to an Email Message](#attaching-files-to-an-email-message)
            * [Problem](#problem-153)
            * [Solution](#solution-132)
            * [How It Works](#how-it-works-154)
        * [Sending an HTML Email](#sending-an-html-email)
            * [Problem](#problem-154)
            * [Solution](#solution-133)
            * [How It Works](#how-it-works-155)
        * [Sending Email to a Group of Recipients](#sending-email-to-a-group-of-recipients)
            * [Problem](#problem-155)
            * [Solution](#solution-134)
            * [How It Works](#how-it-works-156)
        * [Checking Email](#checking-email)
            * [Problem](#problem-156)
            * [Solution](#solution-135)
            * [How It Works](#how-it-works-157)
            * [Summary](#summary-12)
    * [JSON and XML Processing](#json-and-xml-processing)
        * [Writing an XML File](#writing-an-xml-file)
            * [Problem](#problem-157)
            * [Solution](#solution-136)
            * [How It Works](#how-it-works-158)
        * [Reading an XML File](#reading-an-xml-file)
            * [Problem](#problem-158)
            * [Solution 1](#solution-1-21)
            * [Solution 2](#solution-2-22)
            * [How It Works](#how-it-works-159)
        * [Transforming XML](#transforming-xml)
            * [Problem](#problem-159)
            * [Solution](#solution-137)
            * [How It Works](#how-it-works-160)
        * [Validating XML](#validating-xml)
            * [Problem](#problem-160)
            * [Solution](#solution-138)
            * [How It Works](#how-it-works-161)
        * [Working with JSON](#working-with-json)
            * [Problem](#problem-161)
            * [Solution](#solution-139)
            * [How It Works](#how-it-works-162)
        * [Building a JSON Object](#building-a-json-object)
            * [Problem](#problem-162)
            * [Solution](#solution-140)
            * [How It Works](#how-it-works-163)
        * [Writing a JSON Object to File](#writing-a-json-object-to-file)
            * [Problem](#problem-163)
            * [Solution](#solution-141)
            * [How It Works](#how-it-works-164)
        * [Parsing a JSON Object](#parsing-a-json-object)
            * [Problem](#problem-164)
            * [Solution](#solution-142)
            * [How It Works](#how-it-works-165)
            * [Summary](#summary-13)
    * [Networking](#networking)
        * [Listening for Connections on the Server](#listening-for-connections-on-the-server)
            * [Problem](#problem-165)
            * [Solution](#solution-143)
            * [How It Works](#how-it-works-166)
        * [Defining a Network Connection to a Server](#defining-a-network-connection-to-a-server)
            * [Problem](#problem-166)
            * [Solution](#solution-144)
            * [How It Works](#how-it-works-167)
        * [Broadcasting to a Group of Recipients](#broadcasting-to-a-group-of-recipients)
            * [Problem](#problem-167)
            * [Solution](#solution-145)
            * [How It Works](#how-it-works-168)
        * [Generating and Reading from URLs](#generating-and-reading-from-urls)
            * [Problem](#problem-168)
            * [Solution](#solution-146)
            * [How It Works](#how-it-works-169)
        * [Parsing a URL](#parsing-a-url)
            * [Problem](#problem-169)
            * [Solution](#solution-147)
            * [How It Works](#how-it-works-170)
            * [Summary](#summary-14)

<!-- TOC -->
------------------------------------------------------------------------------------------------------------------

## Getting Started with Java 17

### Installing Java

#### Problem

#### Solution

#### How It Works

### Configuring the PATH

#### Problem

#### Solution

#### How It Works

### Testing Java

#### Problem

#### Solution

#### How It Works

### Installing Eclipse

#### Problem

#### Solution

#### How It Works

### Getting to “Hello, World”

#### Problem

#### Solution

#### How It Works

### Configuring the CLASSPATH

#### Problem

#### Solution

#### How It Works

### Organizing Code with Packages

#### Problem

#### Solution

#### How It Works

### Declaring Variables and Access Modifiers

#### Problem

#### Solution

#### How It Works

### Converting to and from a String

#### Problem

#### Solution

#### How It Works

### Passing Arguments via Command-Line Execution

#### Problem

#### Solution

#### How It Works

### Accepting Input from the Keyboard

#### Problem

#### Solution

#### How It Works

### Documenting Your Code

#### Problem

#### Solution

#### How It Works

### Reading Environment Variables

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Enhancements from Java 9 Through Java 17

### Introduction to the var Keyword

#### Problem

#### Solution

#### How It Works

### Reading the Contents of Files

#### Problem

#### Solution

#### How It Works

### Writing a Text Block

#### Problem

#### Solution

#### How It Works

### The Enhancement of NullPointerException

#### Problem

#### Solution

#### How It Works

### Pattern Matching for instanceof

#### Problem

#### Solution

#### How It Works

### Using Record

#### Problem

#### Solution

#### How It Works

### Restore Always-Strict Floating-Point Semantics

#### Problem

#### Solution

#### How It Works

### Pseudorandom Number Generators

#### Problem

#### Solution

#### How It Works

### Sealed Classes

#### Problem

#### Solution

#### How It Works

### The Vector API

#### Problem

#### Solution

#### How It Works

### Avoiding Redundancy in Interface Code

#### Problem

#### Solution

#### How It Works

### Easily Retrieving Information on OS Processes

#### Problem

#### Solution

#### How It Works

### Handling try-with-resources Construct

#### Problem

#### Solution

#### How It Works

### Filtering Data Before and After a Condition with Streams

#### Problem

#### Solution

#### How It Works

### Utilizing Factory Methods to Create Immutable Collections

#### Problem

#### Solution

#### How It Works

### Pattern Matching for switch (Preview)

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Strings

### Compact Strings

### Obtaining a Subsection of a String

#### Problem

#### Solution

#### How It Works

### Comparing Strings

#### Problem

#### Solution

#### How It Works

### Trimming Whitespace

#### Problem

#### Solution

#### How It Works

### Discovering Blank Strings

#### Problem

#### Solution

#### How It Works

### Stripping Whitespace

#### Problem

#### Solution

#### How It Works

### Breaking String Lines

#### Problem

#### Solution

#### How It Works

### Repeating Strings

#### Problem

#### Solution

#### How It Works

### Changing the Case of a String

#### Problem

#### Solution

#### How It Works

### Concatenating Strings

#### Problem

#### Solution 1

#### Solution 2

#### Solution 3

#### How It Works

### Converting Strings to Numeric Values

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Iterating Over the Characters of a String

#### Problem

#### Solution

#### How It Works

### Finding Text Matches

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Replacing All Text Matches

#### Problem

#### Solution

#### How It Works

#### Solution 2

#### How It Works

### Randomly Generating Values

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Obtaining the Current Date Without Time

#### Problem

#### Solution

#### How It Works

### Obtaining a Date Object Given Date Criteria

#### Problem

#### Solution

#### How It Works

### Obtaining a Year-Month-Day Date Combination

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Obtaining and Calculating Times Based on the Current Time

#### Problem

#### Solution

#### How It Works

### Obtaining and Using the Date and Time Together

#### Problem

#### Solution 1

#### Solution 2

#### Solution 3

#### How It Works

### Obtaining a Machine Timestamp

#### Problem

#### Solution

#### How It Works

### Converting Dates and Times Based on the Time Zone

#### Problem

#### Solution

#### How It Works

### Comparing Two Dates

#### Problem

#### Solution

#### How It Works

### Finding the Interval Between Dates and Times

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Obtaining Date-Time from a Specified String

#### Problem

#### Solution

#### How It Works

### Formatting Dates for Display

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Writing Readable Numeric Literals

#### Problem

#### Solution

#### How It Works

### Declaring Binary Literals

#### Problem

#### Solution

#### How It Works

### Period of Day

#### Problem

#### Solution

#### How It Works

#### Summary

## Object-Oriented Java

------------------------------------------------------------------------------------------------------------------

### Controlling Access to Members of a Class

#### Problem

#### Solution

#### How It Works

### Making Private Fields Accessible to Other Classes

#### Problem

#### Solution

#### How It Works

### Creating a Class with a Single Instance

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Generating Instances of a Class

#### Problem

#### Solution

#### How It Works

### Creating Reusable Objects

#### Problem

#### Solution

#### How It Works

### Defining an Interface for a Class

#### Problem

#### Solution

#### How It Works

### Modifying Interfaces Without Breaking Existing Code

#### Problem

#### Solution

#### How It Works

### Constructing Instances of the Same Class with Different Values

#### Problem

#### Solution

#### How It Works

### Interacting with a Class via Interfaces

#### Problem

#### Solution

#### How It Works

### Making a Class Cloneable

#### Problem

#### Solution

#### How It Works

### Comparing Objects

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Extending the Functionality of a Class

#### Problem

#### Solution

#### How It Works

### Defining a Template for Classes to Extend

#### Problem

#### Solution

#### How It Works

### Increasing Class Encapsulation

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Lambda Expressions

### Writing a Simple Lambda Expression

#### Problem

#### Solution

#### How It Works

### Enabling the Use of Lambda Expressions

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Invoking Existing Methods by Name

#### Problem

#### Solution

#### How It Works

### Sorting with Fewer Lines of Code

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Filtering a Collection of Data

#### Problem

#### Solution

#### How It Works

### Implementing Runnable

#### Problem

#### Solution

#### How It Works

### Accessing Class Variables from a Lambda Expression

#### Problem

#### Solution

#### How It Works

### Passing Lambda Expressions to Methods

#### Problem

#### Solution

#### How It Works

### Local Variable

#### Problem

#### Solution

#### How It Works

### Switch Expressions

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Data Sources and Collections

### Defining a Fixed Set of Related Constants

#### Problem

#### Solution

#### How It Works

### Designing Intelligent Constants

#### Problem

#### Solution

#### How It Works

### Executing Code Based on a Specified Value

#### Problem

#### Solution

#### How It Works

### Working with Fix-Sized Arrays

#### Problem

#### Solution

#### How It Works

### Safely Enabling Types or Methods to Operate on Objects of Various Types

#### Problem

#### Solution

#### How It Works

### Working with Dynamic Arrays

#### Problem

#### Solution

#### How It Works

### Making Your Objects Iterable

#### Problem

#### Solution

#### How It Works

### Iterating Collections

#### Problem

#### Solution

#### How It Works

### Iterating Over a Map

#### Problem

#### Solution

#### How It Works

### Executing Streams in Parallel

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Input and Output

### Serializing Java Objects

#### Problem

#### Solution

#### How It Works

### Serializing Java Objects More Efficiently

#### Problem

#### Solution

#### How It Works

### Serializing Java Objects as XML

#### Problem

#### Solution

#### How It Works

### Creating a Socket Connection and Sending Serializable Objects Across the Wire

#### Problem

#### Solution

#### How It Works

### Obtaining the Java Execution Path

#### Problem

#### Solution

#### How It Works

### Copying a File

#### Problem

#### Solution

#### How It Works

### Moving a File

#### Problem

#### Solution

#### How It Works

### Iterating Over Files in a Directory

#### Problem

#### Solution

#### How It Works

### Querying (and Setting) File Metadata

#### Problem

#### Solution

#### How It Works

### Monitoring a Directory for Content Changes

#### Problem

#### Solution

#### How It Works

### Reading Property Files

#### Problem

#### Solution

#### How It Works

### Uncompressing Files

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Exceptions and Logging

### Catching Exceptions

#### Problem

#### Solution

#### How It Works

### Guaranteeing a Block of Code Is Executed

#### Problem

#### Solution

#### How It Works

### Throwing Exceptions

#### Problem

#### Solution

#### How It Works

### Catching Multiple Exceptions

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Catching the Uncaught Exceptions

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Managing Resources with try/catch Blocks

#### Problem

#### Solution

#### How It Works

### Creating an Exception Class

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Logging Events Within Your Application

#### Problem

#### Solution

#### How It Works

### Rotating and Purging Logs

#### Problem

#### Solution

#### How It Works

### Logging Exceptions

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Concurrency

### Starting a Background Task

#### Problem

#### Solution

#### How It Works

### Updating (and Iterating) a Map

#### Problem

#### Solution

#### How It Works

### Inserting a Key into a Map Only If the Key Is Not Already Present

#### Problem

#### Solution

#### How It Works

### Iterating Through a Changing Collection

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Coordinating Different Collections

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Splitting Work into Separate Threads

#### Problem

#### Solution

#### How It Works

### Coordinating Threads

#### Problem

#### Solution 1

#### Solution 2

#### Solution 3

#### How It Works

### Creating Thread-Safe Objects

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Implementing Thread-Safe Counters

#### Problem

#### Solution

#### How It Works

### Updating a Common Value Across Multiple Threads

#### Problem

#### Solution

#### How It Works

### Executing Multiple Tasks Asynchronously

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Unicode, Internationalization, and Currency Codes

### Converting Unicode Characters to Digits

#### Problem

#### Solution

#### How It Works

### Creating and Working with Locales

#### Problem

#### Solution

#### How It Works

### Matching and Filtering Locales

#### Problem

#### Solution

#### How It Works

### Searching Unicode with Regular Expressions

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Overriding the Default Currency

#### Problem

#### Solution

#### How It Works

### Converting Byte Arrays to and from Strings

#### Problem

#### Solution

#### How It Works

### Converting Character Streams and Buffers

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Working with Databases

### Installing MySQL

#### Problem

#### Solution

#### How It Works

### Connecting to a Database

#### Problem

#### Solution

#### How It Works

### Handling Connection and SQL Exceptions

#### Problem

#### Solution

#### How It Works

### Querying a Database and Retrieving Results

#### Problem

#### Solution

#### How It Works

### Performing CRUD Operations

#### Problem

#### Solution

#### How It Works

### Simplifying Connection Management

#### Problem

#### Solution

#### How It Works

### Guarding Against SQL Injection

#### Problem

#### Solution

#### How It Works

### Performing Transactions

#### Problem

#### Solution

#### How It Works

### Creating a Scrollable ResultSet

#### Problem

#### Solution

#### How It Works

### Creating an Updatable ResultSet

#### Problem

#### Solution

#### How It Works

### Caching Data for Use When Disconnected

#### Problem

#### Solution

#### How It Works

### Obtaining Dates for Database Use

#### Problem

#### Solution

#### How It Works

### Closing Resources Automatically

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Java Web Applications

### Installing Tomcat

#### Problem

#### Solution

#### How It Works

### Creating an HTML Page

#### Problem

#### Solution

#### How It Works

### Creating a JSP Page

#### Problem

#### Solution

#### How It Works

### Listing the HTML-Request Parameters

#### Problem

#### Solution

#### How It Works

### Creating and Configuring a Web Project

#### Problem

#### Solution

#### How It Works

### Creating a Servlet

#### Problem

#### Solution

#### How It Works

### Using a Servlet for Representing Values

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Email

### Installing JavaMail

#### Problem

#### Solution

#### How It Works

### Sending an Email

#### Problem

#### Solution

#### How It Works

### Attaching Files to an Email Message

#### Problem

#### Solution

#### How It Works

### Sending an HTML Email

#### Problem

#### Solution

#### How It Works

### Sending Email to a Group of Recipients

#### Problem

#### Solution

#### How It Works

### Checking Email

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## JSON and XML Processing

### Writing an XML File

#### Problem

#### Solution

#### How It Works

### Reading an XML File

#### Problem

#### Solution 1

#### Solution 2

#### How It Works

### Transforming XML

#### Problem

#### Solution

#### How It Works

### Validating XML

#### Problem

#### Solution

#### How It Works

### Working with JSON

#### Problem

#### Solution

#### How It Works

### Building a JSON Object

#### Problem

#### Solution

#### How It Works

### Writing a JSON Object to File

#### Problem

#### Solution

#### How It Works

### Parsing a JSON Object

#### Problem

#### Solution

#### How It Works

#### Summary

------------------------------------------------------------------------------------------------------------------

## Networking

### Listening for Connections on the Server

#### Problem

#### Solution

#### How It Works

### Defining a Network Connection to a Server

#### Problem

#### Solution

#### How It Works

### Broadcasting to a Group of Recipients

#### Problem

#### Solution

#### How It Works

### Generating and Reading from URLs

#### Problem

#### Solution

#### How It Works

### Parsing a URL

#### Problem

#### Solution

#### How It Works

#### Summary