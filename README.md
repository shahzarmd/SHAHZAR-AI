# NADRA Database Management System 🇵🇰

This is a NADRA-like (National Database & Registration Authority - Pakistan) database management system built as a web application. It allows administrative-level management of citizens, families, and criminal records using a relational database model. The system is built using **HTML**, **CSS**, **JavaScript** for the frontend, **PHP** for the backend, and **MySQL** as the database.

---

## 🌐 Features

- Citizen Registration with complete biodata
- CNIC generation and search
- Family linkage with proper relationships
- Criminal Record Management
- Search and filter citizens by various parameters (Name, CNIC, DOB, etc.)
- Admin login and session management
- Proper foreign key constraints for relational integrity
- Clean UI built with custom HTML/CSS/JS

---

## 🧱 Tech Stack

| Layer        | Technology       |
|--------------|------------------|
| Frontend     | HTML, CSS, JavaScript |
| Backend      | PHP              |
| Database     | MySQL            |

---

## 🗃️ Database Schema Overview

The database is designed with normalized relational tables such as:

- `citizens` – CNIC, Name, DOB, Gender, Address, etc.
- `families` – Family ID, Head CNIC, Relationship Mapping
- `criminal_records` – Crime ID, CNIC, Crime Type, Date, Status
- `admins` – Admin login credentials

✅ All tables are connected using **primary** and **foreign keys**.  
✅ Referential integrity is ensured.

---

## 🚀 How to Run Locally

### Prerequisites

- XAMPP / LAMP / WAMP stack installed
- MySQL enabled
- PHP 7.x or above

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/NADRA-database
