# Clinic Management System Database

![Clinic System Schema](https://private-us-east-1.manuscdn.com/sessionFile/Tkn5x9GBoVTryYvW4MEDut/sandbox/Ysyrud7bWObhX6mhhsVsBX-images_1782840218687_na1fn_L2hvbWUvdWJ1bnR1L2NsaW5pY19zeXN0ZW1fc2NoZW1h.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvVGtuNXg5R0JvVlRyeVl2VzRNRUR1dC9zYW5kYm94L1lzeXJ1ZDdiV09iaFg2bWhoc1ZzQlgtaW1hZ2VzXzE3ODI4NDAyMTg2ODdfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwyTnNhVzVwWTE5emVYTjBaVzFmYzJOb1pXMWgucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxNzk4NzYxNjAwfX19XX0_&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=o2w88pK0Rtx-t9fIVTjgzYUeVCxixz6kw-zdTGKn1CXlviClx6ttWT1niH-85tQ3qxwhkRwKzsJQDUKY74VcNMj1dFHoIaKgoGtoDz24yGdfX0BXJzClq2Vx0vvKdl5Ns9WUL4z5PI~NAtFCMuoHFOX6lmAkQ4J9jS3IwJMwbV36K3Xo1eGSZsws~z87q8OmVSAm1Qyd5rw6bHtx~SNlWE1gmXVE6DbiB6M2AsHgi9i8RkvAu6AzPzu6ECyl8o4~6yPDhjXnkeMetuGUTyvchxUJJZBLsGlU4xH0n~TMFMZ6UIpFxz2~jHpjWkvwB5rlbn2Iz8Egi4sWpw-X3VsuEA__)

## Overview
This repository contains the database schema and sample data for a **Clinic Management System**. The system is designed to manage the core operations of a healthcare facility, including patient registration, appointment scheduling, medical record keeping, and financial transactions (billing and payments).

The database is implemented in **MySQL** and follows a relational structure to ensure data integrity and efficient retrieval.

## Key Features
- **Patient Management**: Store comprehensive patient profiles, including personal details, contact information, and medical history.
- **Appointment Scheduling**: Track patient visits, assign healthcare staff, and manage appointment statuses (Scheduled, Completed, Cancelled).
- **Medical Records**: Maintain detailed records of diagnoses and treatments for every patient visit.
- **Staff Management**: Organize healthcare professionals and support staff by roles, specializations, and clinic locations.
- **Financial Module**: Handle billing for medical services and track patient payments with status monitoring (Pending, Paid, Overdue).
- **Multi-Clinic Support**: Support for multiple clinic centers within a single management framework.

## Database Schema
The database consists of the following core tables:
- `patients`: Personal and contact information for clinic patients.
- `staff`: Details of doctors, nurses, and other clinic personnel.
- `cliniccenter`: Information about the different clinic locations.
- `appointments`: Scheduling details connecting patients and staff.
- `medicalrecords`: Clinical data related to specific appointments.
- `billing`: Financial records generated from medical treatments.
- `payments`: Transaction history for settled bills.

## Getting Started
### Prerequisites
- MySQL Server (v8.0 or higher recommended)
- A database management tool (e.g., MySQL Workbench, phpMyAdmin)

### Installation
1. Create a new database:
   ```sql
   CREATE DATABASE `clinic_management_system`;
   ```
2. Import the SQL file:
   ```bash
   mysql -u yourusername -p clinic_management_system < Clinic_Managment_SystemDatabase.sql
   ```

## Usage
The provided SQL script includes both the table structures and sample data, allowing you to immediately begin testing queries or building an application interface on top of the schema.

## License
This project is open-source and available under the [MIT License](LICENSE).
