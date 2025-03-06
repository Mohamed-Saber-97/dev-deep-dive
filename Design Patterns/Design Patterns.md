# Design Patterns

------------------------------------------------------------------------------------------------------------------

## Table of Contents

<!-- TOC -->

* [Design Patterns](#design-patterns)
    * [Table of Contents](#table-of-contents)
    * [Welcome to Design Patterns: intro to Design Patterns](#welcome-to-design-patterns-intro-to-design-patterns)
        * [It started with a simple SimUDuck app](#it-started-with-a-simple-simuduck-app)
        * [But now we need the ducks to FLY](#but-now-we-need-the-ducks-to-fly)
        * [But something went horribly wrong…](#but-something-went-horribly-wrong)
        * [Joe thinks about inheritance…](#joe-thinks-about-inheritance)
        * [How about an interface?](#how-about-an-interface)
        * [What would you do if you were Joe?](#what-would-you-do-if-you-were-joe)
        * [The one constant in software development](#the-one-constant-in-software-development)
        * [Zeroing in on the problem…](#zeroing-in-on-the-problem)
        * [Separating what changes from what stays the same](#separating-what-changes-from-what-stays-the-same)
        * [Designing the Duck Behaviors](#designing-the-duck-behaviors)
        * [Implementing the Duck Behaviors](#implementing-the-duck-behaviors)
        * [Integrating the Duck Behavior](#integrating-the-duck-behavior)
        * [Testing the Duck code](#testing-the-duck-code)
        * [Setting behavior dynamically](#setting-behavior-dynamically)
        * [The Big Picture on encapsulated behaviors](#the-big-picture-on-encapsulated-behaviors)
        * [HAS-A can be better than IS-A](#has-a-can-be-better-than-is-a)
        * [Speaking of Design Patterns…](#speaking-of-design-patterns)
        * [Overheard at the local diner…](#overheard-at-the-local-diner)
        * [Overheard in the next cubicle…](#overheard-in-the-next-cubicle)
        * [The power of a shared pattern vocabulary](#the-power-of-a-shared-pattern-vocabulary)
        * [How do I use Design Patterns?](#how-do-i-use-design-patterns)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox)
    * [Keeping your Objects in the Know: the Observer Pattern](#keeping-your-objects-in-the-know-the-observer-pattern)
        * [The Weather Monitoring application overview](#the-weather-monitoring-application-overview)
        * [Meet the Observer Pattern](#meet-the-observer-pattern)
        * [Publishers + Subscribers = Observer Pattern](#publishers--subscribers--observer-pattern)
        * [The Observer Pattern defined](#the-observer-pattern-defined)
        * [The Power of Loose Coupling](#the-power-of-loose-coupling)
        * [Designing the Weather Station](#designing-the-weather-station)
        * [Implementing the Weather Station](#implementing-the-weather-station)
        * [Power up the Weather Station](#power-up-the-weather-station)
        * [Looking for the Observer Pattern in the Wild](#looking-for-the-observer-pattern-in-the-wild)
        * [Coding the life-changing application](#coding-the-life-changing-application)
        * [Meanwhile, back at Weather-O-Rama](#meanwhile-back-at-weather-o-rama)
        * [Test Drive the new code](#test-drive-the-new-code)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-1)
        * [Design Principle Challenge](#design-principle-challenge)
    * [Decorating Objects: the Decorator Pattern](#decorating-objects-the-decorator-pattern)
        * [Welcome to Starbuzz Coffee](#welcome-to-starbuzz-coffee)
        * [The Open-Closed Principle](#the-open-closed-principle)
        * [Meet the Decorator Pattern](#meet-the-decorator-pattern)
        * [Constructing a drink order with Decorators](#constructing-a-drink-order-with-decorators)
        * [The Decorator Pattern defined](#the-decorator-pattern-defined)
        * [Decorating our Beverages](#decorating-our-beverages)
        * [Writing the Starbuzz code](#writing-the-starbuzz-code)
        * [Coding beverages](#coding-beverages)
        * [Coding condiments](#coding-condiments)
        * [Serving some coffees](#serving-some-coffees)
        * [Real-World Decorators: Java I/O](#real-world-decorators-java-io)
        * [Decorating the java.io classes](#decorating-the-javaio-classes)
        * [Writing your own Java I/O Decorator](#writing-your-own-java-io-decorator)
        * [Test out your new Java I/O Decorator](#test-out-your-new-java-io-decorator)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-2)
    * [Baking with OO Goodness: the Factory Pattern](#baking-with-oo-goodness-the-factory-pattern)
        * [Identifying the aspects that vary](#identifying-the-aspects-that-vary)
        * [Encapsulating object creation](#encapsulating-object-creation)
        * [Building a simple pizza factory](#building-a-simple-pizza-factory)
        * [The Simple Factory defined](#the-simple-factory-defined)
        * [A framework for the pizza store](#a-framework-for-the-pizza-store)
        * [Allowing the subclasses to decide](#allowing-the-subclasses-to-decide)
        * [Declaring a factory method](#declaring-a-factory-method)
        * [It’s finally time to meet the Factory Method Pattern](#its-finally-time-to-meet-the-factory-method-pattern)
        * [View Creators and Products in Parallel](#view-creators-and-products-in-parallel)
        * [Factory Method Pattern defined](#factory-method-pattern-defined)
        * [Looking at object dependencies](#looking-at-object-dependencies)
        * [The Dependency Inversion Principle](#the-dependency-inversion-principle)
        * [Applying the Principle](#applying-the-principle)
        * [Families of ingredients…](#families-of-ingredients)
        * [Building the ingredient factories](#building-the-ingredient-factories)
        * [Reworking the pizzas…](#reworking-the-pizzas)
        * [Revisiting our pizza stores](#revisiting-our-pizza-stores)
        * [What have we done?](#what-have-we-done)
        * [Abstract Factory Pattern defined](#abstract-factory-pattern-defined)
        * [Factory Method and Abstract Factory compared](#factory-method-and-abstract-factory-compared)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-3)
    * [One-of-a-Kind Objects: the Singleton Pattern](#one-of-a-kind-objects-the-singleton-pattern)
        * [Dissecting the classic Singleton Pattern implementation](#dissecting-the-classic-singleton-pattern-implementation)
        * [The Chocolate Factory](#the-chocolate-factory)
        * [Singleton Pattern defined](#singleton-pattern-defined)
        * [Houston, we have a problem](#houston-we-have-a-problem)
        * [Dealing with multithreading](#dealing-with-multithreading)
        * [Can we improve multithreading?](#can-we-improve-multithreading)
        * [Meanwhile, back at the Chocolate Factory…](#meanwhile-back-at-the-chocolate-factory)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-4)
    * [Encapsulating Invocation: the Command Pattern](#encapsulating-invocation-the-command-pattern)
        * [Home Automation or Bust](#home-automation-or-bust)
        * [Taking a look at the vendor classes](#taking-a-look-at-the-vendor-classes)
        * [A brief introduction to the Command Pattern](#a-brief-introduction-to-the-command-pattern)
        * [From the Diner to the Command Pattern](#from-the-diner-to-the-command-pattern)
        * [Our first command object](#our-first-command-object)
        * [Using the command object](#using-the-command-object)
        * [Assigning Commands to slots](#assigning-commands-to-slots)
        * [Implementing the Remote Control](#implementing-the-remote-control)
        * [Implementing the Commands](#implementing-the-commands)
        * [Putting the Remote Control through its paces](#putting-the-remote-control-through-its-paces)
        * [Time to write that documentation…](#time-to-write-that-documentation)
        * [What are we doing?](#what-are-we-doing)
        * [Time to QA that Undo button!](#time-to-qa-that-undo-button)
        * [Using state to implement Undo](#using-state-to-implement-undo)
        * [Adding Undo to the Ceiling Fan commands](#adding-undo-to-the-ceiling-fan-commands)
        * [Every remote needs a Party Mode!](#every-remote-needs-a-party-mode)
        * [Using a macro command](#using-a-macro-command)
        * [More uses of the Command Pattern: queuing requests](#more-uses-of-the-command-pattern-queuing-requests)
        * [More uses of the Command Pattern: logging requests](#more-uses-of-the-command-pattern-logging-requests)
        * [Command Pattern in the Real World](#command-pattern-in-the-real-world)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-5)
    * [Being Adaptive: the Adapter and Facade Patterns](#being-adaptive-the-adapter-and-facade-patterns)
        * [might be a duck turkey wrapped with a duck adapter…](#might-be-a-duck-turkey-wrapped-with-a-duck-adapter)
        * [Test drive the adapter](#test-drive-the-adapter)
        * [The Adapter Pattern explained](#the-adapter-pattern-explained)
        * [Adapter Pattern defined](#adapter-pattern-defined)
        * [Object and class adapters](#object-and-class-adapters)
        * [Real-world adapters](#real-world-adapters)
        * [Adapting an Enumeration to an Iterator](#adapting-an-enumeration-to-an-iterator)
        * [Home Sweet Home Theater](#home-sweet-home-theater)
        * [Watching a movie (the hard way)](#watching-a-movie-the-hard-way)
        * [Lights, Camera, Facade!](#lights-camera-facade)
        * [Constructing your home theater facade](#constructing-your-home-theater-facade)
        * [Implementing the simplified interface](#implementing-the-simplified-interface)
        * [Time to watch a movie (the easy way)](#time-to-watch-a-movie-the-easy-way)
        * [Facade Pattern defined](#facade-pattern-defined)
        * [The Principle of Least Knowledge](#the-principle-of-least-knowledge)
        * [How NOT to Win Friends and Influence Objects](#how-not-to-win-friends-and-influence-objects)
        * [The Facade Pattern and the Principle of Least Knowledge](#the-facade-pattern-and-the-principle-of-least-knowledge)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-6)
    * [Encapsulating Algorithms: theTemplate Method Pattern](#encapsulating-algorithms-thetemplate-method-pattern)
        * [It’s time for some more caffeine](#its-time-for-some-more-caffeine)
        * [Whipping up some coffee and tea classes (in Java)](#whipping-up-some-coffee-and-tea-classes-in-java)
        * [Let’s abstract that Coffee and Tea](#lets-abstract-that-coffee-and-tea)
        * [Taking the design further…](#taking-the-design-further)
        * [Abstracting prepareRecipe()](#abstracting-preparerecipe)
        * [What have we done?](#what-have-we-done-1)
        * [Meet the Template Method](#meet-the-template-method)
        * [What did the Template Method get us?](#what-did-the-template-method-get-us)
        * [Template Method Pattern defined](#template-method-pattern-defined)
        * [Hooked on Template Method…](#hooked-on-template-method)
        * [Using the hook](#using-the-hook)
        * [The Hollywood Principle and Template Method](#the-hollywood-principle-and-template-method)
        * [Template Methods in the Wild](#template-methods-in-the-wild)
        * [Sorting with Template Method](#sorting-with-template-method)
        * [We’ve got some ducks to sort…](#weve-got-some-ducks-to-sort)
        * [What is compareTo()?](#what-is-compareto)
        * [Comparing Ducks and Ducks](#comparing-ducks-and-ducks)
        * [Let’s sort some Ducks](#lets-sort-some-ducks)
        * [The making of the sorting duck machine](#the-making-of-the-sorting-duck-machine)
        * [Swingin’ with Frames](#swingin-with-frames)
        * [Custom Lists with AbstractList](#custom-lists-with-abstractlist)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-7)
    * [Well-Managed Collections: the Iterator and Composite Patterns](#well-managed-collections-the-iterator-and-composite-patterns)
        * [Breaking News: Objectville Diner and Objectville Pancake House Merge](#breaking-news-objectville-diner-and-objectville-pancake-house-merge)
        * [Check out the Menu Items](#check-out-the-menu-items)
        * [Implementing the spec: our first attempt](#implementing-the-spec-our-first-attempt)
        * [Can we encapsulate the iteration?](#can-we-encapsulate-the-iteration)
        * [Meet the Iterator Pattern](#meet-the-iterator-pattern)
        * [Adding an Iterator to DinerMenu](#adding-an-iterator-to-dinermenu)
        * [Reworking the DinerMenu with Iterator](#reworking-the-dinermenu-with-iterator)
        * [Fixing up the Waitress code](#fixing-up-the-waitress-code)
        * [Testing our code](#testing-our-code)
        * [Reviewing our current design…](#reviewing-our-current-design)
        * [Cleaning things up with java.util.Iterator](#cleaning-things-up-with-javautiliterator)
        * [Iterator Pattern defined](#iterator-pattern-defined)
        * [The Iterator Pattern Structure](#the-iterator-pattern-structure)
        * [The Single Responsibility Principle](#the-single-responsibility-principle)
        * [Meet Java’s Iterable interface](#meet-javas-iterable-interface)
        * [Java’s enhanced for loop](#javas-enhanced-for-loop)
        * [Taking a look at the Café Menu](#taking-a-look-at-the-café-menu)
        * [Iterators and Collections](#iterators-and-collections)
        * [Is the Waitress ready for prime time?](#is-the-waitress-ready-for-prime-time)
        * [The Composite Pattern defined](#the-composite-pattern-defined)
        * [Designing Menus with Composite](#designing-menus-with-composite)
        * [Implementing MenuComponent](#implementing-menucomponent)
        * [Implementing the MenuItem](#implementing-the-menuitem)
        * [Implementing the Composite Menu](#implementing-the-composite-menu)
        * [Now for the test drive…](#now-for-the-test-drive)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-8)
    * [The State of Things: the State Pattern](#the-state-of-things-the-state-pattern)
        * [Java Breakers](#java-breakers)
        * [State machines 101](#state-machines-101)
        * [Writing the code](#writing-the-code)
        * [In-house testing](#in-house-testing)
        * [You knew it was coming…a change request!](#you-knew-it-was-cominga-change-request)
        * [The messy STATE of things…](#the-messy-state-of-things)
        * [The new design](#the-new-design)
        * [Defining the State interfaces and classes](#defining-the-state-interfaces-and-classes)
        * [Reworking the Gumball Machine](#reworking-the-gumball-machine)
        * [Now, let’s look at the complete GumballMachine class…](#now-lets-look-at-the-complete-gumballmachine-class)
        * [Implementing more states](#implementing-more-states)
        * [The State Pattern defined](#the-state-pattern-defined)
        * [We still need to finish the Gumball 1 in 10 game](#we-still-need-to-finish-the-gumball-1-in-10-game)
        * [Finishing the game](#finishing-the-game)
        * [Demo for the CEO of Mighty Gumball, Inc.](#demo-for-the-ceo-of-mighty-gumball-inc)
        * [Sanity check…](#sanity-check)
        * [We almost forgot!](#we-almost-forgot)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-9)
    * [Controlling Object Access: the Proxy Pattern](#controlling-object-access-the-proxy-pattern)
        * [Coding the Monitor](#coding-the-monitor)
        * [Testing the Monitor](#testing-the-monitor)
        * [Remote methods 101](#remote-methods-101)
        * [Getting the GumballMachine ready to be a remote service](#getting-the-gumballmachine-ready-to-be-a-remote-service)
        * [Registering with the RMI registry…](#registering-with-the-rmi-registry)
        * [The Proxy Pattern defined](#the-proxy-pattern-defined)
        * [Get ready for the Virtual Proxy](#get-ready-for-the-virtual-proxy)
        * [Designing the Album Cover Virtual Proxy](#designing-the-album-cover-virtual-proxy)
        * [Writing the Image Proxy](#writing-the-image-proxy)
        * [Using the Java API’s Proxy to create a protection proxy](#using-the-java-apis-proxy-to-create-a-protection-proxy)
        * [Geeky Matchmaking in Objectville](#geeky-matchmaking-in-objectville)
        * [The Person implementation](#the-person-implementation)
        * [Five-minute drama: protecting subjects](#five-minute-drama-protecting-subjects)
        * [Big Picture: creating a Dynamic Proxy for the Person](#big-picture-creating-a-dynamic-proxy-for-the-person)
        * [The Proxy Zoo](#the-proxy-zoo)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-10)
        * [The code for the Album Cover Viewer](#the-code-for-the-album-cover-viewer)
    * [Patterns of Patterns: compound patterns](#patterns-of-patterns-compound-patterns)
        * [Working together](#working-together)
        * [Duck reunion](#duck-reunion)
        * [What did we do?](#what-did-we-do)
        * [A bird’s duck’s-eye view: the class diagram](#a-birds-ducks-eye-view-the-class-diagram)
        * [The King of Compound Patterns](#the-king-of-compound-patterns)
        * [Meet Model-View-Controller](#meet-model-view-controller)
        * [A closer look…](#a-closer-look)
        * [Understanding MVC as a set of Patterns](#understanding-mvc-as-a-set-of-patterns)
        * [Using MVC to control the beat…](#using-mvc-to-control-the-beat)
        * [Building the pieces](#building-the-pieces)
        * [Now let’s have a look at the concrete BeatModel class](#now-lets-have-a-look-at-the-concrete-beatmodel-class)
        * [The View](#the-view)
        * [Implementing the View](#implementing-the-view)
        * [Now for the Controller](#now-for-the-controller)
        * [Putting it all together…](#putting-it-all-together)
        * [Exploring Strategy](#exploring-strategy)
        * [Adapting the Model](#adapting-the-model)
        * [And now for a test run…](#and-now-for-a-test-run)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-11)
    * [Patterns in the Real World: better living with patterns](#patterns-in-the-real-world-better-living-with-patterns)
        * [Design Pattern defined](#design-pattern-defined)
        * [Looking more closely at the Design Pattern definition](#looking-more-closely-at-the-design-pattern-definition)
        * [May the force be with you](#may-the-force-be-with-you)
        * [So you wanna be a Design Patterns writer](#so-you-wanna-be-a-design-patterns-writer)
        * [Organizing Design Patterns](#organizing-design-patterns)
        * [Thinking in Patterns](#thinking-in-patterns)
        * [Your Mind on Patterns](#your-mind-on-patterns)
        * [Don’t forget the power of the shared vocabulary](#dont-forget-the-power-of-the-shared-vocabulary)
        * [Cruisin’ Objectville with the Gang of Four](#cruisin-objectville-with-the-gang-of-four)
        * [Your journey has just begun…](#your-journey-has-just-begun)
        * [The Patterns Zoo](#the-patterns-zoo)
        * [Annihilating evil with Anti-Patterns](#annihilating-evil-with-anti-patterns)
        * [Tools for your Design Toolbox](#tools-for-your-design-toolbox-12)
        * [Leaving Objectville](#leaving-objectville)
    * [Appendix: Leftover Patterns](#appendix-leftover-patterns)
        * [Bridge](#bridge)
        * [Builder](#builder)
        * [Chain of Responsibility](#chain-of-responsibility)
        * [Flyweight](#flyweight)
        * [Interpreter](#interpreter)
        * [Mediator](#mediator)
        * [Memento](#memento)
        * [Prototype](#prototype)
        * [Visitor](#visitor)

<!-- TOC -->

------------------------------------------------------------------------------------------------------------------

## Welcome to Design Patterns: intro to Design Patterns

### It started with a simple SimUDuck app

### But now we need the ducks to FLY

### But something went horribly wrong…

### Joe thinks about inheritance…

### How about an interface?

### What would you do if you were Joe?

### The one constant in software development

### Zeroing in on the problem…

### Separating what changes from what stays the same

### Designing the Duck Behaviors

### Implementing the Duck Behaviors

### Integrating the Duck Behavior

### Testing the Duck code

### Setting behavior dynamically

### The Big Picture on encapsulated behaviors

### HAS-A can be better than IS-A

### Speaking of Design Patterns…

### Overheard at the local diner…

### Overheard in the next cubicle…

### The power of a shared pattern vocabulary

### How do I use Design Patterns?

### Tools for your Design Toolbox

------------------------------------------------------------------------------------------------------------------

## Keeping your Objects in the Know: the Observer Pattern

### The Weather Monitoring application overview

### Meet the Observer Pattern

### Publishers + Subscribers = Observer Pattern

### The Observer Pattern defined

### The Power of Loose Coupling

### Designing the Weather Station

### Implementing the Weather Station

### Power up the Weather Station

### Looking for the Observer Pattern in the Wild

### Coding the life-changing application

### Meanwhile, back at Weather-O-Rama

### Test Drive the new code

### Tools for your Design Toolbox

### Design Principle Challenge

------------------------------------------------------------------------------------------------------------------

## Decorating Objects: the Decorator Pattern

### Welcome to Starbuzz Coffee

### The Open-Closed Principle

### Meet the Decorator Pattern

### Constructing a drink order with Decorators

### The Decorator Pattern defined

### Decorating our Beverages

### Writing the Starbuzz code

### Coding beverages

### Coding condiments

### Serving some coffees

### Real-World Decorators: Java I/O

### Decorating the java.io classes

### Writing your own Java I/O Decorator

### Test out your new Java I/O Decorator

### Tools for your Design Toolbox

------------------------------------------------------------------------------------------------------------------

## Baking with OO Goodness: the Factory Pattern

### Identifying the aspects that vary

### Encapsulating object creation

### Building a simple pizza factory

### The Simple Factory defined

### A framework for the pizza store

### Allowing the subclasses to decide

### Declaring a factory method

### It’s finally time to meet the Factory Method Pattern

### View Creators and Products in Parallel

### Factory Method Pattern defined

### Looking at object dependencies

### The Dependency Inversion Principle

### Applying the Principle

### Families of ingredients…

### Building the ingredient factories

### Reworking the pizzas…

### Revisiting our pizza stores

### What have we done?

### Abstract Factory Pattern defined

### Factory Method and Abstract Factory compared

### Tools for your Design Toolbox

------------------------------------------------------------------------------------------------------------------

## One-of-a-Kind Objects: the Singleton Pattern

### Dissecting the classic Singleton Pattern implementation

### The Chocolate Factory

### Singleton Pattern defined

### Houston, we have a problem

### Dealing with multithreading

### Can we improve multithreading?

### Meanwhile, back at the Chocolate Factory…

### Tools for your Design Toolbox

------------------------------------------------------------------------------------------------------------------

## Encapsulating Invocation: the Command Pattern

### Home Automation or Bust

### Taking a look at the vendor classes

### A brief introduction to the Command Pattern

### From the Diner to the Command Pattern

### Our first command object

### Using the command object

### Assigning Commands to slots

### Implementing the Remote Control

### Implementing the Commands

### Putting the Remote Control through its paces

### Time to write that documentation…

### What are we doing?

### Time to QA that Undo button!

### Using state to implement Undo

### Adding Undo to the Ceiling Fan commands

### Every remote needs a Party Mode!

### Using a macro command

### More uses of the Command Pattern: queuing requests

### More uses of the Command Pattern: logging requests

### Command Pattern in the Real World

### Tools for your Design Toolbox

------------------------------------------------------------------------------------------------------------------

## Being Adaptive: the Adapter and Facade Patterns

### might be a duck turkey wrapped with a duck adapter…

### Test drive the adapter

### The Adapter Pattern explained

### Adapter Pattern defined

### Object and class adapters

### Real-world adapters

### Adapting an Enumeration to an Iterator

### Home Sweet Home Theater

### Watching a movie (the hard way)

### Lights, Camera, Facade!

### Constructing your home theater facade

### Implementing the simplified interface

### Time to watch a movie (the easy way)

### Facade Pattern defined

### The Principle of Least Knowledge

### How NOT to Win Friends and Influence Objects

### The Facade Pattern and the Principle of Least Knowledge

### Tools for your Design Toolbox

------------------------------------------------------------------------------------------------------------------

## Encapsulating Algorithms: theTemplate Method Pattern

### It’s time for some more caffeine

### Whipping up some coffee and tea classes (in Java)

### Let’s abstract that Coffee and Tea

### Taking the design further…

### Abstracting prepareRecipe()

### What have we done?

### Meet the Template Method

### What did the Template Method get us?

### Template Method Pattern defined

### Hooked on Template Method…

### Using the hook

### The Hollywood Principle and Template Method

### Template Methods in the Wild

### Sorting with Template Method

### We’ve got some ducks to sort…

### What is compareTo()?

### Comparing Ducks and Ducks

### Let’s sort some Ducks

### The making of the sorting duck machine

### Swingin’ with Frames

### Custom Lists with AbstractList

### Tools for your Design Toolbox

------------------------------------------------------------------------------------------------------------------

## Well-Managed Collections: the Iterator and Composite Patterns

### Breaking News: Objectville Diner and Objectville Pancake House Merge

### Check out the Menu Items

### Implementing the spec: our first attempt

### Can we encapsulate the iteration?

### Meet the Iterator Pattern

### Adding an Iterator to DinerMenu

### Reworking the DinerMenu with Iterator

### Fixing up the Waitress code

### Testing our code

### Reviewing our current design…

### Cleaning things up with java.util.Iterator

### Iterator Pattern defined

### The Iterator Pattern Structure

### The Single Responsibility Principle

### Meet Java’s Iterable interface

### Java’s enhanced for loop

### Taking a look at the Café Menu

### Iterators and Collections

### Is the Waitress ready for prime time?

### The Composite Pattern defined

### Designing Menus with Composite

### Implementing MenuComponent

### Implementing the MenuItem

### Implementing the Composite Menu

### Now for the test drive…

### Tools for your Design Toolbox

------------------------------------------------------------------------------------------------------------------

## The State of Things: the State Pattern

### Java Breakers

### State machines 101

### Writing the code

### In-house testing

### You knew it was coming…a change request!

### The messy STATE of things…

### The new design

### Defining the State interfaces and classes

### Reworking the Gumball Machine

### Now, let’s look at the complete GumballMachine class…

### Implementing more states

### The State Pattern defined

### We still need to finish the Gumball 1 in 10 game

### Finishing the game

### Demo for the CEO of Mighty Gumball, Inc.

### Sanity check…

### We almost forgot!

### Tools for your Design Toolbox

------------------------------------------------------------------------------------------------------------------

## Controlling Object Access: the Proxy Pattern

### Coding the Monitor

### Testing the Monitor

### Remote methods 101

### Getting the GumballMachine ready to be a remote service

### Registering with the RMI registry…

### The Proxy Pattern defined

### Get ready for the Virtual Proxy

### Designing the Album Cover Virtual Proxy

### Writing the Image Proxy

### Using the Java API’s Proxy to create a protection proxy

### Geeky Matchmaking in Objectville

### The Person implementation

### Five-minute drama: protecting subjects

### Big Picture: creating a Dynamic Proxy for the Person

### The Proxy Zoo

### Tools for your Design Toolbox

### The code for the Album Cover Viewer

------------------------------------------------------------------------------------------------------------------

## Patterns of Patterns: compound patterns

### Working together

### Duck reunion

### What did we do?

### A bird’s duck’s-eye view: the class diagram

### The King of Compound Patterns

### Meet Model-View-Controller

### A closer look…

### Understanding MVC as a set of Patterns

### Using MVC to control the beat…

### Building the pieces

### Now let’s have a look at the concrete BeatModel class

### The View

### Implementing the View

### Now for the Controller

### Putting it all together…

### Exploring Strategy

### Adapting the Model

### And now for a test run…

### Tools for your Design Toolbox

------------------------------------------------------------------------------------------------------------------

## Patterns in the Real World: better living with patterns

### Design Pattern defined

### Looking more closely at the Design Pattern definition

### May the force be with you

### So you wanna be a Design Patterns writer

### Organizing Design Patterns

### Thinking in Patterns

### Your Mind on Patterns

### Don’t forget the power of the shared vocabulary

### Cruisin’ Objectville with the Gang of Four

### Your journey has just begun…

### The Patterns Zoo

### Annihilating evil with Anti-Patterns

### Tools for your Design Toolbox

### Leaving Objectville

------------------------------------------------------------------------------------------------------------------

## Leftover Patterns

### Bridge

### Builder

### Chain of Responsibility

### Flyweight

### Interpreter

### Mediator

### Memento

### Prototype

### Visitor