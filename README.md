# Smartlibrary_Limkokwing_University
Smartlibrary system for Limkokwing University Sierra Leone

# Smart Library Management System

# Overview
A Python + PostgreSQL desktop system designed to digitise book lending,
membership management, reading clubs, and library analytics.

# Technologies
Python
PyQt5
psycopg2
PostgreSQL
Qt Designer

# 1. Setup Instructions

Create database:
    CREATE DATABASE SmartLibrary;

# Update connection settings in config.py
HOST = "localhost"
PORT = "5432"
DATABASE = "smartlibrary_Limkokwin_University"
USER = "postgres"
PASSWORD = "PEACElu2"

# 2. Install Dependencies
pip install -r requirements.txt

requirements.txt should include:
PyQt5==5.15.7
psycopg2==2.9.6

# 3. Run Database Migrations
Run the SQL file:
psql -U postgres -d SmartLibrary -f schema.sql

# 4. Launch Application
python main.py


# 5. Features
- Login system
- Add, update, and delete books
- Search books & authors
- Manage members
- Borrow / Return books
- Club management
- Interactive dashboard
- Admin settings & permissions
