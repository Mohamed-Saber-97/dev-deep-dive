# Flowable Open Source

## Introducing Flowable Open Source

- **Required software:** Flowable runs on a JDK 17+
- **Modeling:** free to use Flowable Cloud Design application, which you can use to model CMMN, BPMN, DMN and other model types.
- **BPMN (Business Process Model and Notation):**
    - **Purpose:** Used for modeling business processes, defining workflows, and automating them.
    - **Use Case:** Sequential workflows such as order processing, employee onboarding, approval workflows, etc.
    - **Key Elements:**
        - Tasks (User Task, Service Task, Script Task)
        - Gateways (Exclusive, Inclusive, Parallel)
        - Events (Start, End, Intermediate)
        - Sequence Flows (connectors between tasks and events)
    - **Example:** A process where a manager approves a leave request before HR processes it.
- **CMMN (Case Management Model and Notation):**
    - **Purpose:** Used for modeling case management scenarios where workflows are more dynamic and unstructured.
    - **Use Case:** Customer service cases, legal case handling, insurance claims, etc.
    - **Key Elements:**
        - Case Plan Model (defines the structure of a case)
        - Stages (logical groupings of tasks)
        - Tasks (User Task, Human Task, Process Task)
        - Milestones (mark significant events in a case)
        - Sentries (conditions that trigger tasks or transitions)
    - **Example:** A legal case where different tasks (document review, client meetings, court proceedings) may be performed in any order depending on the situation.
- **DMN (Decision Model and Notation)**
    - **Purpose:** Used for modeling decision logic using decision tables
    - **Use Case:** Business rules such as loan approval criteria, insurance pricing, risk assessment, etc.
    - **Key Elements:**
        - Decision Tables (define conditions and outcomes)
        - Input Data (data required for decisions)
        - Business Knowledge Models (reusable decision logic)
    - **Example:**
        - A decision table that determines whether a loan should be approved based on factors like credit score and income.
- **Other Model Types**
    - **Form Models:** Used to design UI forms for user tasks in BPMN and CMMN
    - **App Models:** Used to bundle multiple models into a deployable application
    - **Connector Models:** Define integrations with external systems via REST, database queries, etc
- **Experimental features:**
    - Sections marked with **EXPERIMENTAL** should not be considered stable
    - All classes that have .impl. in the package name are internal implementation classes and cannot be considered stable or guaranteed in any way.
    - However, if the User Guide mentions any classes as configuration values, they are supported and can be considered stable
- **Versioning Strategy: MAJOR.MINOR.MICRO**
    - **MAJOR:** evolutions of the core engines
    - **MINOR:** new features and new APIs
    - **MICRO:** bug fixes and improvements
- Flowable attempts to remain "source compatible" in MINOR and MICRO releases for all non-internal implementation classes and "binary compatible" in MINOR and MICRO releases
    - We define "source compatible" to mean an application will continue to build without error and the semantics have remained unchanged
    - We define "binary compatible" to mean that this new version of Flowable can be dropped as a jar replacement into a compiled application and continue to function properly

## BPMN User Guide

### What is Flowable?

- Flowable is a light-weight business process engine written in Java. The Flowable process engine allows you to deploy BPMN 2.0 process definitions (an industry XML standard for defining processes), creating process instances of those process definitions, running queries, accessing active or historical process instances and related data, plus much more
- You can use the Flowable REST API to communicate over HTTP
- There are also several Flowable Applications (Flowable Modeler, Flowable Admin, Flowable IDM and Flowable Task) that offer out-of-the-box example UIs for working with processes and tasks.
- The first thing we need to do is to instantiate a `ProcessEngine` instance. This is a thread-safe object that you typically have to instantiate only once in an application
- A `ProcessEngine` is created from a `ProcessEngineConfiguration` instance, which allows you to configure and tweak the settings for the process engine.
- Often, the `ProcessEngineConfiguration` is created using a configuration XML file, but (as we do here) you can also create it programmatically. The minimum configuration a `ProcessEngineConfiguration` needs is a JDBC connection to a database:

```java
package org.flowable;

import org.flowable.engine.ProcessEngine;
import org.flowable.engine.ProcessEngineConfiguration;
import org.flowable.engine.impl.cfg.StandaloneProcessEngineConfiguration;

public class HolidayRequest {

    public static void main(String[] args) {
        ProcessEngineConfiguration cfg = new StandaloneProcessEngineConfiguration()
                //note that such a database does not survive a JVM restart
                .setJdbcUrl("jdbc:h2:mem:flowable;DB_CLOSE_DELAY=-1")
                .setJdbcUsername("sa")
                .setJdbcPassword("")
                .setJdbcDriver("org.h2.Driver")
                .setDatabaseSchemaUpdate(ProcessEngineConfiguration.DB_SCHEMA_UPDATE_TRUE);

        ProcessEngine processEngine = cfg.buildProcessEngine();
    }

}
```

- In the code above, on line 10, a standalone configuration object is created. The 'standalone' here refers to the fact that the engine is created and used completely by itself (and not, for example, in a Spring environment, where you’d use the `SpringProcessEngineConfiguration` class instead)
- Flowable uses `SLF4J` as its logging framework internally
- Log4j needs a properties file for configuration. Add a log4j.properties file to the src/main/resources folder with the following content:

```properties
log4j.rootLogger=DEBUG, CA
log4j.appender.CA=org.apache.log4j.ConsoleAppender
log4j.appender.CA.layout=org.apache.log4j.PatternLayout
log4j.appender.CA.layout.ConversionPattern=%d{hh:mm:ss,SSS} [%t] %-5p %c %x - %m%n
```

## Deploying a process definition


## CMMN User Guide

## Event Registry User Guide

## DMN User Guide

## Applications Guide

## Additional resources
- 