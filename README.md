# Employee Onboarding System (ServiceNow)

##  Overview

This project is an automated **Employee Onboarding System** built using the ServiceNow Developer Program. It streamlines the onboarding process by replacing manual coordination with a structured workflow involving request creation, approvals, and task automation.

The system ensures that when a new employee joins, all necessary resources such as laptop allocation and ID card creation are handled efficiently with minimal human intervention.

---

## Problem Statement

In many organizations, onboarding a new employee involves multiple teams (HR, IT, Admin) and manual communication, leading to:

* Delays in resource allocation
* Lack of tracking and accountability
* Increased dependency on emails and follow-ups

This project solves these issues by introducing an automated workflow system.

---

## Solution

The system provides a **centralized service catalog request** where managers can initiate onboarding. Once submitted:

1. Request is created in the system
2. Approval is triggered for the manager
3. Upon approval:

   * IT team receives a task for laptop setup
   * Admin team receives a task for ID card creation
4. Progress is tracked in real-time

---

## Features

* 📋 Service Catalog-based request form
* 🔐 Manager approval workflow
* ⚙️ Automated task creation
* 👥 Role-based task assignment (IT & Admin)
* 📊 End-to-end tracking of onboarding requests

---

## Modules Used

* Service Catalog
* Flow Designer
* Incident & Task Management

---

## ⚙️ System Workflow

Manager → Raises Request → Approval → Task Creation → Completion Tracking

---

## 🖥️ Implementation Details

### 1. Catalog Item

* Created "Employee Onboarding" under Service Catalog
* Added variables:

  * Employee Name
  * Department
  * Laptop Requirement
  * Joining Date

### 2. Flow Designer

* Trigger: Catalog Item Request
* Approval: Manager approval step
* Actions:

  * Create IT task (Laptop Setup)
  * Create Admin task (ID Card Creation)

---

## Testing

* Submitted onboarding request via Service Catalog
* Verified:

  * Request creation
  * Approval flow
  * Task generation
  * Assignment to respective teams

---

## Future Enhancements

*  AI-based automatic request categorization
* SLA tracking and escalation
*  Email notifications integration
* Integration with external HR systems

---

## Key Learnings

* Hands-on experience with ServiceNow platform
* Workflow automation using Flow Designer
* Designing service catalog forms
* Understanding enterprise-level ITSM processes

---

## Conclusion

This project demonstrates how enterprise workflows can be automated using ServiceNow, improving efficiency, reducing manual effort, and ensuring smooth coordination between teams.
