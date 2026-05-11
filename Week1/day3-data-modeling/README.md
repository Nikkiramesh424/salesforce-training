# Day 3 - Data Modeling and Validation

## Date
11 May 2026

---

## Modules Completed
- Data Modeling
- Formulas and Validations

---

## What is Data Modeling?

Data modeling is the process of organizing and managing data using objects, fields, records, and relationships in Salesforce.

It helps companies store structured data properly instead of using spreadsheets.

---

## Important Concepts Learned

### Object
An object stores information in Salesforce.

Examples:
- Account
- Contact
- Opportunity
- Property

---

### Record
A record is a single entry inside an object.

Example:
One student record inside the Student object.

---

### Field
Fields store specific information.

Examples:
- Name
- Email
- Phone Number
- Address

---

### Relationships
Relationships connect objects together.

Examples:
- Lookup Relationship
- Master-Detail Relationship

---

## Formula Fields

Formula fields automatically calculate values.

Example:
Days Remaining field in Contract object.

---

## Validation Rules

Validation rules prevent users from entering incorrect data.

Example:
ZIP code validation between Contact and Account.

---

## Roll-Up Summary Fields

Roll-up summary fields calculate values from related records.

Example:
Total Expected Revenue from Opportunities.

---

## College Management System Example

### Objects
- Student
- Faculty
- Course
- Department

### Relationships
- One department has many faculty
- One department has many courses
- One course has many students

### Validation Examples
- Student email cannot be blank
- Course seats cannot exceed limit

---

## What I Learned

### Objects, Fields and Records

I learned that objects are used to store data in Salesforce. Fields store specific information like name, email, or phone number. Records are individual entries inside an object.

Example:
Student object can contain multiple student records.

---

### Standard vs Custom Objects

I understood that standard objects are already available in Salesforce like Account, Contact, and Opportunity.

Custom objects are created based on business needs such as Student, Property, or Course.

---

### Relationships in Salesforce

I learned how relationships connect objects together.

I understood:

* Lookup Relationship
* Master-Detail Relationship

Relationships help organize data properly in real systems.

Example:
One department can contain many courses and faculty members.

---

### Formula Fields

I learned that formula fields automatically calculate values without manual work.

Examples:

* Percentage calculation
* Remaining seats
* Days remaining

Formula fields help reduce repetitive calculations.

---

### Validation Rules

I understood that validation rules prevent users from entering wrong or incomplete data.

Examples:

* Email cannot be empty
* Age cannot be negative
* ZIP codes must match

Validation rules help maintain correct and consistent data.

---

### Structured Data in Enterprise Systems

I learned why companies prefer structured data instead of random spreadsheets.

Structured data:

* avoids duplicate data
* improves consistency
* helps maintain relationships
* makes reporting easier

---

### Metadata and No-Code Logic

I understood that Salesforce is a metadata-driven platform where many business processes can be created using clicks instead of coding.

This helps companies build applications faster and manage business logic easily.

---

## Screenshots
Screenshots of completed modules and hands-on challenges are added in the screenshots folder.
