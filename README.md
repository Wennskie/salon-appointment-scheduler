# 💇 Salon Appointment Scheduler

A **PostgreSQL relational database & Interactive Bash scripting project** completed as part of the **freeCodeCamp Relational Database Certification**.

## 📚 About

This project builds an interactive terminal application for managing salon bookings and customer appointments. It handles database creation, relational data mapping, and real-time user input via Bash scripting, including:

* 💇 **Services**: Storing available salon services and prices
* 👤 **Customers**: Managing customer profiles with unique phone number identification
* 📅 **Appointments**: Scheduling appointments linked via foreign keys to customers and services
* 🔁 **Interactive CLI**: Re-prompting invalid inputs and handling both new and returning customer workflows dynamically

## 🛠️ Technologies

* **PostgreSQL** (Relational Database)
* **Bash / Shell Scripting** (CLI Application Logic)
* **SQL** (Data Manipulation & Foreign Key Constraints)

## 📁 Project Files

| File | Description |
| --- | --- |
| `salon.sql` | PostgreSQL database dump containing the complete schema, tables, and seed data |
| `salon.sh` | Executable Bash script handling the interactive salon booking workflow |

## 🚀 Usage

1. Make sure the script file has executable permissions:
```bash
chmod +x salon.sh
