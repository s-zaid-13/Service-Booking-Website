# Flask Service Booking

A multi-role service booking web application built with Flask, allowing customers to book services, providers to manage orders, and admins to oversee the platform.

## Features
- User authentication with role-based access (Customer, Provider, Admin)
- Service listing and management
- Booking, order tracking, and cancellation
- Review and rating system
- Password reset via email
- Responsive UI with Bootstrap

## Tech Stack
- Flask
- SQLAlchemy & Flask-Migrate
- Flask-Login & WTForms
- Bootstrap & Custom CSS
- SQLite (development)

## Roles
- **Customer:** Book services, manage bookings, submit reviews  
- **Service Provider:** Manage services, accept and complete orders  
- **Admin:** Manage services, providers, and bookings  

## Project Structure
- `run.py` – Application entry point  
- `app/` – Models, routes, forms, templates, static files  
- `migrations/` – Database migrations (Alembic)

## Setup
```bash
pip install -r requirements.txt
python run.py
