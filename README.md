# Django Vendor Management System

A Vendor Management System (VMS) built using Django and Django REST Framework. This system manages vendor profiles, tracks purchase orders, and calculates vendor performance metrics.

## Table of Contents

- [Features](#features)
- [Technical Requirements](#technical-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Features

1. **Vendor Profile Management:**
   - Create, retrieve, update, and delete vendor profiles.
   - Calculate and display vendor performance metrics.

2. **Purchase Order Tracking:**
   - Create, retrieve, update, and delete purchase orders.
   - Track delivery status, items, quantity, and other details.

3. **Vendor Performance Evaluation:**
   - Calculate performance metrics, including on-time delivery rate, quality rating average, average response time, and fulfillment rate.
   - Historical performance tracking for trend analysis.

## Technical Requirements

- Django (latest stable version)
- Django REST Framework (latest stable version)
- Token-based authentication
- PEP 8 compliant code
- Comprehensive data validations
- Django ORM for database interactions

## Installation

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    .\venv\Scripts\activate

   
2. Install dependencies:
   ```bash
    pip install -r requirements.txt

3. Run migrations:
    ```bash 
    python manage.py makemigrations
    python manage.py migrate
4. Run :
    ```bash 
    python manage.py runserver

## API 

    ```bash 
    http://127.0.0.1:8000/admin/
    http://127.0.0.1:8000/api/vendors/ 
    http://127.0.0.1:8000/api/vendors/<int:pk>/ 
    http://127.0.0.1:8000/api/purchase_orders/
    http://127.0.0.1:8000/api/purchase_orders/<int:pk>/ 
    http://127.0.0.1:8000/api/historical_performance/ 
    http://127.0.0.1:8000/api/vendors/<int:vendor_id>/performance/ 
    http://127.0.0.1:8000/api/purchase_orders/<int:pk>/acknowledge/ 



