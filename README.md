# Courier Management System (CMS)

* [Overview](#overview)
* [Project Structure](#project-structure)
* [Core Features by Role](#fCore-Features-by-Role)
* [Technical Specifications](#Technical-Specifications)
* [Project Lifecycle](#Project-Lifecycle)

## Overview
The Courier Management System (CMS) automates and streamlines logistics and delivery operations[cite: 276]. [cite_start]It connects customers, courier staff, delivery personnel, and super admins into a single, cohesive platform for end-to-end parcel management.

## Project Structure

```text
│   README.md
├───1. Context
│       context.png
│       context.svg
├───2. DFD
│       dfd level 0.png
│       dfd level 0.svg
├───3. Use-case
│   │   Use-case diagram.png
│   │   Use-case diagram.svg
│   └───Use-case analysis
│       ├───courir admin
│       │       courir admin.png
│       │       courir admin.svg
│       │       Generate Documents.pdf
│       │       login.pdf
│       │       Search Shipment.pdf
│       ├───customer
│       │       Book Shipment.pdf
│       │       customer.png
│       │       customer.svg
│       │       login.pdf
│       │       Pay Shipping Bills.pdf
│       │       Track Parcel.pdf
│       ├───delivery
│       │       COD.pdf
│       │       delivery.png
│       │       delivery.svg
│       │       login.pdf
│       │       POD.pdf
│       │       Update Delivery.pdf
│       │       View Shipments.pdf
│       └───super admin
│               login.pdf
│               Manage Staff.pdf
│               Reports.pdf
│               super admin.png
│               super admin.svg
│               Update Rates.pdf
├───4. Activity
│       Activity.png
│       Activity.svg
├───5. SSD
│   │   SSD diagram.png
│   │   SSD diagram.svg
│   ├───SSD diagram 1
│   │       SSD diagram 1.png
│   │       SSD diagram 1.svg
│   ├───SSD diagram 2
│   │       SSD diagram 2.png
│   │       SSD diagram 2.svg
│   ├───SSD diagram 3
│   │       SSD diagram 3.png
│   │       SSD diagram 3.svg
│   └───SSD diagram 4
│           SSD diagram 4.png
│           SSD diagram 4.svg
├───6. SD
│   │   Master_Courier_Management.png
│   ├───SD diagram 1 - Login Sequence
│   │       SD diagram 1 - Login Sequence.png
│   │       SD diagram 1 - Login Sequence.svg
│   ├───SD diagram3 - Super Admin
│   │       SD diagram3 - Super Admin.png
│   │       SD diagram3 - Super Admin.svg
│   └───SD diagrams 2 - Courier Admin - Search & Update
│           SD diagrams 2 - Courier Admin - Search & Update .png
│           SD diagrams 2 - Courier Admin - Search & Update .svg
└───7. Class
        Class Diagram.png
        Class Diagram.svg
```
## Core Features by Role

* **Customers:** Book shipments, calculate rates, make secure payments, and track parcels in real-time via GPS.
* **Courier Admin:** Search shipments, update transit statuses/locations, and generate official shipping manifests.
* **Delivery Personnel:** View assigned tasks, update live delivery statuses, collect Cash on Delivery (COD), and capture Proof of Delivery (POD).
* **Super Admin:** Oversee global operations, manage staff and branches, configure service rates, and generate analytical reports.

## Technical Specifications

* **Tech Stack:** Developed using PHP and MySQL with a modular architecture.
* **Performance:** 24/7 availability with <3 second response times for tracking and GPS mapping.
* **Security:** Implements BCrypt password hashing and Role-Based Access Control (RBAC).
* **Deployment:** Cross-platform compatible (Windows, Linux, macOS) and deployable on standard server environments (WAMP, XAMPP, Apache2).

## Project Lifecycle

The system was developed through four key phases:
1. **Requirement Gathering:** Defined logistical scope and user needs across all roles.
2. **System Design:** Created UI mockups, logic flows, and database schemas.
3. **Implementation:** Coded frontend interfaces and backend automation for rates and GPS.
4. **Documentation:** Compiled comprehensive records detailing the system's technical implementation and use cases.
