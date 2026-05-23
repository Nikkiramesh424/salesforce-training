# Day 9 – Component Communication and Aura Basics
---

# 1. Introduction

Today’s learning focused on communication between Lightning Web Components, Aura component basics, Visualforce fundamentals, and modular enterprise application architecture.

The concepts covered how frontend components exchange information, how reusable systems are designed, and how Salesforce evolved from Visualforce and Aura toward Lightning Web Components.

---

# 2. Communication Between Components

Component communication is important in enterprise applications because different UI modules must share data and interact with each other.

There are mainly three communication types:

- Child to Parent
- Parent to Child
- Communication between unrelated components

This architecture improves modularity and maintainability.

---

# 3. Child-to-Parent Communication

A child component can communicate with its parent component using custom events.

Example:
- Controls component sends an event
- Parent component receives the event
- Parent updates UI or business logic

This method is widely used in event-driven UI systems.

---

# 4. Event-Based Architecture

Events allow components to communicate without tightly coupling modules together.

Benefits:
- reusable architecture
- loose coupling
- scalability
- easier debugging
- cleaner application structure

---

# 5. Data Flow in Enterprise Applications

## Example: Student Registration Workflow

Student UI Form
↓
Validation Rules
↓
Flow Automation
↓
Apex Business Logic
↓
Database Storage
↓
Notification Service

Enterprise systems separate frontend interaction from backend processing to improve security and maintainability.

---

# 6. Dashboard Component Architecture

## Student Dashboard

Components:
- Header Component
- Student Profile Component
- Attendance Component
- Notifications Component
- Course Component

---

## Faculty Dashboard

Components:
- Faculty Profile
- Student Records
- Attendance Update
- Notifications
- Reports

---

## Admin Dashboard

Components:
- User Management
- Analytics
- Reports
- Course Management
- Monitoring System

---

# 7. Aura Components

Aura Components are an older Salesforce UI framework.

Aura architecture uses:
- Components
- Controllers
- Helpers
- Apex Controllers

Aura introduced component-based development before Lightning Web Components.

---

# 8. Visualforce Basics

Visualforce is a framework used to create custom Salesforce pages using Apex and HTML-like syntax.

Features:
- server-side rendering
- Apex integration
- dynamic UI generation
- Salesforce data access

Visualforce was widely used before Lightning Web Components.

---

# 9. Aura vs Lightning Web Components

| Aura Components | Lightning Web Components |
|-----------------|--------------------------|
| Older framework | Modern framework |
| More complex | Lightweight |
| Slower rendering | Faster rendering |
| Custom framework model | Uses modern web standards |
| Higher complexity | Easier maintenance |

Salesforce now recommends Lightning Web Components for modern application development.

---

# 10. Importance of Modular Architecture

Enterprise systems use modular architecture because it:
- improves scalability
- supports reusable components
- simplifies maintenance
- improves team collaboration
- reduces duplicate logic

Modular systems are easier to manage and expand.

---

# 11. Security Awareness

Modern enterprise applications must protect:
- user information
- business records
- authentication data
- confidential operations

Secure frontend and backend separation helps reduce security vulnerabilities.

---

# 12. Reflection

Today I learned how Salesforce applications use component communication and event-driven architecture to create scalable enterprise systems. I also understood the evolution from Visualforce and Aura to Lightning Web Components and the importance of reusable modular UI design.

---

# 13. What I Learned

- Component communication patterns
- Child-to-parent communication
- Event-driven architecture
- Aura component basics
- Visualforce basics
- Enterprise modular architecture
- Frontend and backend separation

---

# 14. Conclusion

Day 9 helped me understand how enterprise Salesforce applications are designed using reusable component architecture, communication patterns, and modular frontend systems. It also introduced legacy technologies like Aura and Visualforce and how Salesforce evolved toward Lightning Web Components.

---

# Screenshots

Screenshots of completed LWC communication modules, Aura components, Visualforce pages, Lightning App Builder pages, VS Code setup, Event Comms project, and Trailhead progress are included in the screenshots folder.
