KPRC Healthcare CRM
📌 Overview

KPRC Healthcare CRM is a database-driven clinic management system built using Alpha Anywhere. The platform is designed to manage patient records, appointment scheduling, treatment history, and billing operations with a structured relational database architecture.

🚀 Key Features

Patient Registration & Profile Management

Appointment Scheduling System

Doctor/Therapist Availability Tracking

Treatment & Session Record Management

Billing & Payment Tracking

Structured Data Storage with Relational Database

🛠 Tech Stack

Platform: Alpha Anywhere

Database: (MySQL / MariaDB – update as per your setup)

Architecture: Relational Database Model

Backend Logic: Server-side scripting (Alpha)

🗄 Database Design

The system follows normalized relational schema design.

Core Tables:

patients

doctors

appointments

treatments

payments

Relationships:

One patient → Many appointments

One doctor → Many appointments

One appointment → One treatment record

One appointment → One payment entry

Indexes applied on:

appointment_date

patient_id

doctor_id

📊 Data Engineering Focus

Structured relational schema (3NF)

Foreign key constraints

Indexed appointment scheduling

Query-ready dataset for analytics

Designed for scalability and reporting

📈 Sample Analytics Use Cases

Monthly appointment trends

Revenue per doctor

Repeat patient analysis

Peak booking hour identification

🔮 Future Enhancements

Dashboard with appointment analytics

ETL pipeline for reporting

Automated reminder system

Role-based access control

👨‍💻 Author

Sourabh Rathore
Data Engineering | SQL | Database Design | ETL | Scalable Data Systems
