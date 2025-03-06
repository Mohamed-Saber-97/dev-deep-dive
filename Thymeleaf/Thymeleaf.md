# Thymeleaf

------------------------------------------------------------------------------------------------------------------

## Table Of Contents

<!-- TOC -->

* [Thymeleaf](#thymeleaf)
    * [Table Of Contents](#table-of-contents)
    * [What are Spring Boot and Thymeleaf?](#what-are-spring-boot-and-thymeleaf)
        * [Spring Framework](#spring-framework)
        * [Spring Boot](#spring-boot)
        * [Thymeleaf](#thymeleaf-1)
    * [Getting started](#getting-started)
        * [Prerequisites](#prerequisites)
            * [macOS/Linux](#macoslinux)
            * [Windows](#windows)
        * [Spring Initializer](#spring-initializer)
        * [Summary](#summary)
    * [Thymeleaf introduction](#thymeleaf-introduction)
        * [What is Thymeleaf?](#what-is-thymeleaf)
        * [Writing our first template](#writing-our-first-template)
        * [Writing our first controller](#writing-our-first-controller)
        * [Thymeleaf expressions](#thymeleaf-expressions)
            * [Variables](#variables)
            * [Text](#text)
            * [Selected objects](#selected-objects)
            * [Link to URLs](#link-to-urls)
            * [Literal substitutions](#literal-substitutions)
            * [Expression inlining](#expression-inlining)
        * [Thymeleaf attributes](#thymeleaf-attributes)
            * [Element text content](#element-text-content)
            * [Element id attribute](#element-id-attribute)
            * [Conditional inclusion](#conditional-inclusion)
            * [Conditional exclusion](#conditional-exclusion)
            * [Iteration](#iteration)
        * [Preprocessing](#preprocessing)
        * [Summary](#summary-1)
    * [Thyme Wizards](#thyme-wizards)
        * [Cascading Style Sheets](#cascading-style-sheets)
        * [Tailwind CSS](#tailwind-css)
            * [What is Tailwind CSS?](#what-is-tailwind-css)
            * [Adding Tailwind CSS](#adding-tailwind-css)
            * [Configure Maven](#configure-maven)
            * [Live reload](#live-reload)
            * [Tailwind CSS design system configuration](#tailwind-css-design-system-configuration)
        * [Application shell](#application-shell)
            * [Tailwind UI](#tailwind-ui)
            * [Client side interactivity](#client-side-interactivity)
            * [Serving static images](#serving-static-images)
        * [Summary](#summary-2)
    * [Fragments](#fragments)
        * [What are fragments?](#what-are-fragments)
        * [Using fragments](#using-fragments)
        * [Fragments with parameters](#fragments-with-parameters)
        * [Fragments with HTML snippets as arguments](#fragments-with-html-snippets-as-arguments)
        * [Inline separate SVG files](#inline-separate-svg-files)
        * [Homepage refactoring](#homepage-refactoring)
        * [Menu item components](#menu-item-components)
        * [Summary](#summary-3)
    * [Layouts](#layouts)
        * [What is the Thymeleaf Layout Dialect?](#what-is-the-thymeleaf-layout-dialect)
        * [Layouts with parameters](#layouts-with-parameters)
        * [Page titles](#page-titles)
        * [Homepage refactoring](#homepage-refactoring-1)
        * [Summary](#summary-4)
    * [Controllers](#controllers)
        * [What is a controller?](#what-is-a-controller)
        * [Exposing data to the view](#exposing-data-to-the-view)
        * [Path parameters](#path-parameters)
        * [Posting data](#posting-data)
        * [Support for other HTTP methods](#support-for-other-http-methods)
        * [Team and User controllers](#team-and-user-controllers)
        * [Summary](#summary-5)
    * [Internationalization](#internationalization)
        * [Internationalization basics](#internationalization-basics)
        * [Using a query parameter to select the language](#using-a-query-parameter-to-select-the-language)
        * [Menu items translations](#menu-items-translations)
        * [Summary](#summary-6)
    * [Database connection](#database-connection)
        * [Spring Data JPA](#spring-data-jpa)
        * [PostgreSQL database](#postgresql-database)
        * [Getting started with Spring Data JPA](#getting-started-with-spring-data-jpa)
            * [Add Spring Data JPA to the project](#add-spring-data-jpa-to-the-project)
            * [User Entity](#user-entity)
            * [User repository](#user-repository)
            * [User Repository Test](#user-repository-test)
            * [Adding properties to User](#adding-properties-to-user)
        * [Summary](#summary-7)
    * [Displaying data](#displaying-data)
        * [Generate random users](#generate-random-users)
        * [Get users on the HTML page](#get-users-on-the-html-page)
        * [Refactor the table using fragments](#refactor-the-table-using-fragments)
        * [Use pagination](#use-pagination)
        * [Hide columns on mobile](#hide-columns-on-mobile)
        * [Summary](#summary-8)
    * [Forms](#forms)
        * [Form fields](#form-fields)
        * [Error messages](#error-messages)
        * [Custom error messages](#custom-error-messages)
        * [Custom validator](#custom-validator)
        * [Errors summary](#errors-summary)
        * [Validation groups and order](#validation-groups-and-order)
        * [Summary](#summary-9)
    * [Data editing](#data-editing)
        * [Add user button](#add-user-button)
        * [Edit user data](#edit-user-data)
        * [Refactoring to fragments](#refactoring-to-fragments)
        * [Handling Optimistic Locking failure](#handling-optimistic-locking-failure)
        * [Custom error pages](#custom-error-pages)
        * [Summary](#summary-10)
    * [Implement deletion of an entity](#implement-deletion-of-an-entity)
        * [Using a dedicated URL](#using-a-dedicated-url)
        * [Using the DELETE HTTP method](#using-the-delete-http-method)
        * [Flash attributes](#flash-attributes)
        * [Summary](#summary-11)
    * [Security](#security)
        * [Default Spring Security](#default-spring-security)
        * [Hardcoded password](#hardcoded-password)
        * [User roles](#user-roles)
            * [URL based authorization](#url-based-authorization)
            * [Annotation based authorization](#annotation-based-authorization)
        * [Thymeleaf integration](#thymeleaf-integration)
            * [User specific views](#user-specific-views)
            * [Current logged on user information](#current-logged-on-user-information)
        * [Custom logon page](#custom-logon-page)
        * [Users from database](#users-from-database)
            * [User entity updates](#user-entity-updates)
            * [Spring Security connection](#spring-security-connection)
            * [Show current user info](#show-current-user-info)
            * [Create user form](#create-user-form)
            * [Refactor the edit user implementation](#refactor-the-edit-user-implementation)
        * [Summary](#summary-12)
    * [Testing](#testing)
        * [Using @WebMvcTest](#using-webmvctest)
            * [Getting started with @WebMvcTest](#getting-started-with-webmvctest)
            * [Authenticating in the @WebMvcTest](#authenticating-in-the-webmvctest)
            * [Using HtmlUnit](#using-htmlunit)
        * [Using Cypress](#using-cypress)
            * [Cypress installation](#cypress-installation)
            * [First Cypress test](#first-cypress-test)
            * [Bypassing login](#bypassing-login)
            * [Running Cypress tests from JUnit](#running-cypress-tests-from-junit)
            * [JUnit Testfactory](#junit-testfactory)
        * [Summary](#summary-13)
    * [Various tips and tricks](#various-tips-and-tricks)
        * [Open Session In View](#open-session-in-view)
            * [What is it?](#what-is-it)
            * [Consequences of disabling](#consequences-of-disabling)
        * [StringTrimmerEditor](#stringtrimmereditor)
        * [Global model attributes](#global-model-attributes)
            * [Controller specific](#controller-specific)
            * [Application wide](#application-wide)
        * [File upload](#file-upload)
        * [Selecting a linked entity value](#selecting-a-linked-entity-value)
            * [Implementation](#implementation)
            * [Tests](#tests)
        * [Dynamically adding rows](#dynamically-adding-rows)
            * [Entities](#entities)
            * [Static server side rendering](#static-server-side-rendering)
            * [Make updates persistent](#make-updates-persistent)
            * [Add rows](#add-rows)
            * [Delete rows](#delete-rows)
        * [Custom editors and formatters](#custom-editors-and-formatters)
            * [Custom editor](#custom-editor)
            * [Custom formatter](#custom-formatter)
        * [Date picker](#date-picker)
            * [Duet Date Picker](#duet-date-picker)
            * [Internationalization of date picker](#internationalization-of-date-picker)
    * [Closing](#closing)
    * [Additional resources](#additional-resources)

<!-- TOC -->

------------------------------------------------------------------------------------------------------------------

## What are Spring Boot and Thymeleaf?

### Spring Framework

### Spring Boot

### Thymeleaf

------------------------------------------------------------------------------------------------------------------

## Getting started

### Prerequisites

#### macOS/Linux

#### Windows

### Spring Initializer

### Summary

------------------------------------------------------------------------------------------------------------------

## Thymeleaf introduction

### What is Thymeleaf?

### Writing our first template

### Writing our first controller

### Thymeleaf expressions

#### Variables

#### Text

#### Selected objects

#### Link to URLs

#### Literal substitutions

#### Expression inlining

### Thymeleaf attributes

#### Element text content

#### Element id attribute

#### Conditional inclusion

#### Conditional exclusion

#### Iteration

### Preprocessing

### Summary

------------------------------------------------------------------------------------------------------------------

## Thyme Wizards

### Cascading Style Sheets

### Tailwind CSS

#### What is Tailwind CSS?

#### Adding Tailwind CSS

#### Configure Maven

#### Live reload

#### Tailwind CSS design system configuration

### Application shell

#### Tailwind UI

#### Client side interactivity

#### Serving static images

### Summary

------------------------------------------------------------------------------------------------------------------

## Fragments

### What are fragments?

### Using fragments

### Fragments with parameters

### Fragments with HTML snippets as arguments

### Inline separate SVG files

### Homepage refactoring

### Menu item components

### Summary

------------------------------------------------------------------------------------------------------------------

## Layouts

### What is the Thymeleaf Layout Dialect?

### Layouts with parameters

### Page titles

### Homepage refactoring

### Summary

------------------------------------------------------------------------------------------------------------------

## Controllers

### What is a controller?

### Exposing data to the view

### Path parameters

### Posting data

### Support for other HTTP methods

### Team and User controllers

### Summary

------------------------------------------------------------------------------------------------------------------

## Internationalization

### Internationalization basics

### Using a query parameter to select the language

### Menu items translations

### Summary

------------------------------------------------------------------------------------------------------------------

## Database connection

### Spring Data JPA

### PostgreSQL database

### Getting started with Spring Data JPA

#### Add Spring Data JPA to the project

#### User Entity

#### User repository

#### User Repository Test

#### Adding properties to User

### Summary

------------------------------------------------------------------------------------------------------------------

## Displaying data

### Generate random users

### Get users on the HTML page

### Refactor the table using fragments

### Use pagination

### Hide columns on mobile

### Summary

------------------------------------------------------------------------------------------------------------------

## Forms

### Form fields

### Error messages

### Custom error messages

### Custom validator

### Errors summary

### Validation groups and order

### Summary

------------------------------------------------------------------------------------------------------------------

## Data editing

### Add user button

### Edit user data

### Refactoring to fragments

### Handling Optimistic Locking failure

### Custom error pages

### Summary

------------------------------------------------------------------------------------------------------------------

## Implement deletion of an entity

### Using a dedicated URL

### Using the DELETE HTTP method

### Flash attributes

### Summary

------------------------------------------------------------------------------------------------------------------

## Security

### Default Spring Security

### Hardcoded password

### User roles

#### URL based authorization

#### Annotation based authorization

### Thymeleaf integration

#### User specific views

#### Current logged on user information

### Custom logon page

### Users from database

#### User entity updates

#### Spring Security connection

#### Show current user info

#### Create user form

#### Refactor the edit user implementation

### Summary

------------------------------------------------------------------------------------------------------------------

## Testing

### Using @WebMvcTest

#### Getting started with @WebMvcTest

#### Authenticating in the @WebMvcTest

#### Using HtmlUnit

### Using Cypress

#### Cypress installation

#### First Cypress test

#### Bypassing login

#### Running Cypress tests from JUnit

#### JUnit Testfactory

### Summary

------------------------------------------------------------------------------------------------------------------

## Various tips and tricks

### Open Session In View

#### What is it?

#### Consequences of disabling

### StringTrimmerEditor

### Global model attributes

#### Controller specific

#### Application wide

### File upload

### Selecting a linked entity value

#### Implementation

#### Tests

### Dynamically adding rows

#### Entities

#### Static server side rendering

#### Make updates persistent

#### Add rows

#### Delete rows

### Custom editors and formatters

#### Custom editor

#### Custom formatter

### Date picker

#### Duet Date Picker

#### Internationalization of date picker

------------------------------------------------------------------------------------------------------------------

## Closing

------------------------------------------------------------------------------------------------------------------

## Additional resources

- [**Thymeleaf Docs**](https://www.thymeleaf.org/documentation.html)