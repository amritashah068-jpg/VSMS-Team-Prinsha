# Document Title: UML Systems Architecture Specifications - VSMS
# Document ID: DOC-03-UML
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

## 1. Use Case Diagram Specification
* **Diagram ID:** `D-UC-01`
* **Actors:** Customer, Workshop Mechanic, System Administrator

```plantuml
@startuml
left to right direction
actor Customer
actor Mechanic
actor Administrator

rectangle "Vehicle Service Management System (VSMS)" {
    usecase "Register & Manage Profile" as UC1
    usecase "Book Service Appointment" as UC2
    usecase "View Repair Status" as UC3
    usecase "Update Repair Progress" as UC4
    usecase "Log Spare Parts & Labor" as UC5
    usecase "Manage Service Catalog" as UC6
    usecase "Generate Digital Invoice" as UC7
    usecase "View Revenue Reports" as UC8
}

Customer --> UC1
Customer --> UC2
Customer --> UC3

Mechanic --> UC4
Mechanic --> UC5

Administrator --> UC6
Administrator --> UC7
Administrator --> UC8
@enduml
