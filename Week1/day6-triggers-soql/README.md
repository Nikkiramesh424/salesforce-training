# Day 6 – SOQL and Apex Triggers

## Date
14 May 2026

---

# 1. What is SOQL?

SOQL stands for Salesforce Object Query Language. It is used to retrieve data from Salesforce objects and records.

SOQL is similar to SQL but is specially designed for Salesforce data and relationships.

Using SOQL, developers can:
- retrieve records
- filter data
- access related objects
- perform queries efficiently

SOQL helps enterprise systems access and process required data quickly.

---

# 2. What is an Apex Trigger?

An Apex Trigger is a piece of Apex code that runs automatically when specific events happen in Salesforce objects.

Triggers help systems react automatically to actions like:
- insert
- update
- delete

Triggers are mainly used for implementing backend business logic and automation.

Example:
After student registration, automatically send a notification or create related records.

---

# 3. Difference Between Flow and Trigger

## Flow

Flow is a declarative automation tool that uses drag-and-drop components.

### Advantages
- No coding required
- Easy to develop
- Faster implementation
- Best for simple automation

### Limitations
- Limited for complex logic
- Difficult for advanced integrations

---

## Apex Trigger

Apex Trigger is programming-based automation using Apex code.

### Advantages
- Supports advanced logic
- Better flexibility
- Suitable for enterprise-level automation
- Useful for bulk processing

### Limitations
- Requires coding knowledge
- Needs testing and debugging

---

# Difference Between Before Trigger and After Trigger

## Before Trigger

Before Trigger runs before the record is saved into the database.

It is mainly used for:
- validations
- modifying field values
- checking conditions

Example:
Automatically copying billing address to shipping address before saving.

---

## After Trigger

After Trigger runs after the record is saved into the database.

It is mainly used for:
- creating related records
- sending notifications
- integrations
- updating related objects

Example:
Creating follow-up tasks after opportunity status becomes Closed Won.

---

# 4. Trigger Use Cases

## 1. Student Registration Confirmation

After a student record is inserted, automatically send a welcome email.

Trigger Event:
After Insert

---

## 2. Attendance Warning System

After attendance gets updated below 75%, automatically notify the student.

Trigger Event:
After Update

---

## 3. Course Capacity Notification

When course seats become full, automatically notify faculty members.

Trigger Event:
After Update

---

## 4. Automatic Fee Receipt Generation

After successful fee payment, automatically generate a receipt record.

Trigger Event:
After Insert

---

## 5. Student ID Auto Generation

Before saving student records, automatically generate student IDs.

Trigger Event:
Before Insert

---

# 5. Query Examples

## Example Queries

- Find all students in Course A
- Find all students with attendance below 75%
- Find all courses handled by Faculty X
- Find students who have pending fee payments
- Find courses with available seats
- Find all students registered this month

---

# 6. Reflection – Why Enterprise Systems React Automatically to Data Changes

Enterprise systems handle large amounts of data and business activities continuously.

Automatic reactions are important because they:
- reduce manual work
- improve speed
- increase accuracy
- provide real-time updates
- improve workflow management

Triggers and automation help systems respond immediately whenever important data changes occur.

---

# Reflective Questions

## Why do systems need triggers?

Triggers help systems react automatically to important events and automate repetitive processes.

---

## Difference between polling and event-driven systems?

Polling systems repeatedly check for updates continuously, while event-driven systems react automatically only when an event occurs.

---

## Why are database queries important?

Database queries help retrieve required data efficiently from large systems and support business operations.

---

## When should Flows be preferred over Triggers?

Flows should be preferred for simple automation that does not require complex programming logic.

---

## What problems happen if automation logic becomes too complex?

Complex automation becomes difficult to maintain, debug, and manage properly.

---

## Why should developers think carefully before automating actions?

Incorrect automation can create errors, duplicate actions, performance issues, and business workflow problems.

---

# What I Learned

Today I learned how Salesforce retrieves data using SOQL and how Apex Triggers automate actions automatically when records are inserted or updated. I understood the difference between Flows and Triggers, Before and After triggers, and how enterprise systems react intelligently to data changes.

---

# Conclusion

Day 6 helped me understand event-driven automation and data querying in Salesforce. I learned how SOQL retrieves records and how Apex Triggers help automate backend business processes in enterprise systems.

---

# Screenshots

Screenshots of completed modules, Apex trigger challenges, SOQL exercises, and Trailhead progress are included in the screenshots folder.
