# Thymeleaf

------------------------------------------------------------------------------------------------------------------

## Table Of Contents

<!-- TOC -->
* [Thymeleaf](#thymeleaf)
  * [Table Of Contents](#table-of-contents)
  * [Thymeleaf introduction](#thymeleaf-introduction)
    * [What is Thymeleaf?](#what-is-thymeleaf)
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
    * [Summary](#summary)
  * [Fragments](#fragments)
    * [What are fragments?](#what-are-fragments)
    * [Using fragments](#using-fragments)
    * [Fragments with parameters](#fragments-with-parameters)
    * [Fragments with HTML snippets as arguments](#fragments-with-html-snippets-as-arguments)
    * [Inline separate SVG files](#inline-separate-svg-files)
    * [Homepage refactoring](#homepage-refactoring)
    * [Menu item components](#menu-item-components)
    * [Summary](#summary-1)
  * [Layouts](#layouts)
    * [What is the Thymeleaf Layout Dialect?](#what-is-the-thymeleaf-layout-dialect)
    * [Layouts with parameters](#layouts-with-parameters)
    * [Page titles](#page-titles)
    * [Homepage refactoring](#homepage-refactoring-1)
    * [Summary](#summary-2)
  * [Controllers](#controllers)
    * [What is a controller?](#what-is-a-controller)
    * [Exposing data to the view](#exposing-data-to-the-view)
    * [Path parameters](#path-parameters)
    * [Posting data](#posting-data)
    * [Support for other HTTP methods](#support-for-other-http-methods)
    * [Team and User controllers](#team-and-user-controllers)
    * [Summary](#summary-3)
  * [Internationalization](#internationalization)
    * [Internationalization basics](#internationalization-basics)
    * [Using a query parameter to select the language](#using-a-query-parameter-to-select-the-language)
    * [Menu items translations](#menu-items-translations)
    * [Summary](#summary-4)
  * [Database connection](#database-connection)
    * [Spring Data JPA](#spring-data-jpa)
    * [PostgreSQL database](#postgresql-database)
    * [Getting started with Spring Data JPA](#getting-started-with-spring-data-jpa)
      * [Add Spring Data JPA to the project](#add-spring-data-jpa-to-the-project)
      * [User Entity](#user-entity)
      * [User repository](#user-repository)
      * [User Repository Test](#user-repository-test)
      * [Adding properties to User](#adding-properties-to-user)
    * [Summary](#summary-5)
  * [Displaying data](#displaying-data)
    * [Generate random users](#generate-random-users)
    * [Get users on the HTML page](#get-users-on-the-html-page)
    * [Refactor the table using fragments](#refactor-the-table-using-fragments)
    * [Use pagination](#use-pagination)
    * [Hide columns on mobile](#hide-columns-on-mobile)
    * [Summary](#summary-6)
  * [Forms](#forms)
    * [Form fields](#form-fields)
    * [Error messages](#error-messages)
    * [Custom error messages](#custom-error-messages)
    * [Custom validator](#custom-validator)
    * [Errors summary](#errors-summary)
    * [Validation groups and order](#validation-groups-and-order)
    * [Summary](#summary-7)
  * [Data editing](#data-editing)
    * [Add user button](#add-user-button)
    * [Edit user data](#edit-user-data)
    * [Refactoring to fragments](#refactoring-to-fragments)
    * [Handling Optimistic Locking failure](#handling-optimistic-locking-failure)
    * [Custom error pages](#custom-error-pages)
    * [Summary](#summary-8)
  * [Implement deletion of an entity](#implement-deletion-of-an-entity)
    * [Using a dedicated URL](#using-a-dedicated-url)
    * [Using the DELETE HTTP method](#using-the-delete-http-method)
    * [Flash attributes](#flash-attributes)
    * [Summary](#summary-9)
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
    * [Summary](#summary-10)
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
    * [Summary](#summary-11)
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

## Thymeleaf introduction

### What is Thymeleaf?

- Thymeleaf is a server-side Java template engine that can be used in web and standalone environments
- Natural templates are HTML templates that can correctly be displayed in browsers and work as static prototypes
- It is mainly used for HTML, but can also be used for XML, JavaScript, CSS or plain text.
- This diagram shows how server-side rendering works:
    - The browser starts by doing a GET request over the network to the server where the application runs
    - The application will match the requested path of the URL to a Controller. This is a piece of software in our application that will build a kind of Map of java objects that will be used by the template during rendering. We call this map the Model
    - The application finds the Thymeleaf template to use for rendering
    - The application uses the Thymeleaf engine (also running inside the application) to combine the template with the Java objects in the model. This results in an HTML page
    - The application returns the generated HTML page to the browser where the browser renders it

![how server-side rendering works.png](./images/how%20server-side%20rendering%20works.png)

- We are using Thymeleaf with Spring MVC. MVC is an acronym for Model View Controller. It is a well-known design pattern.
    - Model → Object that the controller passes to the view with the data to be used for the rendering of the template.
    - View → when we created our `index.html` template. It is the visual part of the design pattern
    - Controller → The controller is responsible for fetching the data from the application, and showing the correct view according to the requested URL. It usually has no actual business logic, but delegates to other components in the application

### Writing our first controller

```java
import org.springframework.stereotype.Controller;
import org.springframework.ui.Model;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RequestMapping;

import java.util.Set;

@Controller
@RequestMapping("/")
public class RootController {
    @GetMapping
    public String index(Model model) {
        model.addAttribute("pageTitle", "Taming Thymeleaf");
        model.addAttribute("developers", Set.of("Developer 1", "Developer 2", "Developer 3"));
        return "index";
    }
}
```

- The `@Controller` annotation indicates to Spring Boot that this class is a controller. The component scanning will automatically create an instance of this class and add it to the Spring Context
- The `@RequestMapping` annotation sets the root path of the URL for all methods of the class
- `GetMapping` indicates that an `HTTP GET` will call this method. Note that the name of the method (index in the example) really does not matter at all for the working of the application
- Controller methods can declare parameters of certain types that Spring MVC will inject with the proper instances. We will later see some other examples, but `Model` is one of the most important ones. It allows adding attributes that Thymeleaf can use to render the data
- We add a simple `String` value under the `pageTitle` key to the model
- We can also add complex objects or collections to the model
- The return value of a controller method has a few options. One of the simplest ones is to return a String. The value will be interpreted as the path to the template. With default Spring Boot, this is relative to the `src/main/resources/templates` directory

```html
<!DOCTYPE html>
<html lang="en"
      xmlns="http://www.w3.org/1999/xhtml"
      xmlns:th="http://www.thymeleaf.org">
<head>
    <meta charset="UTF-8">
    <title>Taming Thymeleaf</title>
</head>
<body>
<h1 th:text="${pageTitle}">Taming Thymeleaf</h1>
<div>
    <ul>
        <li th:each="developer : ${developers}"> ②
            <span th:text="${developer}"></span>
        </li>
    </ul>
</div>
</body>
</html>
```

- Use the `pageTitle` model attribute. Note that the actual text Taming Thymeleaf inside the `<h1>` tag does not matter at all. Thymeleaf will overwrite it with the contents of `pageTitle`
- Use the `th:each` tag to loop over our collection of scientists

### Thymeleaf expressions

- The expression inside the `th:*` HTML attributes are `OGNL` (**_Object-Graph Navigation Language_**) expression by default.
- However, in a Spring Boot application, those are SpringEL (Spring Expression Language) expressions. Luckily, in most cases, the syntax is exactly the same

#### Variables

- When a Thymeleaf template gets processed, the application will put variables in the context via the controller.
- Those variables can be referenced in the templates via the `${…}` syntax
    - `<div th:text="${username}"></div>`
- Suppose there is a String in the Thymeleaf context with the name username that has the value John Doe, then the HTML will be rendered as: `<div>John Doe</div>`
- The variable in the context does not need to be a `String`. Other types will have their `toString()` method invoked
- The Thymeleaf variable syntax is not limited to the exact object placed on the context. We can call methods:
    - `<div th:text="${user.getName()}"></div>`
    - Or if the method name adheres to the **_JavaBean specification_**, we can simulate property access: `<div th:text="${user.name}"></div>`
- `Map`:
    - If the object in the context is a `Map`, then dot notation can be used to access a value via its key: `<div th:text="${capitalsOfTheWorld.Belgium}"></div>`
    - Alternatively, use the bracket syntax. For certain keys (E.g., if they contain spaces) you will need to use the bracket syntax: `<div th:text="${capitalsOfTheWorld['The Netherlands']}"></div>`
- `Array` or `List`
    - `Collections` that allow indexed access can be used like this: `<div th:text="${vehiclesList[0].name}"></div>`

#### Text

- Most applications will require that they can be translated into the language of the user. Even if it is not a requirement at the start, you probably want to do this in case it ever becomes a requirement
    - The syntax for this is: `<h1 th:text="#{dashboard.title}"></h1>`
    - By default, Spring Boot will pick up translations from a `src/main/resources/messages.properties` file `dashboard.title=Dashboard`
    - Additional languages can be added by adding another such file, but post-fixing the file name with the locale. For example, use `messages_nl.properties` for Dutch translations

#### Selected objects

- Thymeleaf has a kind of shortcut syntax in case you need to use many properties of a single object. Suppose you have a template that displays information about a car like this:

```html

<div>
    <p>Brand: <span th:text="${car.brand}"></span></p>
    <p>Type: <span th:text="${car.type}"></span></p>
    <p>Fuel: <span th:text="${car.fuelType}"></span></p>
    <p>Color: <span th:text="${car.color}"></span></p>
</div>
```

- You can avoid the duplication of the car variable by selecting the variable with the `th:object` attribute and refer to the properties of the selected object using the `*{…}` syntax:
    - If there is no object selected, then `${…}` and `*{…}` are equivalent

```html

<div th:object="${car}">
    <p>Brand: <span th:text="*{brand}"></span></p>
    <p>Type: <span th:text="*{type}"></span></p>
    <p>Fuel: <span th:text="*{fuelType}"></span></p>
    <p>Color: <span th:text="*{color}"></span></p>
</div>
```

#### Link to URLs

- What would a web application be without URLs? It would have been basic, I guess. As URLs are so important, there is a special syntax for them: `@{…}`
    - This can be used for an absolute URL: `<a th:href="@{https://www.google.com/search?q=thymeleaf"></a>`
    - or a relative URL: `<a th:href="@{/users}"></a>`
    - We can also use variables inside those links: `<a th:href="@{https://www.google.com/search(q=${searchTerm})"></a>`
    - If the variable is not referenced in the URL itself, it is added as a query parameter. If it is referenced, it can be used as a path variable: `<a th:href="@{/users/{userId}/edit(userId=${user.id})"></a>`
        - Will output `'/users/123/edit'`

#### Literal substitutions

- If you need to combine a string literal with a variable, you can do something like this: `<div th:id="'container-' + ${index}"></div>`
- Thymeleaf has a shortcut syntax that is equivalent using the pipe (`|`) symbol: `<div th:id="|container-${index}|"></div>`

#### Expression inlining

- Instead of using `th:*` tags to use variables, it might be desirable at times to directly put a variable result in HTML. This is possible in Thymeleaf using expression inlining
    - `<span>The total price is [[${totalPrice}]]</span>` -> `<span>The total price is € 5.00</span>`

### Thymeleaf attributes

- The Thymeleaf expressions we just saw can be used inside Thymeleaf attributes. For example, the `th:text` attribute is one of those. This section will show the most important ones.

#### Element text content

- `th:text` will place the result of the expression inside the tag it is declared on
    - `<div th:text="${username}">Bob</div>` -> `<div>Jane</div>`

#### Element id attribute

- `th:id` will add an id attribute with the result of the expression on the tag it is declared on
    - `<div th:id="|container-${userId}|"></div>` -> `<div id="container-1"></div>`

#### Conditional inclusion

- `th:if` will render the tag it is declared on only if the expression evaluates to `true`
    - `<div th:if="${user.followerCount > 10}">You are famous</div>` -> `<div>You are famous</div>`
        - Given the `user.followerCount` variable in the context a value greater than `10`.
        - If the variable is less than `10`, the `<div>` will not be rendered in the output

#### Conditional exclusion

- `th:unless` will render the tag it is declared on only if the expression evaluates to `false`
    - `<div th:unless="${user.followerCount > 0}">You have no followers currently.</div>` -> `<div>You have no followers currently</div>`
        - Given the `user.followerCount` variable in the context is exactly `0`.
        - If the variable is greater than `0`, the `<div>` will not be rendered in the output
- Thymeleaf has no `if`/`else` statement, but this can be easily done by combining `th:if` with `th:unless`. For example:

```html

<div th:if="${user.followerCount > 0}">You have <span
        th:text="${user.followerCount}"></span> followers currently.
</div>
<div th:unless="${user.followerCount > 0}">You have no followers
    currently.
</div>
```

- Either the first `<div>` or the 2nd one will be rendered depending on the value of `user.followerCount`

#### Iteration

- `th:each` allows iterating over a collection. It will create as many tags as there are items in the collection

```html

<ul>
    <li th:each="scientist : ${scientists}" th:text="${scientist.name}"></li>
</ul>
```

- Thymeleaf will do the "right thing" you expect in the above example and first evaluate the `th:each` and then the `th:text`
    - There is a defined precedence in the attribute processing that ensures the proper order

### Preprocessing

- Thymeleaf has a preprocessing expression. This allows first executing the preprocessing and use the result of that in the final rendering of the templates; so basically, it’s an expression inside another expression that Thymeleaf resolves in two passes.
- This will be especially useful for Fragments which we will cover later
- As a simple example, consider this snippet: `<h1 th:text="#{__${title}__}"></h1>`
    - Thymeleaf will first substitute `${title}` with the value of that parameter
    - Assume `users.title` for example and then This will turn the template into the following: `<h1 th:text="#{users.title}"></h1>`

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

- [**Tutorial: Using Thymeleaf**](https://www.thymeleaf.org/doc/tutorials/3.1/usingthymeleaf.pdf)
- [**Tutorial: Thymeleaf + Spring**](https://www.thymeleaf.org/doc/tutorials/3.1/thymeleafspring.pdf)
- [**Tutorial: Extending Thymeleaf**](https://www.thymeleaf.org/doc/tutorials/3.1/extendingthymeleaf.pdf)
- [**Thymeleaf Docs**](https://www.thymeleaf.org/documentation.html)