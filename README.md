<<<<<<< HEAD
# 🛡️ Buggy Bank – Secure FinTech Web App (Intentionally Vulnerable)

Buggy Bank is an intentionally vulnerable online banking and inventory management application built with Flask and PostgreSQL. This project is designed to demonstrate common web application security flaws in a controlled DevSecOps environment. Ideal for security testing, training, and CI/CD automation experiments.

---

## 🚀 Features

- User authentication system with admin and regular users
- Inventory item management
- Admin dashboard to manage users and records
- PostgreSQL database with SQLAlchemy ORM
- Fully containerized using Docker and Docker Compose
- Environment-based DB config with fallback
- Preconfigured admin account

---

## ❌ Known Vulnerabilities (for education only)

| Vulnerability Type       | Endpoint / Location            |
|--------------------------|--------------------------------|
| Hardcoded Secrets        | `app.py`                       |
| SQL Injection            | `/insecure_login`              |
| Command Injection        | `/ping`                        |
| Insecure Deserialization | `/load_profile`                |
| Broken Access Control    | `/vuln_update_item/<item_id>`  |
| Stored XSS               | `/vuln_add_item`               |

---

## 🧰 Tech Stack

- Python 3.11
- Flask
- PostgreSQL 15
- Docker & Docker Compose
- SQLAlchemy
- Flask-Bcrypt, Flask-Login
=======
# test-repo
>>>>>>> 75d24c92cdd489e2fb043aed1482c6b16ea67c7d
