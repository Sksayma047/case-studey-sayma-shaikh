Backend Case Study – Inventory Management System

Overview

This repository contains my solution for a backend engineering case study focused on debugging, database design, and API implementation for an inventory management system.

The solution demonstrates structured problem-solving, clear reasoning for design decisions, and handling of real-world edge cases.


---

Contents

Part 1: Code Review & Debugging

Identified technical and business logic issues in an existing product creation API

Explained production impact of each issue

Provided a corrected, production-ready implementation

Emphasized transactions, validation, and data integrity


Part 2: Database Design

Designed a normalized relational schema

Supported multiple companies, warehouses, and suppliers

Handled multi-warehouse inventory and product bundles

Included inventory change tracking and scalability considerations

Listed missing requirements and clarification questions


Part 3: API Implementation – Low Stock Alerts

Implemented an API to return low-stock alerts per company

Applied product-type-based thresholds

Considered recent sales activity

Handled multiple warehouses per company

Included supplier details for reordering

Covered edge cases and performance considerations



---

Assumptions

Inventory is tracked per product and per warehouse

SKUs are unique across the platform

Prices use decimal precision

Low-stock alerts consider recent sales activity

Supplier information may be optional


All assumptions are documented within the solution.


---

Technology (Conceptual)

Python (Flask)

SQLAlchemy

Relational Database (MySQL / PostgreSQL)

REST APIs



---

Notes

This repository focuses on design, reasoning, and implementation logic rather than deployment or UI.


---

Author

Sayma Shaikh# case-studey-sayma-shaikh
