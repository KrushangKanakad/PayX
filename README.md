# 💳 PayX – Payment App DBMS

A complete **Database Management System (DBMS)** project designed for a digital payment platform, where users can manage bank accounts, make transactions, pay bills, subscribe to services, and earn rewards – all in one ecosystem.

---

## 🎯 Objective

To develop a fully normalized and scalable relational database that:
- Handles digital payments, banking, and bill services
- Tracks transactions, user activity, rewards, and services
- Maintains data integrity through well-defined relations and constraints
- Simulates real-world financial and utility workflows

---

## 📖 Project Overview

The **PayX Payment App** enables users to:
- Register and manage their profiles
- Link bank accounts and cards securely
- Send/receive payments via UPI
- Subscribe to mobile, broadband, OTT, travel, hotel, and donation services
- Pay bills and track due dates
- Earn discounts and cashback rewards based on usage

The backend database manages all user, service, and payment data while supporting core banking, communication, and reward functionalities.

---

## 🧱 Core Features

- ✅ Fully normalized schema (**up to BCNF**)
- ✅ 15+ relational tables with primary and foreign keys
- ✅ Composite keys for complex relationships
- ✅ Support for cascading updates and deletes
- ✅ Structured bill and service management
- ✅ Rewards, discounts, and cashback tracking
- ✅ Contact list and friend referrals
- ✅ Payment categorization and history logging

---

## 🔎 Key Functionalities

### 👤 **User & Profile Management**
- Stores personal info, mobile number, email, DOB, UPI ID
- Manages contact list with friend references

### 🏦 **Banking & Cards**
- Stores account info with balance, IFSC, account type
- Manages card details with cardholder name, type, CVV, expiry

### 💸 **Transaction System**
- Full log of each transaction: sender, receiver, amount, time, status
- Categories like recharge, bill, donation, travel, etc.

### 🎁 **Rewards & Discounts**
- Earn rewards based on transaction categories
- Discount %, cashback ranges, and validity are tracked

### 🧾 **Bills & Payments**
- Users can pay bills across services like broadband, mobile, OTT, etc.
- Due date, provider, and bill amount are stored per record

### 🌐 **Service Integration**
- Supports 6+ types of services:
  - 📱 Mobile recharge
  - 📶 Broadband internet
  - 📺 OTT subscriptions
  - 🏨 Hotel bookings
  - 🚌 Travel ticketing
  - ❤️ Donations

### 🗃️ **Service Provider Mapping**
- Each service is linked with a provider by city and state
- Enables location-based service differentiation

---

## 📂 Project Deliverables

- 📌 **ER Diagram** – Visual design of entities and their relationships
- 📌 **Relational Schema** – Logical schema with all attributes and keys
- 📌 **Functional Dependencies** – Clearly defined for each relation
- 📌 **Normalization** – All tables are normalized to **BCNF**
- 📌 **Candidate Keys** – Identified for every relation
- 📌 **DDL SQL Script** – Table creation (optional)
- 📌 **DML SQL Script** – Sample data insertion (optional)
- 📌 **Sample Queries** – To demonstrate system functionality (optional)

---

## 🧾 Technologies Used

- **Database**: PostgreSQL / MySQL
- **Query Language**: SQL (DDL, DML, Queries)
- **Design Tools**: dbdiagram.io / draw.io

---

## 🧠 Educational Value

This project demonstrates how **real-world fintech and utility platforms** operate on a structured relational model, ensuring:
- Data consistency through normalization
- Scalable multi-service integration
- Clean, efficient schema design

It’s ideal for academic DBMS courses, portfolio projects, and demonstrating backend data modeling skills.

---

> 🔐 Built with attention to **data integrity**, **entity relationship modeling**, and **real-life transaction flows**.
