# 💇 Salon Appointment Scheduler

<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-Database-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/SQL-Relational%20Database-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/Bash-Scripting-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/freeCodeCamp-Certification-0A0A23?style=for-the-badge&logo=freecodecamp&logoColor=white" alt="freeCodeCamp"/>
</p>

A PostgreSQL database project built for the **freeCodeCamp Relational Database Certification**.

The Salon Appointment Scheduler stores salon services, customer details, and appointment information in a relational database. It demonstrates table creation, primary and foreign keys, database constraints, and SQL operations using Bash scripting.<br>

## 🗂️ Database Structure

The database contains three related tables: `customers` stores customer information, `services` stores the salon services offered, and `appointments` records appointment details and links customers to their selected services.

| Table | Keys | Main Columns |
|---|---|---|
| `customers` | **PK:** `customer_id` · **Unique:** `phone` | `phone`, `name` |
| `services` | **PK:** `service_id` | `name` |
| `appointments` | **PK:** `appointment_id` · **FK:** `customer_id`, `service_id` | `customer_id`, `service_id`, `time` |

<br>

## 🛠️ Tools & Technologies

* **PostgreSQL** - relational database system
* **SQL** - database query and definition language
* **Bash** - scripting and automation
* **`psql`** - PostgreSQL command-line client
* **`pg_dump`** - PostgreSQL database backup tool

<br>

## 📚 Concepts Demonstrated

- Database and table creation
- Primary keys, foreign keys, and constraints
- Auto-incrementing IDs using PostgreSQL sequences
- SQL queries and relational database design
- Bash scripting and PostgreSQL integration
- Database backup and restoration

<br>

## 📂 Project Files

| File | Description |
|---|---|
| `salon.sh` | Bash script for displaying salon services and collecting customer and appointment details |
| `salon.sql` | PostgreSQL database dump containing the schema, data, constraints, sequences, and relationships |

<br>

<p align="center">
  <strong>💇 Salon Appointment Scheduler</strong> · Built with PostgreSQL, SQL & Bash
</p>
