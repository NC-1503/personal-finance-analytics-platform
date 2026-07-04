# Software Requirements Specification (SRS)

## 1. Project Overview

### 1.1 Project Name

Personal Finance Analytics Platform

### 1.2 Purpose

The Personal Finance Analytics Platform is a web-based application that helps users manage their personal finances by recording income, expenses, wallets, and budgets. The platform also provides data analytics and financial reports to help users understand their spending habits and make better financial decisions.

### 1.3 Scope

The system allows users to:

- Register and log in
- Manage wallets
- Manage categories
- Record income
- Record expenses
- Set monthly budgets
- View dashboards and reports
- Analyze financial data

### 1.4 Target Users

- Individual users who want to manage their personal finances.
- Administrators who manage the system.

---

## 2. Business Goals

The goal of this project is to build a modern financial management platform that not only records transactions but also transforms raw financial data into meaningful insights through analytics and reporting.

---

## 3. Functional Requirements

FR01 - User Registration

FR02 - User Login

FR03 - Wallet Management

FR04 - Category Management

FR05 - Income Management

FR06 - Expense Management

FR07 - Budget Management

FR08 - Dashboard

FR09 - Reports

FR10 - User Profile

---

## 4. Non-Functional Requirements

- RESTful API
- JWT Authentication
- PostgreSQL Database
- Dockerized Deployment
- Response time under 500ms
- Secure password hashing
- Logging and monitoring
- Clean Architecture

---

## 5. Technology Stack

Backend

- FastAPI

Frontend

- React

Database

- PostgreSQL

ORM

- SQLAlchemy

Data Pipeline

- Apache Airflow

Analytics

- Pandas

Container

- Docker

Version Control

- Git & GitHub

---

## 6. Out of Scope

- Online Banking Integration

- OCR Receipt Scanning

- AI Financial Advisor

- Cryptocurrency Trading

- Investment Recommendation

---

## 7. Future Enhancements

- Mobile Application

- AI Spending Prediction

- Goal Saving

- Export PDF Reports

- Email Notifications

- Multi-language Support