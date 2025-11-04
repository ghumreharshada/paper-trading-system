# paper-trading-system
Simulated trading backend using Java, Spring Boot, and MySQL. Supports virtual order placement, portfolio management, and trade execution.
# 🧠 Paper Trading System

## 📘 Overview
Paper Trading System is a **simulated trading backend** built using **Java, Spring Boot, and MySQL**.  
It allows users to place **virtual BUY/SELL orders**, track order status, and maintain a portfolio just like a real trading platform — but without using real money.

---

## ⚙️ Tech Stack
- Java 17  
- Spring Boot 3  
- Spring Data JPA (Hibernate)  
- MySQL  
- Postman (for API testing)  
- Maven  

---

## 🎯 Features
✅ Register new users  
✅ Add trading instruments (stocks, crypto, etc.)  
✅ Place BUY/SELL orders (Market & Limit)  
✅ View order history and status  
✅ Maintain user portfolios  
✅ Simulate market prices for paper trading  

---

## 🧩 Architecture (Simplified)
Frontend (Postman / UI)
↓
Spring Boot REST APIs
↓
Service Layer (Business Logic)
↓
MySQL Database (Persistence)
