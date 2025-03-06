# Object-Oriented Programming (OOP)

------------------------------------------------------------------------------------------------------------------

## Table of Contents

<!-- TOC -->

* [Object-Oriented Programming (OOP)](#object-oriented-programming-oop)
    * [Table of Contents](#table-of-contents)
    * [Intro](#intro)
        * [Great Software Begins Here: well-designed apps rock](#great-software-begins-here-well-designed-apps-rock)
            * [Rock and roll is forever!](#rock-and-roll-is-forever)
            * [Rick’s shiny new application](#ricks-shiny-new-application)
            * [What’s the FIRST thing you’d change?](#whats-the-first-thing-youd-change)
            * [Great Software is...](#great-software-is)
            * [Great software in 3 easy steps](#great-software-in-3-easy-steps)
            * [Focus on functionality first](#focus-on-functionality-first)
            * [Test drive](#test-drive)
            * [Looking for problems](#looking-for-problems)
            * [Analysis](#analysis)
            * [Apply basic OO principles](#apply-basic-oo-principles)
            * [Design once, design twice](#design-once-design-twice)
            * [How easy is it to change your applications?](#how-easy-is-it-to-change-your-applications)
            * [Encapsulate what varies](#encapsulate-what-varies)
            * [Delegation](#delegation)
            * [Great software at last (for now)](#great-software-at-last-for-now)
            * [OOA&D is about writing great software](#ooad-is-about-writing-great-software)
            * [Bullet Points](#bullet-points)
        * [Give Them What They Want: gathering requirements](#give-them-what-they-want-gathering-requirements)
            * [You’ve got a new programming gig](#youve-got-a-new-programming-gig)
            * [Test drive](#test-drive-1)
            * [Incorrect usage (sort of)](#incorrect-usage-sort-of)
            * [What is a requirement?](#what-is-a-requirement)
            * [Creating a requirements list](#creating-a-requirements-list)
            * [Plan for things going wrong](#plan-for-things-going-wrong)
            * [Alternate paths handle system problems](#alternate-paths-handle-system-problems)
            * [Introducing use cases](#introducing-use-cases)
            * [One use case, three parts](#one-use-case-three-parts)
            * [Check your requirements against your use cases](#check-your-requirements-against-your-use-cases)
            * [Your system must work in the real world](#your-system-must-work-in-the-real-world)
            * [Getting to know the Happy Path](#getting-to-know-the-happy-path)
            * [OOA&D Toolbox](#ooad-toolbox)
        * [I Love You, You’re Perfect... Now Change: requirements change](#i-love-you-youre-perfect-now-change-requirements-change)
            * [You’re a hero!](#youre-a-hero)
            * [You’re a goat!](#youre-a-goat)
            * [The one constant in software analysis & design](#the-one-constant-in-software-analysis--design)
            * [Original path? Alternate path? Who can tell?](#original-path-alternate-path-who-can-tell)
            * [Use cases have to make sense to you](#use-cases-have-to-make-sense-to-you)
            * [Start to finish: a single scenario](#start-to-finish-a-single-scenario)
            * [Confessions of an Alternate Path](#confessions-of-an-alternate-path)
            * [Finishing up the requirements list](#finishing-up-the-requirements-list)
            * [Duplicate code is a bad idea](#duplicate-code-is-a-bad-idea)
            * [Final test drive](#final-test-drive)
            * [Write your own design principle](#write-your-own-design-principle)
            * [OOA&D Toolbox](#ooad-toolbox-1)
        * [Taking Your Software Into the Real World: analysis](#taking-your-software-into-the-real-world-analysis)
            * [One dog, two dog, three dog, four...](#one-dog-two-dog-three-dog-four)
            * [Your software has a context](#your-software-has-a-context)
            * [Identify the problem](#identify-the-problem)
            * [Plan a solution](#plan-a-solution)
            * [A tale of two coders](#a-tale-of-two-coders)
            * [Delegation Detour](#delegation-detour)
            * [The power of loosely coupled applications](#the-power-of-loosely-coupled-applications)
            * [Pay attention to the nouns in your use case](#pay-attention-to-the-nouns-in-your-use-case)
            * [From good analysis to good classes...](#from-good-analysis-to-good-classes)
            * [Class diagrams dissected](#class-diagrams-dissected)
            * [Class diagrams aren’t everything](#class-diagrams-arent-everything)
            * [Bullet Points](#bullet-points-1)
    * [Part 1: Nothing Ever Stays the Same: good design](#part-1-nothing-ever-stays-the-same-good-design)
        * [Rick’s Guitars is expanding](#ricks-guitars-is-expanding)
        * [Abstract classes](#abstract-classes)
        * [Class diagrams dissected (again)](#class-diagrams-dissected-again)
        * [UML Cheat Sheet](#uml-cheat-sheet)
        * [Design problem tipoffs](#design-problem-tipoffs)
        * [3 steps to great software (revisited)](#3-steps-to-great-software-revisited)
    * [Part 2: Give Your Software a 30-minute Workout: flexible software](#part-2-give-your-software-a-30-minute-workout-flexible-software)
        * [Back to Rick’s search tool](#back-to-ricks-search-tool)
        * [A closer look at the search() method](#a-closer-look-at-the-search-method)
        * [The benefits of analysis](#the-benefits-of-analysis)
        * [Classes are about behavior](#classes-are-about-behavior)
        * [Death of a design (decision)](#death-of-a-design-decision)
        * [Turn bad design decisions into good ones](#turn-bad-design-decisions-into-good-ones)
        * [“Double encapsulation” in Rick’s software](#double-encapsulation-in-ricks-software)
        * [Never be afraid to make mistakes](#never-be-afraid-to-make-mistakes)
        * [Rick’s flexible application](#ricks-flexible-application)
        * [Test driving well-designed software](#test-driving-well-designed-software)
        * [How easy is it to change Rick’s software?](#how-easy-is-it-to-change-ricks-software)
        * [The Great Ease-of-Change Challenge](#the-great-ease-of-change-challenge)
        * [A cohesive class does one thing really well](#a-cohesive-class-does-one-thing-really-well)
        * [The design/cohesion lifecycle](#the-designcohesion-lifecycle)
        * [Great software is “good enough”](#great-software-is-good-enough)
        * [OOA&D Toolbox](#ooad-toolbox-2)
        * [“My Name is Art Vandelay”: solving really big problems](#my-name-is-art-vandelay-solving-really-big-problems)
            * [Solving big problems](#solving-big-problems)
            * [It’s all in how you look at the big problem](#its-all-in-how-you-look-at-the-big-problem)
            * [Requirements and use cases are a good place to start...](#requirements-and-use-cases-are-a-good-place-to-start)
            * [Commonality and variability](#commonality-and-variability)
            * [Figure out the features](#figure-out-the-features)
            * [The difference between features and requirements](#the-difference-between-features-and-requirements)
            * [Use cases don’t always help you see the big picture](#use-cases-dont-always-help-you-see-the-big-picture)
            * [Use case diagrams](#use-case-diagrams)
            * [The Little Actor](#the-little-actor)
            * [Actors are people, too (well, not always)](#actors-are-people-too-well-not-always)
            * [Let’s do a little domain analysis](#lets-do-a-little-domain-analysis)
            * [Divide and conquer](#divide-and-conquer)
            * [Don’t forget who the customer really is](#dont-forget-who-the-customer-really-is)
            * [What’s a design pattern?](#whats-a-design-pattern)
            * [The power of OOA&D (and a little common sense)](#the-power-of-ooad-and-a-little-common-sense)
            * [OOA&D Toolbox](#ooad-toolbox-3)
        * [Bringing Order to Chaos: architecture](#bringing-order-to-chaos-architecture)
            * [Feeling a little overwhelmed?](#feeling-a-little-overwhelmed)
            * [We need an architecture](#we-need-an-architecture)
            * [Start with functionality](#start-with-functionality)
            * [What’s architecturally significant?](#whats-architecturally-significant)
            * [The three Qs of architecture](#the-three-qs-of-architecture)
            * [Reducing risk](#reducing-risk)
            * [Scenarios help reduce risk](#scenarios-help-reduce-risk)
            * [Focus on one feature at a time](#focus-on-one-feature-at-a-time)
            * [Architecture is your design structure](#architecture-is-your-design-structure)
            * [Commonality revisited](#commonality-revisited)
            * [Commonality Analysis: the path to flexible software](#commonality-analysis-the-path-to-flexible-software)
            * [What does it mean? Ask the customer](#what-does-it-mean-ask-the-customer)
            * [Reducing risk helps you write great software](#reducing-risk-helps-you-write-great-software)
            * [Bullet Points](#bullet-points-2)
        * [Originality is Overrated: design principles](#originality-is-overrated-design-principles)
            * [Design principle roundup](#design-principle-roundup)
            * [The Open-Closed Principle (OCP)](#the-open-closed-principle-ocp)
            * [The OCP, step-by-step](#the-ocp-step-by-step)
            * [The Don’t Repeat Yourself Principle (DRY)](#the-dont-repeat-yourself-principle-dry)
            * [DRY is about one requirement in one place](#dry-is-about-one-requirement-in-one-place)
            * [The Single Responsibility Principle (SRP)](#the-single-responsibility-principle-srp)
            * [Spotting multiple responsibilities](#spotting-multiple-responsibilities)
            * [Going from multiple responsibilities to a single responsibility](#going-from-multiple-responsibilities-to-a-single-responsibility)
            * [The Liskov Substitution Principle (LSP)](#the-liskov-substitution-principle-lsp)
            * [Misusing subclassing: a case study in misuing inheritance](#misusing-subclassing-a-case-study-in-misuing-inheritance)
            * [LSP reveals hidden problems with your inheritance structure](#lsp-reveals-hidden-problems-with-your-inheritance-structure)
            * [Subtypes must be substitutable for their base types](#subtypes-must-be-substitutable-for-their-base-types)
            * [Violating the LSP makes for confusing code](#violating-the-lsp-makes-for-confusing-code)
            * [Delegate functionality to another class](#delegate-functionality-to-another-class)
            * [Use composition to assemble behaviors from other classes](#use-composition-to-assemble-behaviors-from-other-classes)
            * [Aggregation: composition, without the abrupt ending](#aggregation-composition-without-the-abrupt-ending)
            * [Aggregation versus composition](#aggregation-versus-composition)
            * [Inheritance is just one option](#inheritance-is-just-one-option)
            * [Bullet Points](#bullet-points-3)
            * [OOA&D Toolbox](#ooad-toolbox-4)
        * [The Software is Still for the Customer: iteration and testing](#the-software-is-still-for-the-customer-iteration-and-testing)
            * [Your toolbox is filling up](#your-toolbox-is-filling-up)
            * [You write great software iteratively](#you-write-great-software-iteratively)
            * [Iterating deeper: two basic choices](#iterating-deeper-two-basic-choices)
            * [Feature driven development](#feature-driven-development)
            * [Use case driven development](#use-case-driven-development)
            * [Two approaches to development](#two-approaches-to-development)
            * [Analysis of a feature](#analysis-of-a-feature)
            * [Writing test scenarios](#writing-test-scenarios)
            * [Test driven development](#test-driven-development)
            * [Commonality Analysis (redux)](#commonality-analysis-redux)
            * [Emphasizing commonality](#emphasizing-commonality)
            * [Emphasizing encapsulation](#emphasizing-encapsulation)
            * [Match your tests to your design](#match-your-tests-to-your-design)
            * [Test cases dissected...](#test-cases-dissected)
            * [Prove yourself to the customer](#prove-yourself-to-the-customer)
            * [We’ve been programming by contract](#weve-been-programming-by-contract)
            * [Programming by contract is about trust](#programming-by-contract-is-about-trust)
            * [Defensive programming](#defensive-programming)
            * [Break your apps into smaller chunks of functionality](#break-your-apps-into-smaller-chunks-of-functionality)
            * [Bullet Points](#bullet-points-4)
            * [OOA&D Toolbox](#ooad-toolbox-5)
        * [Putting It All Together: the ooa&d lifecycle](#putting-it-all-together-the-ooad-lifecycle)
            * [Developing software, OOA&D style](#developing-software-ooad-style)
            * [The Objectville Subway problem](#the-objectville-subway-problem)
            * [Objectville Subway Map](#objectville-subway-map)
            * [Feature lists](#feature-lists)
            * [Use cases reflect usage, features reflect functionality](#use-cases-reflect-usage-features-reflect-functionality)
            * [Now start to iterate](#now-start-to-iterate)
            * [A closer look at representing a subway](#a-closer-look-at-representing-a-subway)
            * [To use a Line, or not to use a Line](#to-use-a-line-or-not-to-use-a-line)
            * [Points of interest on the Objectville Subway (class)](#points-of-interest-on-the-objectville-subway-class)
            * [Protecting your classes](#protecting-your-classes)
            * [Break time](#break-time)
            * [Back to the requirements phase](#back-to-the-requirements-phase)
            * [Focus on code, then focus on customers](#focus-on-code-then-focus-on-customers)
            * [Iteration makes problems easier](#iteration-makes-problems-easier)
            * [What does a route look like?](#what-does-a-route-look-like)
            * [Check out Objectville for yourself !](#check-out-objectville-for-yourself-)
            * [Iteration #3, anyone?](#iteration-3-anyone)
            * [The journey’s not over...](#the-journeys-not-over)
    * [Leftovers](#leftovers)
        * [IS-A and HAS-A](#is-a-and-has-a)
        * [Use case formats](#use-case-formats)
        * [Anti-patterns](#anti-patterns)
        * [CRC cards](#crc-cards)
        * [Metrics](#metrics)
        * [Sequence diagrams](#sequence-diagrams)
        * [State diagrams](#state-diagrams)
        * [Unit testing](#unit-testing)
        * [Coding standards and readable code](#coding-standards-and-readable-code)
        * [Refactoring](#refactoring)
    * [Welcome to objectville](#welcome-to-objectville)
        * [UML and class diagrams](#uml-and-class-diagrams)
        * [Inheritance](#inheritance)
        * [Polymorphism](#polymorphism)
        * [Encapsulation](#encapsulation)
        * [Bullet Points](#bullet-points-5)

<!-- TOC -->

------------------------------------------------------------------------------------------------------------------

## Great Software Begins Here: well-designed apps rock

### Rock and roll is forever!

### Rick’s shiny new application

### What’s the FIRST thing you’d change?

### Great Software is...

### Great software in 3 easy steps

### Focus on functionality first

### Test drive

### Looking for problems

### Analysis

### Apply basic OO principles

### Design once, design twice

### How easy is it to change your applications?

### Encapsulate what varies

### Delegation

### Great software at last (for now)

### OOA&D is about writing great software

### Bullet Points

------------------------------------------------------------------------------------------------------------------

## Give Them What They Want: gathering requirements

### You’ve got a new programming gig

### Test drive

### Incorrect usage (sort of)

### What is a requirement?

### Creating a requirements list

### Plan for things going wrong

### Alternate paths handle system problems

### Introducing use cases

### One use case, three parts

### Check your requirements against your use cases

### Your system must work in the real world

### Getting to know the Happy Path

### OOA&D Toolbox

------------------------------------------------------------------------------------------------------------------

## I Love You, You’re Perfect... Now Change: requirements change

### You’re a hero!

### You’re a goat!

### The one constant in software analysis & design

### Original path? Alternate path? Who can tell?

### Use cases have to make sense to you

### Start to finish: a single scenario

### Confessions of an Alternate Path

### Finishing up the requirements list

### Duplicate code is a bad idea

### Final test drive

### Write your own design principle

### OOA&D Toolbox

------------------------------------------------------------------------------------------------------------------

## Taking Your Software Into the Real World: analysis

### One dog, two dog, three dog, four...

### Your software has a context

### Identify the problem

### Plan a solution

### A tale of two coders

### Delegation Detour

### The power of loosely coupled applications

### Pay attention to the nouns in your use case

### From good analysis to good classes...

### Class diagrams dissected

### Class diagrams aren’t everything

### Bullet Points

------------------------------------------------------------------------------------------------------------------

## Part 1: Nothing Ever Stays the Same: good design

### Rick’s Guitars is expanding

### Abstract classes

### Class diagrams dissected (again)

### UML Cheat Sheet

### Design problem tipoffs

### 3 steps to great software (revisited)

------------------------------------------------------------------------------------------------------------------

## Part 2: Give Your Software a 30-minute Workout: flexible software

### Back to Rick’s search tool

### A closer look at the search() method

### The benefits of analysis

### Classes are about behavior

### Death of a design (decision)

### Turn bad design decisions into good ones

### “Double encapsulation” in Rick’s software

### Never be afraid to make mistakes

### Rick’s flexible application

### Test driving well-designed software

### How easy is it to change Rick’s software?

### The Great Ease-of-Change Challenge

### A cohesive class does one thing really well

### The design/cohesion lifecycle

### Great software is “good enough”

### OOA&D Toolbox

------------------------------------------------------------------------------------------------------------------

## “My Name is Art Vandelay”: solving really big problems

### Solving big problems

### It’s all in how you look at the big problem

### Requirements and use cases are a good place to start...

### Commonality and variability

### Figure out the features

### The difference between features and requirements

### Use cases don’t always help you see the big picture

### Use case diagrams

### The Little Actor

### Actors are people, too (well, not always)

### Let’s do a little domain analysis

### Divide and conquer

### Don’t forget who the customer really is

### What’s a design pattern?

### The power of OOA&D (and a little common sense)

### OOA&D Toolbox

------------------------------------------------------------------------------------------------------------------

## Bringing Order to Chaos: architecture

### Feeling a little overwhelmed?

### We need an architecture

### Start with functionality

### What’s architecturally significant?

### The three Qs of architecture

### Reducing risk

### Scenarios help reduce risk

### Focus on one feature at a time

### Architecture is your design structure

### Commonality revisited

### Commonality Analysis: the path to flexible software

### What does it mean? Ask the customer

### Reducing risk helps you write great software

### Bullet Points

------------------------------------------------------------------------------------------------------------------

## Originality is Overrated: design principles

### Design principle roundup

### The Open-Closed Principle (OCP)

### The OCP, step-by-step

### The Don’t Repeat Yourself Principle (DRY)

### DRY is about one requirement in one place

### The Single Responsibility Principle (SRP)

### Spotting multiple responsibilities

### Going from multiple responsibilities to a single responsibility

### The Liskov Substitution Principle (LSP)

### Misusing subclassing: a case study in misuing inheritance

### LSP reveals hidden problems with your inheritance structure

### Subtypes must be substitutable for their base types

### Violating the LSP makes for confusing code

### Delegate functionality to another class

### Use composition to assemble behaviors from other classes

### Aggregation: composition, without the abrupt ending

### Aggregation versus composition

### Inheritance is just one option

### Bullet Points

### OOA&D Toolbox

------------------------------------------------------------------------------------------------------------------

## The Software is Still for the Customer: iteration and testing

### Your toolbox is filling up

### You write great software iteratively

### Iterating deeper: two basic choices

### Feature driven development

### Use case driven development

### Two approaches to development

### Analysis of a feature

### Writing test scenarios

### Test driven development

### Commonality Analysis (redux)

### Emphasizing commonality

### Emphasizing encapsulation

### Match your tests to your design

### Test cases dissected...

### Prove yourself to the customer

### We’ve been programming by contract

### Programming by contract is about trust

### Defensive programming

### Break your apps into smaller chunks of functionality

### Bullet Points

### OOA&D Toolbox

------------------------------------------------------------------------------------------------------------------

## Putting It All Together: the ooa&d lifecycle

### Developing software, OOA&D style

### The Objectville Subway problem

### Objectville Subway Map

### Feature lists

### Use cases reflect usage, features reflect functionality

### Now start to iterate

### A closer look at representing a subway

### To use a Line, or not to use a Line

### Points of interest on the Objectville Subway (class)

### Protecting your classes

### Break time

### Back to the requirements phase

### Focus on code, then focus on customers

### Iteration makes problems easier

### What does a route look like?

### Check out Objectville for yourself !

### Iteration #3, anyone?

### The journey’s not over...

------------------------------------------------------------------------------------------------------------------

## Leftovers

### IS-A and HAS-A

### Use case formats

### Anti-patterns

### CRC cards

### Metrics

### Sequence diagrams

### State diagrams

### Unit testing

### Coding standards and readable code

### Refactoring

------------------------------------------------------------------------------------------------------------------

## Welcome to objectville

### UML and class diagrams

### Inheritance

### Polymorphism

### Encapsulation

### Bullet Points