# Day 10 – Mini Project: Enterprise System Design using Salesforce

## Date
23 May 2026

---

# System Overview

The mini project demonstrates an enterprise-level student management system built using Salesforce concepts. The system integrates frontend UI, backend business logic, CRM concepts, automation, and event-driven communication.

The application is designed using modular architecture to improve scalability, maintainability, and reusable development.

Main modules:
- Student Management
- Faculty Management
- Course Registration
- Attendance Monitoring
- Notifications System

---

# CRM Concepts

The CRM system contains the following entities:

- Student
- Faculty
- Course
- Department
- Registration

The CRM architecture manages relationships between users, courses, and departments while automating workflows and maintaining business records.

CRM helps:
- organize student data
- manage faculty records
- automate registration
- track attendance
- improve communication

---

# Data Model

## Relationships

Department
↓
Course
↓
Student Registration

### Relationship Structure

- One Department → Many Courses
- One Course → Many Students
- One Faculty → Multiple Courses
- One Student → Multiple Registrations

---

# Objects and Fields

## Student Object
- Student Name
- Student ID
- Email
- Phone Number
- Attendance Percentage

## Course Object
- Course Name
- Course Code
- Total Seats
- Available Seats

## Faculty Object
- Faculty Name
- Department
- Email

---

# Validation Rules

Validation rules are used to maintain data integrity.

Examples:
- Email field cannot be blank
- Attendance cannot exceed 100%
- Phone number must contain valid digits
- Registration blocked when seats are full

Example formula:

Attendance > 100

Example formula:

Available_Seats < 0

Validation rules prevent invalid or inconsistent records from entering the system.

---

# Flows

Salesforce Flows automate repetitive business processes.

Implemented flow examples:
- Student registration confirmation
- Attendance warning notification
- Welcome email automation
- Course full notification

Flow automation reduces manual work and improves operational efficiency.

---

# Apex Logic

Apex is used for advanced backend processing.

Implemented concepts:
- Eligibility checking
- Bulk student operations
- Attendance calculations
- Course registration processing

Example backend operations:
- verify seat availability
- calculate attendance percentage
- process student enrollment

Apex handles complex enterprise business logic.

---

# UI Screens

## Student Dashboard
Features:
- Profile information
- Registered courses
- Attendance details
- Notifications

## Faculty Dashboard
Features:
- Student list
- Attendance management
- Course updates
- Reports

## Registration Screen
Features:
- Course selection
- Validation checks
- Registration confirmation

The UI was designed using reusable Lightning Web Components.

---

# Complete Data Flow

Student clicks Register
↓
Lightning Web Component UI
↓
Validation Rules verify input
↓
Flow sends confirmation
↓
Apex processes registration
↓
Database stores records
↓
Trigger updates notifications
↓
Faculty and student receive updates

This workflow demonstrates complete frontend-to-backend integration.

---

# Reflection

This mini project helped me understand how enterprise Salesforce applications integrate frontend UI, backend logic, CRM concepts, automation, and reusable component architecture into a single scalable system.

I learned how:
- modular architecture improves maintainability
- event-driven systems improve communication
- flows automate repetitive tasks
- Apex handles complex logic
- Lightning Web Components create reusable frontend systems

The project also demonstrated how enterprise systems coordinate multiple services together for real-world business operations.

---

# Revision Questions

1. Why do enterprise systems need modular architecture?

Enterprise systems use modular architecture to improve scalability, maintenance, reusability, and team collaboration.

---

2. Why are relationships important?

Relationships connect business records together and help organize enterprise data efficiently.

---

3. Why are Flows insufficient for some cases?

Flows are limited for complex business logic, bulk operations, and advanced backend processing.

---

4. Why do systems need event-driven behavior?

Event-driven systems support real-time communication between components and improve responsiveness.

---

5. Why is UI/backend separation important?

Separating frontend and backend improves maintainability, security, scalability, and modular development.

---

6. Why do enterprise systems require testing?

Testing helps prevent bugs, security issues, and performance failures in large-scale applications.

---

7. Why is reusable UI architecture powerful?

Reusable UI components reduce duplicate code and improve consistency across applications.

---

8. What problems happen when systems scale?

Large systems may face:
- slow performance
- database overload
- concurrency issues
- notification delays
- security risks

---

9. Why should automation be designed carefully?

Incorrect automation can create infinite loops, duplicate records, or performance issues.

---

10. How do all Salesforce concepts integrate together?

Salesforce integrates:
- frontend UI
- backend Apex logic
- CRM database
- Flows
- Validation Rules
- Events
- Automation

to create scalable enterprise business applications.

---

# Conclusion

Day 10 provided understanding of enterprise system architecture using Salesforce technologies including Lightning Web Components, Apex, CRM concepts, Flows, validation rules, automation, and modular frontend systems.

The mini project demonstrated how modern enterprise applications combine frontend communication, backend logic, and reusable architecture to build scalable business systems.

---

# Screenshots

Screenshots of completed modules, Event Comms application, Lightning Web Components, Apex classes, Visualforce pages, Lightning App Builder pages, deployment steps, Trailhead progress, and VS Code setup are included in the screenshots folder.
