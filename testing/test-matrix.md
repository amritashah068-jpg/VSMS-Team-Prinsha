# Document Title: Master Test Case Specification & Traceability Matrix - VSMS
# Document ID: DOC-04-TC
# Version: V-1.0
# Project: Vehicle Service Management System
# Author: Amrita Shah / Prinsha Kusiyait
# Stakeholder: Product Owner (Sita Kumari)
# Reviewed By: Scrum Master (Hari Bahadur)
# Approved By: Instructor (Gaman Aryal)
# Created On: 2026-04-10
# Last Updated: 2026-04-15
# Status: Approved

---

## 1. Test Execution Matrix

| Test Case ID | Requirement ID | User Story | Test Scenario | Execution Steps | Expected Result | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **TC-T-101-01** | `FR-01` | `US-01` | Customer Registration | Enter valid email & password, click Submit. | Account created; user redirected to dashboard. | **Pass** |
| **TC-T-102-01** | `FR-03` | `US-02` | Slot Reservation | Select vehicle, pick date/time slot, click Book. | Appointment status set to `Pending`. | **Pass** |
| **TC-T-103-01** | `FR-04` | `US-03` | Status Transition | Mechanic changes repair status to `In Progress`. | Status updates real-time in customer view. | **Pass** |
| **TC-T-106-01** | `FR-07` | `US-06` | Spare Parts Deduction | Assign 2 units of Brake Pads to job sheet. | Parts inventory deducts 2 units automatically. | **Pass** |
| **TC-T-107-01** | `FR-08` | `US-07` | Invoice Generation | Click "Generate Invoice" for completed job. | PDF invoice downloads with calculated total + tax. | **Pass** |

---

## 2. Requirements Traceability Matrix (RTM)

| Requirement ID | Module | User Story Ref. | Test Case Ref. | Verification Method |
| :--- | :--- | :--- | :--- | :--- |
| **FR-01** | Authentication | `US-01` | `TC-T-101-01` | Functional Testing |
| **FR-03** | Appointment | `US-02` | `TC-T-102-01` | Integration Testing |
| **FR-04** | Repair Management | `US-03` | `TC-T-103-01` | System Testing |
| **FR-07** | Inventory | `US-06` | `TC-T-106-01` | Unit & Integration Testing |
| **FR-08** | Invoicing | `US-07` | `TC-T-107-01` | System & Performance Testing |
