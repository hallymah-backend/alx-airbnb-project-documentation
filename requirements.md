# Backend Requirements – Airbnb Booking System

---

## 1. User Authentication

### Description
Handles user registration and login.

### API Endpoints
- **POST /api/auth/register** – Register a new user  
- **POST /api/auth/login** – Authenticate user

### Input / Output
**Register Input**
```json
{ "email": "user@example.com", "password": "Password123", "role": "guest" }
