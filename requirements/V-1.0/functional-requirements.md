# Document Title: Functional Requirements Specification - VSMS
# Document ID: DOC-01-FR
# Version: 1.0
# Project: Vehicle Service Management System
# Author: Ram Ghimire
# Stakeholder: Product Owner (Sita Kumari)
# Reviewed By: Scrum Master (Hari Bahadur)
# Approved By: Instructor (Gaman Aryal)
# Created On: 2026-04-10
# Last Updated: 2026-04-15
# Status: Approved

---

## 1. System Overview & Scope
The Vehicle Service Management System (VSMS) is an integrated web platform designed to automate workshop operations, appointment scheduling, repair logging, spare parts tracking, digital billing, and revenue reporting.

---

## 2. Functional Requirements Breakdown

| Requirement ID | Module | User Story Ref. | Description | Priority |
| :--- | :--- | :--- | :--- | :--- |
| **FR-01** | Account | `US-01` | System shall allow customers to register an account using email and password. | High |
| **FR-02** | Vehicle | `US-01` | System shall allow customers to store vehicle VIN, license plate, and model details. | High |
| **FR-03** | Booking | `US-02` | System shall allow customers to schedule service appointment slots based on availability. | High |
| **FR-04** | Mechanic | `US-03` | System shall allow mechanics to update repair status (`Pending`, `In Progress`, `Completed`). | High |
| **FR-05** | Admin | `US-04` | System shall allow admins to create, read, update, and delete service types and costs. | Medium |
| **FR-06** | History | `US-05` | System shall allow customers to view complete past service history records. | High |
| **FR-07** | Inventory | `US-06` | System shall allow mechanics to assign spare parts to job sheets with quantity deduction. | Medium |
| **FR-08** | Invoicing | `US-07` | System shall calculate total parts + labor cost and auto-generate PDF invoices. | High |
| **FR-09** | Alerts | `US-08` | System shall trigger automated SMS/Email alerts when service status changes to Completed. | Low |
| **FR-10** | Feedback | `US-09` | System shall allow customers to rate completed services (1–5 stars) and write comments. | Medium |
| **FR-11** | Reporting | `US-10` | System shall generate daily and monthly total revenue reporting for administrators. | Low |
