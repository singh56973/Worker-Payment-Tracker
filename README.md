# 🏗️ Worker Payment Tracker — Cloud Edition

A cloud-based web application designed to help construction contractors digitally manage worker payment records and reduce dependency on traditional pen-and-paper bookkeeping.

## 📌 Problem Statement

At construction sites, contractors often maintain worker payment records manually using notebooks and paper registers.

This can make it difficult to:

- Track how much a worker has been paid
- Check payment history
- Calculate weekly or monthly payments
- Find a specific worker's records
- Maintain records over long periods
- Avoid losing or damaging paper records

To address this problem, I built a web-based Worker Payment Tracker that allows contractors to maintain payment records digitally and access them through the cloud.

---

## 🚀 Key Features

### 🔐 User Authentication

- User registration and login
- Secure authentication using Firebase
- Individual user accounts
- Logout functionality

### 💰 Payment Management

Contractors can record individual worker payments with:

- Worker name
- Payment amount
- Payment date
- Payment time

Each payment is stored digitally in the cloud.

### 👷 Worker Summary

The application provides a worker-wise summary showing:

- Worker name
- Total amount paid
- Payment records

This makes it easier for contractors to understand how much has been paid to each worker.

### 📊 Payment Tracking

Payment history can be filtered based on different time periods:

- All payments
- Today's payments
- This week's payments
- This month's payments

This makes it easier to monitor recent payments and periodic expenses.

### 🔎 Worker Search

Contractors can search for a worker by name and quickly find their payment-related information.

### 📥 CSV Export

Payment records can be exported as a CSV file for:

- Further analysis
- Offline record keeping
- Sharing
- Accounting purposes

### ☁️ Cloud Database

Payment records are stored using Firebase Realtime Database rather than only being stored locally in the browser.

This allows the application to function as a cloud-based record management system.

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript
- Firebase Authentication
- Firebase Realtime Database
- Netlify
- CSV Export

---

## 🏗️ Application Workflow

```text
User
 │
 ▼
Create Account / Login
 │
 ▼
Worker Payment Tracker
 │
 ├── Add Worker Payment
 │       ├── Worker Name
 │       ├── Amount
 │       ├── Date
 │       └── Time
 │
 ├── Worker Summary
 │
 ├── Payment History
 │       ├── All
 │       ├── Today
 │       ├── This Week
 │       └── This Month
 │
 ├── Search Worker
 │
 └── Export CSV
        │
        ▼
 Firebase Realtime Database
