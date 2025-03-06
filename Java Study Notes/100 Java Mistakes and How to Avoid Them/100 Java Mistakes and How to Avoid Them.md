# 100 Java Mistakes and How to Avoid Them

------------------------------------------------------------------------------------------------------------------

## Table Of Contents

<!-- TOC -->

* [100 Java Mistakes and How to Avoid Them](#100-java-mistakes-and-how-to-avoid-them)
    * [Table Of Contents](#table-of-contents)
    * [Managing code quality](#managing-code-quality)
        * [Code review and pair programming](#code-review-and-pair-programming)
        * [Code style](#code-style)
        * [Static analysis](#static-analysis)
            * [Static analysis tools for Java](#static-analysis-tools-for-java)
            * [Using static analyzers](#using-static-analyzers)
            * [Limitations of static analysis](#limitations-of-static-analysis)
            * [Suppressing unwanted warnings](#suppressing-unwanted-warnings)
        * [Automated testing](#automated-testing)
        * [Mutation coverage](#mutation-coverage)
        * [Dynamic analysis](#dynamic-analysis)
        * [Code assertions](#code-assertions)
    * [Expressions](#expressions)
        * [Mistake 1: Incorrect assumptions about numeric operator precedence](#mistake-1-incorrect-assumptions-about-numeric-operator-precedence)
            * [Binary shift](#binary-shift)
            * [Bitwise operators](#bitwise-operators)
        * [Mistake 2: Missing parentheses in conditions](#mistake-2-missing-parentheses-in-conditions)
            * [`&&` and `||` precedence](#-and--precedence)
            * [Conditional operator and addition](#conditional-operator-and-addition)
            * [The conditional operator and `null` check](#the-conditional-operator-and-null-check)
        * [Mistake 3: Accidental concatenation instead of addition](#mistake-3-accidental-concatenation-instead-of-addition)
        * [Mistake 4: Multiline string literals](#mistake-4-multiline-string-literals)
        * [Mistake 5: Unary plus](#mistake-5-unary-plus)
        * [Mistake 6: Implicit type conversion in conditional expressions](#mistake-6-implicit-type-conversion-in-conditional-expressions)
            * [Boxed numbers in conditional expressions](#boxed-numbers-in-conditional-expressions)
            * [Nested conditional expressions](#nested-conditional-expressions)
        * [Mistake 7: Using non-short-circuit logic operators](#mistake-7-using-non-short-circuit-logic-operators)
        * [Mistake 8: Confusing `&&` and `||`](#mistake-8-confusing--and-)
        * [Mistake 9: Incorrectly using variable arity calls](#mistake-9-incorrectly-using-variable-arity-calls)
            * [Ambiguous variable arity calls](#ambiguous-variable-arity-calls)
            * [Mixing array and collection](#mixing-array-and-collection)
            * [Using primitive array in variable arity call](#using-primitive-array-in-variable-arity-call)
        * [Mistake 10: Conditional operators and variable arity calls](#mistake-10-conditional-operators-and-variable-arity-calls)
        * [Mistake 11: Ignoring an important return value](#mistake-11-ignoring-an-important-return-value)
        * [Mistake 12: Not using a newly created object](#mistake-12-not-using-a-newly-created-object)
        * [Mistake 13: Binding a method reference to the wrong method](#mistake-13-binding-a-method-reference-to-the-wrong-method)
        * [Mistake 14: Using the wrong method in a method reference](#mistake-14-using-the-wrong-method-in-a-method-reference)
    * [Program structure](#program-structure)
        * [Mistake 15: A malformed `if`–`else` chain](#mistake-15-a-malformed-ifelse-chain)
        * [Mistake 16: A condition dominated by a previous condition](#mistake-16-a-condition-dominated-by-a-previous-condition)
        * [Mistake 17: Accidental pass through in a switch statement](#mistake-17-accidental-pass-through-in-a-switch-statement)
        * [Mistake 18: Malformed classic for loop](#mistake-18-malformed-classic-for-loop)
        * [Mistake 19: Not using the loop variable](#mistake-19-not-using-the-loop-variable)
        * [Mistake 20: Wrong loop direction](#mistake-20-wrong-loop-direction)
        * [Mistake 21: Loop overflow](#mistake-21-loop-overflow)
        * [Mistake 22: Idempotent loop body](#mistake-22-idempotent-loop-body)
        * [Mistake 23: Incorrect initialization order](#mistake-23-incorrect-initialization-order)
            * [Static fields](#static-fields)
            * [Subclass fields](#subclass-fields)
            * [Class initialization order](#class-initialization-order)
            * [Enum initialization loop](#enum-initialization-loop)
        * [Mistake 24: A missing superclass method call](#mistake-24-a-missing-superclass-method-call)
        * [Mistake 25: Accidental `static` field declaration](#mistake-25-accidental-static-field-declaration)
    * [Numbers](#numbers)
        * [Mistake 26: Accidental use of octal literal](#mistake-26-accidental-use-of-octal-literal)
        * [Mistake 27: Numeric overflow](#mistake-27-numeric-overflow)
            * [Overflow in Java](#overflow-in-java)
            * [Assigning the result of int multiplication to a `long` variable](#assigning-the-result-of-int-multiplication-to-a-long-variable)
            * [File size, time, and financial computations](#file-size-time-and-financial-computations)
        * [Mistake 28: Rounding during integer division](#mistake-28-rounding-during-integer-division)
        * [Mistake 29: Absolute value of `Integer.MIN_VALUE`](#mistake-29-absolute-value-of-integermin_value)
        * [Mistake 30: Oddness check and negative numbers](#mistake-30-oddness-check-and-negative-numbers)
        * [Mistake 31: Widening with precision loss](#mistake-31-widening-with-precision-loss)
        * [Mistake 32: Unconditional narrowing](#mistake-32-unconditional-narrowing)
        * [Mistake 33: Negative hexadecimal values](#mistake-33-negative-hexadecimal-values)
        * [Mistake 34: Implicit type conversion in compound assignments](#mistake-34-implicit-type-conversion-in-compound-assignments)
        * [Mistake 35: Division and compound assignment](#mistake-35-division-and-compound-assignment)
        * [Mistake 36: Using the short type](#mistake-36-using-the-short-type)
        * [Mistake 37: Manually writing bit-manipulating algorithms](#mistake-37-manually-writing-bit-manipulating-algorithms)
        * [Mistake 38: Forgetting about negative byte values](#mistake-38-forgetting-about-negative-byte-values)
        * [Mistake 39: Incorrect clamping order](#mistake-39-incorrect-clamping-order)
        * [Mistake 40: Misusing special floating-point numbers](#mistake-40-misusing-special-floating-point-numbers)
            * [Signed zero: `+0.0` and `–0.0`](#signed-zero-00-and-00)
            * [Not a number: `NaN` values](#not-a-number-nan-values)
            * [`Double.MIN_VALUE` is not the minimal value](#doublemin_value-is-not-the-minimal-value)
    * [Common exceptions](#common-exceptions)
        * [Mistake 41: `NullPointerException`](#mistake-41-nullpointerexception)
            * [Avoiding nulls and defensive checks](#avoiding-nulls-and-defensive-checks)
            * [Using Optional instead of `null`](#using-optional-instead-of-null)
            * [Nullity annotations](#nullity-annotations)
        * [Mistake 42: `IndexOutOfBoundsException`](#mistake-42-indexoutofboundsexception)
        * [Mistake 43: `ClassCastException`](#mistake-43-classcastexception)
            * [Explicit cast](#explicit-cast)
            * [Generic types and implicit casts](#generic-types-and-implicit-casts)
            * [Different class loaders](#different-class-loaders)
        * [Mistake 44: `StackOverflowError`](#mistake-44-stackoverflowerror)
            * [Deep but finite recursion](#deep-but-finite-recursion)
            * [Infinite recursion](#infinite-recursion)
    * [Strings](#strings)
        * [Mistake 45: Assuming that `char` value is a character](#mistake-45-assuming-that-char-value-is-a-character)
        * [Mistake 46: Unexpected case conversions](#mistake-46-unexpected-case-conversions)
        * [Mistake 47: Using `String.format` with the default locale](#mistake-47-using-stringformat-with-the-default-locale)
        * [Mistake 48: Mismatched format arguments](#mistake-48-mismatched-format-arguments)
        * [Mistake 49: Using plain strings instead of regular expressions](#mistake-49-using-plain-strings-instead-of-regular-expressions)
        * [Mistake 50: Accidental use of `replaceAll`](#mistake-50-accidental-use-of-replaceall)
        * [Mistake 51: Accidental use of escape sequences](#mistake-51-accidental-use-of-escape-sequences)
        * [Mistake 52: Comparing strings in different case](#mistake-52-comparing-strings-in-different-case)
        * [Mistake 53: Not checking the result of `indexOf` method](#mistake-53-not-checking-the-result-of-indexof-method)
        * [Mistake 54: Mixing arguments of `indexOf`](#mistake-54-mixing-arguments-of-indexof)
    * [Comparing objects](#comparing-objects)
        * [Mistake 55: Use of reference equality instead of the equals method](#mistake-55-use-of-reference-equality-instead-of-the-equals-method)
        * [Mistake 56: Assuming `equals()` compares content](#mistake-56-assuming-equals-compares-content)
        * [Mistake 57: Using `URL.equals()`](#mistake-57-using-urlequals)
        * [Mistake 58: Comparing BigDecimals with different scales](#mistake-58-comparing-bigdecimals-with-different-scales)
        * [Mistake 59: Using `equals()` on unrelated types](#mistake-59-using-equals-on-unrelated-types)
        * [Mistake 60: Malformed `equals()` implementation](#mistake-60-malformed-equals-implementation)
        * [Mistake 61: Wrong hashCode() with array fields](#mistake-61-wrong-hashcode-with-array-fields)
        * [Mistake 62: Mismatch between `equals()` and `hashCode()`](#mistake-62-mismatch-between-equals-and-hashcode)
        * [Mistake 63: Relying on a particular `return` value of `compare()`](#mistake-63-relying-on-a-particular-return-value-of-compare)
        * [Mistake 64: Failing to `return 0` when comparing equal objects](#mistake-64-failing-to-return-0-when-comparing-equal-objects)
        * [Mistake 65: Using subtraction when comparing numbers](#mistake-65-using-subtraction-when-comparing-numbers)
        * [Mistake 66: Ignoring possible `NaN` values in comparison methods](#mistake-66-ignoring-possible-nan-values-in-comparison-methods)
        * [Mistake 67: Failing to represent an object as a sequence of keys in a comparison method](#mistake-67-failing-to-represent-an-object-as-a-sequence-of-keys-in-a-comparison-method)
        * [Mistake 68: Returning random numbers from the comparator](#mistake-68-returning-random-numbers-from-the-comparator)
    * [Collections and maps](#collections-and-maps)
        * [Mistake 69: Searching the object of unrelated type](#mistake-69-searching-the-object-of-unrelated-type)
        * [Mistake 70: Mixing up single object and collection](#mistake-70-mixing-up-single-object-and-collection)
        * [Mistake 71: Searching for null in a null-hostile collection](#mistake-71-searching-for-null-in-a-null-hostile-collection)
        * [Mistake 72: Using null values in maps](#mistake-72-using-null-values-in-maps)
        * [Mistake 73: Trying to modify an unmodifiable `Collection`](#mistake-73-trying-to-modify-an-unmodifiable-collection)
        * [Mistake 74: Using mutable objects as keys](#mistake-74-using-mutable-objects-as-keys)
        * [Mistake 75: Relying on HashMap and HashSet encounter order](#mistake-75-relying-on-hashmap-and-hashset-encounter-order)
        * [Mistake 76: Concurrent modification during the iteration](#mistake-76-concurrent-modification-during-the-iteration)
        * [Mistake 77: Mixing `List.remove()` overloads](#mistake-77-mixing-listremove-overloads)
        * [Mistake 78: Jumping over the next element after `List.remove()`](#mistake-78-jumping-over-the-next-element-after-listremove)
        * [Mistake 79: Reading the collection inside `Collection.removeIf()`](#mistake-79-reading-the-collection-inside-collectionremoveif)
        * [Mistake 80: Concurrent modification in `Map.computeIfAbsent()`](#mistake-80-concurrent-modification-in-mapcomputeifabsent)
        * [Mistake 81: Violating Iterator contracts](#mistake-81-violating-iterator-contracts)
    * [Library methods](#library-methods)
        * [Mistake 82: Passing char to StringBuilder constructor](#mistake-82-passing-char-to-stringbuilder-constructor)
        * [Mistake 83: Producing side effects in a Stream API chain](#mistake-83-producing-side-effects-in-a-stream-api-chain)
        * [Mistake 84: Consuming the stream twice](#mistake-84-consuming-the-stream-twice)
        * [Mistake 85: Using null values in a stream where it’s not allowed](#mistake-85-using-null-values-in-a-stream-where-its-not-allowed)
        * [Mistake 86: Violating the contract of Stream API operations](#mistake-86-violating-the-contract-of-stream-api-operations)
        * [Mistake 87: Using `getClass()` instead of instanceof](#mistake-87-using-getclass-instead-of-instanceof)
        * [Mistake 88: Using `getClass()` on enums, annotations, or classes](#mistake-88-using-getclass-on-enums-annotations-or-classes)
        * [Mistake 89: Incorrect conversion of string to boolean](#mistake-89-incorrect-conversion-of-string-to-boolean)
        * [Mistake 90: Incorrect format specifiers in date formatting](#mistake-90-incorrect-format-specifiers-in-date-formatting)
        * [Mistake 91: Accidental invalidation of weak or soft references](#mistake-91-accidental-invalidation-of-weak-or-soft-references)
        * [Mistake 92: Assuming the world is stable](#mistake-92-assuming-the-world-is-stable)
        * [Mistake 93: Non-atomic access to concurrently updated data structures](#mistake-93-non-atomic-access-to-concurrently-updated-data-structures)
    * [Unit testing](#unit-testing)
        * [Mistake 94: Side effect in assert statement](#mistake-94-side-effect-in-assert-statement)
        * [Mistake 95: Malformed assertion method calls](#mistake-95-malformed-assertion-method-calls)
        * [Mistake 96: Malformed exception test](#mistake-96-malformed-exception-test)
        * [Mistake 97: Premature exit from test method](#mistake-97-premature-exit-from-test-method)
        * [Mistake 98: Ignoring the AssertionError in unit tests](#mistake-98-ignoring-the-assertionerror-in-unit-tests)
        * [Mistake 99: Using `assertNotEquals()` to check the equality contract](#mistake-99-using-assertnotequals-to-check-the-equality-contract)
        * [Mistake 100: Malformed test methods](#mistake-100-malformed-test-methods)
    * [Static analysis annotations](#static-analysis-annotations)
    * [Extending static analysis tools](#extending-static-analysis-tools)

<!-- TOC -->
------------------------------------------------------------------------------------------------------------------

## Managing code quality

### Code review and pair programming

### Code style

### Static analysis

#### Static analysis tools for Java

#### Using static analyzers

#### Limitations of static analysis

#### Suppressing unwanted warnings

### Automated testing

### Mutation coverage

### Dynamic analysis

### Code assertions

------------------------------------------------------------------------------------------------------------------

## Expressions

### Mistake 1: Incorrect assumptions about numeric operator precedence

#### Binary shift

#### Bitwise operators

### Mistake 2: Missing parentheses in conditions

#### `&&` and `||` precedence

#### Conditional operator and addition

#### The conditional operator and `null` check

### Mistake 3: Accidental concatenation instead of addition

### Mistake 4: Multiline string literals

### Mistake 5: Unary plus

### Mistake 6: Implicit type conversion in conditional expressions

#### Boxed numbers in conditional expressions

#### Nested conditional expressions

### Mistake 7: Using non-short-circuit logic operators

### Mistake 8: Confusing `&&` and `||`

### Mistake 9: Incorrectly using variable arity calls

#### Ambiguous variable arity calls

#### Mixing array and collection

#### Using primitive array in variable arity call

### Mistake 10: Conditional operators and variable arity calls

### Mistake 11: Ignoring an important return value

### Mistake 12: Not using a newly created object

### Mistake 13: Binding a method reference to the wrong method

### Mistake 14: Using the wrong method in a method reference

------------------------------------------------------------------------------------------------------------------

## Program structure

### Mistake 15: A malformed `if`–`else` chain

### Mistake 16: A condition dominated by a previous condition

### Mistake 17: Accidental pass through in a switch statement

### Mistake 18: Malformed classic for loop

### Mistake 19: Not using the loop variable

### Mistake 20: Wrong loop direction

### Mistake 21: Loop overflow

### Mistake 22: Idempotent loop body

### Mistake 23: Incorrect initialization order

#### Static fields

#### Subclass fields

#### Class initialization order

#### Enum initialization loop

### Mistake 24: A missing superclass method call

### Mistake 25: Accidental `static` field declaration

------------------------------------------------------------------------------------------------------------------

## Numbers

### Mistake 26: Accidental use of octal literal

### Mistake 27: Numeric overflow

#### Overflow in Java

#### Assigning the result of int multiplication to a `long` variable

#### File size, time, and financial computations

### Mistake 28: Rounding during integer division

### Mistake 29: Absolute value of `Integer.MIN_VALUE`

### Mistake 30: Oddness check and negative numbers

### Mistake 31: Widening with precision loss

### Mistake 32: Unconditional narrowing

### Mistake 33: Negative hexadecimal values

### Mistake 34: Implicit type conversion in compound assignments

### Mistake 35: Division and compound assignment

### Mistake 36: Using the short type

### Mistake 37: Manually writing bit-manipulating algorithms

### Mistake 38: Forgetting about negative byte values

### Mistake 39: Incorrect clamping order

### Mistake 40: Misusing special floating-point numbers

#### Signed zero: `+0.0` and `–0.0`

#### Not a number: `NaN` values

#### `Double.MIN_VALUE` is not the minimal value

------------------------------------------------------------------------------------------------------------------

## Common exceptions

### Mistake 41: `NullPointerException`

#### Avoiding nulls and defensive checks

#### Using Optional instead of `null`

#### Nullity annotations

### Mistake 42: `IndexOutOfBoundsException`

### Mistake 43: `ClassCastException`

#### Explicit cast

#### Generic types and implicit casts

#### Different class loaders

### Mistake 44: `StackOverflowError`

#### Deep but finite recursion

#### Infinite recursion

------------------------------------------------------------------------------------------------------------------

## Strings

### Mistake 45: Assuming that `char` value is a character

### Mistake 46: Unexpected case conversions

### Mistake 47: Using `String.format` with the default locale

### Mistake 48: Mismatched format arguments

### Mistake 49: Using plain strings instead of regular expressions

### Mistake 50: Accidental use of `replaceAll`

### Mistake 51: Accidental use of escape sequences

### Mistake 52: Comparing strings in different case

### Mistake 53: Not checking the result of `indexOf` method

### Mistake 54: Mixing arguments of `indexOf`

------------------------------------------------------------------------------------------------------------------

## Comparing objects

### Mistake 55: Use of reference equality instead of the equals method

### Mistake 56: Assuming `equals()` compares content

### Mistake 57: Using `URL.equals()`

### Mistake 58: Comparing BigDecimals with different scales

### Mistake 59: Using `equals()` on unrelated types

### Mistake 60: Malformed `equals()` implementation

### Mistake 61: Wrong hashCode() with array fields

### Mistake 62: Mismatch between `equals()` and `hashCode()`

### Mistake 63: Relying on a particular `return` value of `compare()`

### Mistake 64: Failing to `return 0` when comparing equal objects

### Mistake 65: Using subtraction when comparing numbers

### Mistake 66: Ignoring possible `NaN` values in comparison methods

### Mistake 67: Failing to represent an object as a sequence of keys in a comparison method

### Mistake 68: Returning random numbers from the comparator

------------------------------------------------------------------------------------------------------------------

## Collections and maps

### Mistake 69: Searching the object of unrelated type

### Mistake 70: Mixing up single object and collection

### Mistake 71: Searching for null in a null-hostile collection

### Mistake 72: Using null values in maps

### Mistake 73: Trying to modify an unmodifiable `Collection`

### Mistake 74: Using mutable objects as keys

### Mistake 75: Relying on HashMap and HashSet encounter order

### Mistake 76: Concurrent modification during the iteration

### Mistake 77: Mixing `List.remove()` overloads

### Mistake 78: Jumping over the next element after `List.remove()`

### Mistake 79: Reading the collection inside `Collection.removeIf()`

### Mistake 80: Concurrent modification in `Map.computeIfAbsent()`

### Mistake 81: Violating Iterator contracts

------------------------------------------------------------------------------------------------------------------

## Library methods

### Mistake 82: Passing char to StringBuilder constructor

### Mistake 83: Producing side effects in a Stream API chain

### Mistake 84: Consuming the stream twice

### Mistake 85: Using null values in a stream where it’s not allowed

### Mistake 86: Violating the contract of Stream API operations

### Mistake 87: Using `getClass()` instead of instanceof

### Mistake 88: Using `getClass()` on enums, annotations, or classes

### Mistake 89: Incorrect conversion of string to boolean

### Mistake 90: Incorrect format specifiers in date formatting

### Mistake 91: Accidental invalidation of weak or soft references

### Mistake 92: Assuming the world is stable

### Mistake 93: Non-atomic access to concurrently updated data structures

------------------------------------------------------------------------------------------------------------------

## Unit testing

### Mistake 94: Side effect in assert statement

### Mistake 95: Malformed assertion method calls

### Mistake 96: Malformed exception test

### Mistake 97: Premature exit from test method

### Mistake 98: Ignoring the AssertionError in unit tests

### Mistake 99: Using `assertNotEquals()` to check the equality contract

### Mistake 100: Malformed test methods

------------------------------------------------------------------------------------------------------------------

## Static analysis annotations

------------------------------------------------------------------------------------------------------------------

## Extending static analysis tools