# OSON CRM Backend

Production-ready CRM backend system for product tracking, sales management, and analytics.

---

## 🚀 Overview

This project is a backend system built using FastAPI designed to manage products, generate QR codes, track sales, and handle seller workflows in a scalable way.

---

## ⚙️ Key Features

- Product management system
- QR code generation for each product or batch
- Seller transfer system (ownership transfer via QR scan)
- Sales tracking and history
- Analytics (daily, weekly, monthly statistics)
- Notification system for real-time updates

---

## 🧠 My Role

- Designed backend architecture
- Implemented core APIs and business logic
- Built QR-based product workflow system
- Designed database schema and optimized queries
- Handled deployment and backend maintenance

---

## 🏗️ Tech Stack

- Python
- FastAPI
- SQLAlchemy
- PostgreSQL
- Redis
- Docker
- NGINX
- Gunicorn

---

## 📡 API Examples

```http
POST /api/products/
GET /api/statistics/
POST /api/transfer/
```

---

## 🧩 Architecture

The system follows a modular architecture:

- API Layer (FastAPI)
- Service Layer (Business Logic)
- Repository Layer (Database Access)




## 📸 Screenshots

### Database Schema
![Database Schema](https://github.com/user-attachments/assets/d5d105da-e92c-4f9d-b269-db1c86ec0c66)

### Project Structure
![Architecture](https://github.com/user-attachments/assets/49fb3bd1-9fc0-4e28-b241-014a21144282)

## ⚡ Installation

```bash
git clone https://github.com/FayzulloBukhoriev/oson-crm-backend
cd oson-crm-backend

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

pip install -r requirements.txt

uvicorn app.main:app --reload


## 📌 Features in Progress

- Advanced analytics dashboard
- Notification improvements
- Performance optimization

```md
## 🔐 Notes

This is a production-based project. Some parts of the code are private due to business logic and security reasons.

## 👤 Author

Fayzullo Bukhoriev
