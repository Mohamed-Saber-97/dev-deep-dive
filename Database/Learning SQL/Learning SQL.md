# Learning SQL

------------------------------------------------------------------------------------------------------------------

## Table Of Contents

------------------------------------------------------------------------------------------------------------------

## A Little Background.

### Introduction to Databases

#### Non-relational Database Systems

#### The Relational Model

#### Some Terminology

### What Is SQL?

#### SQL Statement Classes

#### SQL: A Non-procedural Language

#### SQL Examples

### What Is MySQL?

### SQL Unplugged

### What’s in Store

## Creating and Populating a Database

### Creating a MySQL Database

### Using the mysql Command-Line Tool

### MySQL Data Types

#### Character Data

#### Numeric Data

#### Temporal Data

### Table Creation

#### Step 1: Design

#### Step 2: Refinement

#### Step 3: Building SQL Schema Statements

### Populating and Modifying Tables

#### Inserting Data

#### Updating Data

#### Deleting Data

### When Good Statements Go Bad

#### Non-unique Primary Key

#### Nonexistent Foreign Key

#### Column Value Violations

#### Invalid Date Conversions

### The **Sakila** Database

## Query Primer

### Query Mechanics

### Query Clauses

### The select Clause

#### Column Aliases

#### Removing Duplicates

### The `FROM` Clause

#### Tables

#### Table Links

#### Defining Table Aliases

### The where Clause

### The group by and having Clauses

### The order by Clause

#### Ascending Versus Descending Sort Order

#### Sorting via Numeric Placeholders

## Filtering

### Condition Evaluation

#### Using Parentheses

#### Using the not Operator

### Building a Condition

### Condition Types

#### Equality Conditions

#### Range Conditions

#### Membership Conditions

#### Matching Conditions

### Null: That Four-Letter Word

## Querying Multiple Tables

### What Is a Join?

#### Cartesian Product

#### Inner Joins

#### The ANSI Join Syntax

### Joining Three or More Tables

#### Using Subqueries as Tables

#### Using the Same Table Twice

### Self-Joins

## Working with Sets

### Set Theory Primer

### Set Theory in Practice

### Set Operators

#### The union Operator

#### The `intersect` Operator

#### The `except` Operator

### Set Operation Rules

#### Sorting Compound Query Results

#### Set Operation Precedence

## Data Generation, Manipulation, and Conversion

### Working with String Data

#### String Generation

#### String Manipulation

### Working with Numeric Data

#### Performing Arithmetic Functions

#### Controlling Number Precision

#### Handling Signed Data

### Working with Temporal Data

#### Dealing with Time Zones

#### Generating Temporal Data

#### Manipulating Temporal Data

### Conversion Functions

## Grouping and Aggregates

### Grouping Concepts

### Aggregate Functions

#### Implicit Versus Explicit Groups

#### Counting Distinct Values

#### Using Expressions

#### How Nulls Are Handled

### Generating Groups

#### Single-Column Grouping

#### Multi-column Grouping

#### Grouping via Expressions

#### Generating Roll-ups

### Group Filter Conditions

## Subqueries

### What Is a Subquery?

### Subquery Types

### Non-correlated Subqueries

#### Multiple-Row, Single-Column Subqueries

#### Multi-column Subqueries

### Correlated Subqueries

#### The `exists` Operator

#### Data Manipulation Using Correlated Subqueries

### When to Use Subqueries

#### Subqueries as Data Sources

#### Subqueries as Expression Generators

### Subquery Wrap-Up

## `Joins` Revisited

### Outer Joins

#### Left Versus Right Outer Joins

#### Three-Way Outer Joins

### Cross Joins

### Natural Joins

## Conditional Logic

### What Is Conditional Logic?

### The case Expression

#### Searched case Expressions

#### Simple case Expressions

### Examples of case Expressions

#### Result Set Transformations

#### Checking for Existence

#### Division-by-Zero Errors

#### Conditional Updates

#### Handling Null Values

## Transactions

### Multiuser Databases

#### Locking

#### Lock Granularities

### What Is a Transaction?

#### Starting a Transaction

#### Ending a Transaction

#### Transaction Save-points

## Indexes and Constraints

### Indexes

#### Index Creation

#### Types of Indexes

#### How Indexes Are Used

#### The Downside of Indexes

### Constraints

#### Constraint Creation

## Views

### What Are Views?

### Why Use Views?

#### Data Security

#### Data Aggregation

#### Hiding Complexity

#### Joining Partitioned Data

### Updatable Views

#### Updating Simple Views

#### Updating Complex Views

## Metadata

### Data About Data

### information_schema

### Working with Metadata

#### Schema Generation Scripts

#### Deployment Verification

#### Dynamic SQL Generation

## Analytic Functions

### Analytic Function Concepts

#### Data Windows

#### Localized Sorting

### Ranking

#### viii | Table of Contents

#### Ranking Functions

#### Generating Multiple Rankings

### Reporting Functions

#### Window Frames

#### Lag and Lead

#### Column Value Concatenation

## Working with Large Databases

### Partitioning

#### Partitioning Concepts

#### Table Partitioning

#### Index Partitioning

#### Partitioning Methods

#### Partitioning Benefits

### Clustering

### Sharding

### Big Data

#### Hadoop

#### NoSQL and Document Databases

#### Cloud Computing

#### Conclusion

## SQL and Big Data

### Introduction to Apache Drill

### Querying Files Using Drill

### Querying MySQL Using Drill

### Querying MongoDB Using Drill

### Drill with Multiple Data Sources

### Future of SQL

## ER Diagram for Example Database