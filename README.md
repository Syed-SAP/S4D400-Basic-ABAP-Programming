
# SAP S4D400 — Basic ABAP Programming

## Hands-on ABAP Cloud Development | Exercises 1–21

This repository documents my hands-on learning and implementation of the **SAP S4D400 — Basic ABAP Programming** course using the **SAP BTP, ABAP environment** and **ABAP Development Tools (ADT) in Eclipse**.

The repository contains my practical work across **21 exercises**, progressing from the ABAP development environment and basic ABAP programming to database access, CDS view entities, business objects, EML, and the ABAP RESTful Application Programming Model (RAP).

> **Course:** S4D400 — Basic ABAP Programming  
> **Course Version:** 2601  
> **Platform:** SAP BTP, ABAP environment  
> **Level:** Foundation  
> **Environment:** Eclipse / ABAP Development Tools (ADT)

---

## About This Repository

This is a **learning and practical implementation repository**, not a claim of professional SAP production development experience.

The purpose of this repository is to demonstrate:

- Practical ABAP programming experience
- Familiarity with ABAP Development Tools (ADT)
- ABAP Cloud development concepts
- Database access using ABAP SQL
- CDS view entities
- Internal tables and structured data
- Object-oriented ABAP fundamentals
- Business object concepts
- Entity Manipulation Language (EML)
- ABAP RESTful Application Programming Model (RAP)
- Behavior definitions and implementations
- Validations
- OData V4 UI services
- SAP Fiori Elements generated applications
- UI metadata and annotations
- Debugging and troubleshooting

The work was performed progressively, with later exercises building on objects and concepts introduced earlier in the course.

---

# Course Structure

The 21 exercises are organized into eight learning units.

| Unit | Topic | Exercises |
|---|---|---|
| Unit 1 | Getting Started | 1–3 |
| Unit 2 | Applying Basic Techniques and Concepts | 4–7 |
| Unit 3 | Working with Local Classes | 8–11 |
| Unit 4 | Reading Data from the Database | 12–13 |
| Unit 5 | Working with Structured Data Objects | 14 |
| Unit 6 | Working with Complex Internal Tables | 15 |
| Unit 7 | Implementing Database Updates Using Business Objects | 16–17 |
| Unit 8 | Describing the ABAP RESTful Application Programming Model | 18–21 |

---

# Exercises Completed

## Unit 1 — Getting Started

### Exercise 01 — Create an ABAP Cloud Project and Investigate ABAP Coding

**Topics covered:**

- Eclipse / ABAP Development Tools
- ABAP perspective
- ABAP Cloud Project
- Project Explorer
- Favorite Packages
- Navigating ABAP development objects
- Investigating existing SAP ABAP classes
- ABAP Language Help
- Source-code navigation

**Practical work:**

- Created and configured an ABAP Cloud project.
- Explored the `/DMO/FLIGHT` package.
- Investigated the `/DMO/CL_FLIGHT_LEGACY` class.
- Used ADT navigation and source-code inspection features.

---

### Exercise 02 — Create an ABAP Package

**Topics covered:**

- ABAP packages
- Superpackages
- Favorite Packages
- Software components
- Transport requests
- Development object organization

**Practical work:**

Created a personal development package for the course and organized the course development objects inside the package.

Example package structure:

```text
ZSTUDENTS
└── ZS4D400_##
````

The package was used as the development area for subsequent exercises.

---

### Exercise 03 — Create a "Hello World" Application

**Topics covered:**

* ABAP classes
* Class definitions
* Class implementations
* Methods
* Console output
* Activating and executing ABAP classes

**Practical work:**

Created and executed a simple ABAP application to understand the basic structure and execution flow of an ABAP class.

---

# Unit 2 — Applying Basic Techniques and Concepts

### Exercise 04 — Declare Variables and Process Data

**Topics covered:**

* ABAP data declarations
* Variables
* Data types
* Numeric calculations
* String templates
* Expressions
* Inline declarations

**Practical work:**

Implemented ABAP calculations and processed data using different variable types and expressions.

---

### Exercise 05 — Implement Conditional Branching

**Topics covered:**

* `IF`
* `CASE`
* Conditional logic
* Arithmetic operations
* Error handling
* Exceptions
* Division-by-zero handling

**Practical work:**

Implemented a calculation program supporting:

```text
+
-
*
/
```

and handled invalid operators and division-by-zero situations.

---

### Exercise 06 — Work with Simple Internal Tables

**Topics covered:**

* Internal tables
* Work areas
* `LOOP AT`
* Table processing
* Reading table data
* Adding and processing records

**Practical work:**

Worked with simple internal tables and processed flight-related data using loops and table operations.

---

### Exercise 07 — Debug ABAP Code

**Topics covered:**

* ABAP Debugger
* Breakpoints
* Debug sessions
* Stepping through code
* Variable inspection
* Runtime analysis

**Practical work:**

Used the Eclipse ABAP Debugger to execute ABAP code step-by-step and inspect variable values during runtime.

---

# Unit 3 — Working with Local Classes

### Exercise 08 — Define a Local Class

**Topics covered:**

* Object-oriented ABAP
* Local classes
* Class definitions
* Public and private sections
* Attributes

**Practical work:**

Created a local class and explored the structure of an ABAP class.

---

### Exercise 09 — Create and Manage Instances

**Topics covered:**

* Objects
* Instances
* `NEW`
* References
* Object creation

Example concept:

```abap
DATA(lo_car) = NEW lcl_car( ).
```

**Practical work:**

Created and managed object instances from local classes.

---

### Exercise 10 — Define and Call Methods

**Topics covered:**

* Methods
* Method parameters
* Returning values
* Method calls
* Object interaction

**Practical work:**

Defined methods and called them through object references.

---

### Exercise 11 — Use Private Attributes and a Constructor

**Topics covered:**

* Encapsulation
* Private attributes
* Constructors
* Initialization
* Object-oriented design

**Practical work:**

Implemented private attributes and constructor logic to initialize object state.

---

# Unit 4 — Reading Data from the Database

### Exercise 12 — Read Data from a Database Table

**Topics covered:**

* ABAP SQL
* Database tables
* `SELECT`
* `WHERE`
* Work areas
* Internal tables
* Database access

**Practical work:**

Read data from database tables using ABAP SQL and processed the returned data.

---

### Exercise 13 — Analyze and Use a CDS View Entity

**Topics covered:**

* CDS view entities
* CDS annotations
* Data modeling
* Associations
* Database abstraction
* Consumption of CDS data

**Practical work:**

Analyzed and used CDS view entities and explored how CDS provides a structured data model for ABAP applications.

---

# Unit 5 — Working with Structured Data Objects

### Exercise 14 — Use a Structured Data Object

**Topics covered:**

* Structures
* Structured data objects
* Components
* Data types
* Accessing structure fields

**Practical work:**

Created and processed structured data objects and worked with individual components.

---

# Unit 6 — Working with Complex Internal Tables

### Exercise 15 — Use a Complex Internal Table

**Topics covered:**

* Complex internal tables
* Structured line types
* Nested structures
* Table processing
* Advanced internal table concepts

**Practical work:**

Worked with complex internal table structures and processed structured datasets.

---

# Unit 7 — Implementing Database Updates Using Business Objects

### Exercise 16 — Analyze a Business Object

**Topics covered:**

* Business objects
* Transactional processing
* Business object structure
* Root entities
* Behavior concepts

**Practical work:**

Analyzed the structure and behavior of a business object and explored how business objects are used for transactional application development.

---

### Exercise 17 — Modify Data Using EML

**Topics covered:**

* Entity Manipulation Language (EML)
* Business object entities
* Reading entities
* Modifying entities
* Transactional behavior
* RAP concepts

**Practical work:**

Used EML to work with business object data and understand how transactional modifications are performed in the ABAP RESTful Application Programming Model.

---

# Unit 8 — ABAP RESTful Application Programming Model

## Exercise 18 — Copy a Database Table

**Topics covered:**

* Database tables
* RAP preparation
* Development objects
* Flight data model
* ABAP Cloud database development

**Practical work:**

Created the flight database table used by the following RAP exercises.

The table was populated with flight-related data and became the database foundation for the OData UI service.

---

## Exercise 19 — Generate and Preview an OData UI Service

**Topics covered:**

* RAP
* CDS projection
* Behavior definitions
* Service definitions
* Service bindings
* OData V4
* SAP Fiori Elements
* OData UI service preview

**Practical work:**

Generated the required RAP development objects and published an OData V4 UI service.

The generated Fiori Elements application was opened through the service binding preview.

The application provided:

* Flight list
* Object Page
* Create
* Delete
* Edit
* Flight Price
* Currency
* Plane Type
* Flight Date
* Airline ID
* Flight Number

This exercise established the UI foundation used by Exercises 20 and 21.

---

## Exercise 20 — Validate the Flight Price

**Topics covered:**

* RAP behavior definitions
* Validations
* Behavior implementations
* EML `READ ENTITIES`
* Transactional buffer
* `%tky`
* `%msg`
* `new_message`
* Error reporting
* Debugging RAP validations

**Practical implementation:**

Implemented a `validatePrice` validation.

The validation checks:

```abap
IF flight-Price <= 0.
```

Invalid values are rejected and an error message is reported.

The implementation uses:

```abap
READ ENTITIES OF ZR_09FLIGHT IN LOCAL MODE
```

and processes the returned flight data.

The validation creates an error message using:

```abap
new_message(
    id       = '/LRN/S4D400'
    number   = '101'
    severity = ms-error
)
```

### Debugging

A breakpoint was placed in the validation implementation and the Fiori Elements application was used to trigger the validation.

The ABAP Debugger was used to inspect the validation execution and the flight price value.

### Result

The validation correctly rejects:

```text
Price = 0
Price < 0
```

Positive prices are accepted.

---

# Exercise 21 — Adjust the User Interface

**Topics covered:**

* Fiori Elements
* UI annotations
* Metadata extensions
* Behavior projections
* Value help
* Read-only fields
* Selection fields
* UI field positioning
* OData UI service behavior

This was the final exercise completed in the course sequence.

---

## Task 1 — Analyze Value Help

The Currency field was inspected in the generated Fiori Elements application.

The value help was traced back to the CDS projection view.

Annotation used:

```abap
@Consumption.valueHelpDefinition
```

Value-help CDS view:

```text
I_CurrencyStdVH
```

Relevant definition:

```abap
@Consumption: {
  valueHelpDefinition: [ {
    EntityElement: 'Currency',
    EntityName: 'I_CurrencyStdVH',
    UseForValidation: true
  } ]
}
```

---

## Task 2 — Adjust Behavior

The behavior projection was changed so that the UI service does not expose standard Create and Delete operations.

```abap
// use create;
use update;
// use delete;
```

`PlaneTypeID` was also made read-only:

```abap
field ( readonly ) PlaneTypeID;
```

The behavior projection was activated successfully.

### Verified Result

* Create was removed from the UI.
* Delete was removed from the UI.
* Plane Type became read-only.
* Flight Price remained editable.

---

## Task 3 — Adjust UI Metadata

The metadata extension was modified to improve the Fiori Elements UI.

Administrative fields were hidden:

```abap
@UI.hidden: true
LocalCreatedBy;

@UI.hidden: true
LocalCreatedAt;

@UI.hidden: true
LocalLastChangedBy;

@UI.hidden: true
LocalLastChangedAt;

@UI.hidden: true
LastChangedAt;
```

Only the required business selection fields retained:

```abap
@UI.selectionField
```

These were:

```text
CarrierID
ConnectionID
```

The Object Page field sequence was also changed.

`PlaneTypeID` was positioned between:

```text
FlightDate
     ↓
PlaneTypeID
     ↓
Price
```

using:

```abap
@UI.identification: [ {
  position: 35
} ]
```

The metadata extension was activated with:

```text
0 errors
```

---

## Task 4 — Final Verification

The OData UI service preview was restarted and the resulting Fiori Elements application was tested.

### Report List Page

Verified:

* Create button removed
* Delete button removed
* Administrative fields hidden
* Only the intended business selection fields remained
* Flight data displayed correctly

### Object Page

Verified:

* Administrative fields hidden
* Plane Type appears after Flight Date
* Plane Type appears before Flight Price
* Delete operation removed

### Edit Mode

Verified:

```text
Plane Type → Read-only
Flight Price → Editable
```

This confirmed that the behavior projection and UI metadata changes were working as intended.

---

# Key ABAP Concepts Practiced

Throughout these 21 exercises, I worked with the following concepts:

### ABAP Fundamentals

* Variables
* Data types
* Expressions
* String templates
* Conditional statements
* Loops
* Internal tables
* Structures

### Object-Oriented ABAP

* Classes
* Objects
* Instances
* Methods
* Constructors
* Encapsulation
* Public and private sections

### Database Development

* ABAP SQL
* `SELECT`
* Database tables
* CDS view entities
* CDS annotations
* Associations

### Business Objects

* Business objects
* Entities
* Transactional processing
* EML
* Entity manipulation

### RAP

* Behavior definitions
* Behavior projections
* Behavior implementations
* Validations
* Draft-enabled business objects
* Transactional buffer
* `READ ENTITIES`
* `%tky`
* `%msg`

### SAP Fiori / OData

* OData V4
* Service definitions
* Service bindings
* Fiori Elements
* Metadata extensions
* UI annotations
* Value helps
* UI field positioning
* Read-only fields

### Debugging

* Breakpoints
* ABAP Debugger
* Runtime execution
* Variable inspection
* Debugging RAP validations

---

# Selected Technical Examples

## ABAP SQL

Example concept practiced:

```abap
SELECT *
  FROM some_database_table
  WHERE some_field = @lv_value
  INTO TABLE @DATA(lt_result).
```

The important concepts are:

```text
Database Table
      ↓
SELECT
      ↓
WHERE
      ↓
Internal Table
```

---

## Object Creation

```abap
DATA(lo_car) = NEW lcl_car( ).
```

This demonstrates the basic relationship between:

```text
Class
  ↓
Object / Instance
```

---

## RAP Entity Access

```abap
READ ENTITIES OF ZR_09FLIGHT IN LOCAL MODE
  ENTITY Flight
  FIELDS ( Price )
  WITH CORRESPONDING #( keys )
  RESULT DATA(flights).
```

This was used in the Exercise 20 validation implementation.

---

## RAP Validation

```abap
IF flight-Price <= 0.

  failed_record-%tky = flight-%tky.
  APPEND failed_record TO failed-flight.

  reported_record-%tky = flight-%tky.

  reported_record-%msg = new_message(
    id       = '/LRN/S4D400'
    number   = '101'
    severity = ms-error
  ).

  APPEND reported_record TO reported-flight.

ENDIF.
```

---

## RAP Behavior Projection

```abap
define behavior for ZC_09FLIGHT alias Flight
{
  field ( readonly ) PlaneTypeID;

  // use create;
  use update;
  // use delete;

  use action Edit;
  use action Activate;
  use action Discard;
  use action Resume;
  use action Prepare;
}
```

---

## UI Metadata

Example of UI positioning:

```abap
@UI.identification: [ {
  position: 35
} ]
@UI.lineItem: [ {
  position: 50
} ]
PlaneTypeID;
```

This resulted in the Object Page order:

```text
Flight Date
    ↓
Plane Type
    ↓
Flight Price
```

---

# Development Environment

The exercises were performed using:

```text
SAP BTP ABAP Environment
        +
Eclipse IDE
        +
ABAP Development Tools (ADT)
        +
OData V4
        +
SAP Fiori Elements
```

The RAP exercises used a flight scenario based on a custom flight database table and generated RAP/OData development objects.

---

# Repository Structure

The documentation is organized by exercise so that each exercise can be reviewed independently.

Suggested structure:

```text
S4D400-Basic-ABAP/
│
├── README.md
│
├── 01_Create-ABAP-Cloud-Project/
├── 02_Create-ABAP-Package/
├── 03_Hello-World/
├── 04_Declare-Variables-and-Process-Data/
├── 05_Conditional-Branching/
├── 06_Simple-Internal-Tables/
├── 07_Debug-ABAP-Code/
├── 08_Define-Local-Class/
├── 09_Create-and-Manage-Instances/
├── 10_Define-and-Call-Methods/
├── 11_Private-Attributes-and-Constructor/
├── 12_Read-Database-Table/
├── 13_CDS-View-Entity/
├── 14_Structured-Data-Object/
├── 15_Complex-Internal-Table/
├── 16_Analyze-Business-Object/
├── 17_EML/
├── 18_Copy-Database-Table/
├── 19_OData-UI-Service/
├── 20_Validate-Flight-Price/
└── 21_Adjust-User-Interface/
```

Each exercise folder can contain:

```text
README.md
screenshots/
code/
```

---

# Evidence and Documentation

The repository includes screenshots and documentation from the development environment where applicable.

Screenshots are used to demonstrate actual development and verification steps, including:

* Eclipse / ADT
* ABAP source code
* Project Explorer
* Behavior definitions
* Behavior implementations
* Metadata extensions
* Service bindings
* Fiori Elements preview
* Object Pages
* Debugger execution
* Validation errors
* UI changes

The screenshots are intended as **learning evidence and development documentation**, rather than as a substitute for the complete SAP course material.

---

# What I Learned

The most important progression from these exercises was understanding how the different layers of ABAP development connect.

```text
ABAP Language
      ↓
ABAP Classes
      ↓
ABAP SQL
      ↓
CDS Data Model
      ↓
Business Objects
      ↓
EML
      ↓
RAP Behavior
      ↓
OData V4 Service
      ↓
Fiori Elements UI
```

The final RAP exercises made the relationship between backend behavior and frontend behavior particularly clear.

For example:

```text
Behavior Projection
        ↓
field ( readonly ) PlaneTypeID
        ↓
Fiori Elements
        ↓
Plane Type cannot be edited
```

Similarly:

```text
Behavior Validation
        ↓
validatePrice
        ↓
Price <= 0
        ↓
RAP Error Message
        ↓
Fiori UI rejects the save
```

---

# Important Scope Note

This repository represents **course-based hands-on practice**.

Completing these exercises does not by itself mean that I have professional production SAP ABAP experience.

The purpose of this repository is to demonstrate that I have:

* Worked directly with ABAP Development Tools
* Written and executed ABAP code
* Used ABAP SQL
* Worked with CDS
* Practiced object-oriented ABAP
* Worked with business objects and EML
* Built and modified RAP artifacts
* Created an OData V4 UI service
* Worked with Fiori Elements
* Implemented RAP validation
* Used the ABAP Debugger
* Troubleshot activation and runtime issues
* Documented the development process

The repository should therefore be viewed as a **practical ABAP learning portfolio** and evidence of hands-on training.

---

# Course Completion

## S4D400 — Basic ABAP Programming

```text
Exercises completed: 21 / 21

Unit 1   ████████████████████  3 / 3
Unit 2   ████████████████████  4 / 4
Unit 3   ████████████████████  4 / 4
Unit 4   ████████████████████  2 / 2
Unit 5   ████████████████████  1 / 1
Unit 6   ████████████████████  1 / 1
Unit 7   ████████████████████  2 / 2
Unit 8   ████████████████████  4 / 4
```

**Status: Completed — Exercises 1–21**

---

## Next Step

This repository represents the foundation of my ABAP development learning.

The next stage is to move beyond guided course exercises and build **independent ABAP Cloud / RAP applications**, where the requirements, data model, behavior, validations, services, and UI are designed and implemented without following a step-by-step SAP exercise.

---

## Disclaimer

This repository contains personal learning notes, implementations, screenshots, and documentation created while working through SAP training material.

SAP, SAP S/4HANA, SAP BTP, ABAP, RAP, and SAP Fiori are trademarks or registered trademarks of SAP SE or its affiliates.

This repository is an independent learning portfolio and is not an official SAP repository.

```
