# Day 12 – Employee Management REST API

## 📌 Project Overview

This project is part of **Project Nexelis – Intern-to-Engineer Bootcamp, Day 12**.

The objective is to build a basic **Employee Management REST API using FastAPI** and understand how backend APIs handle:

- API routes
- HTTP methods
- Request and response models
- Pydantic validation
- Path parameters
- HTTP status codes
- CRUD operations
- Automatic API documentation

The current implementation uses an **in-memory list** as temporary storage instead of a database.


## 🎯 Objective

Build a structured Employee Management API using **FastAPI and Pydantic** that supports basic CRUD operations:

Create Employee
      ↓
View Employees
      ↓
View Employee by ID
      ↓
Update Employee
      ↓
Delete Employee

## Validation Rules
name → 2 to 50 characters
email → Must be a valid email address
department → 2 to 50 characters
designation → 2 to 50 characters
salary → Must be greater than 0
is_active → Defaults to True