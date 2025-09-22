# FastAPI Task Manager

Mini Task Manager API using **FastAPI + SQLite**.

## Overview
This is a small project demonstrating:
- FastAPI CRUD APIs
- SQLAlchemy ORM with SQLite
- Pydantic for data validation

## Features
- Create a task
- List all tasks
- Mark task as completed

## Installation / Run Locally
```bash
git clone https://github.com/santhoshini-dev/santhoshini-develop.git
cd santhoshini-develop
python -m venv venv
# Activate virtual environment:
# Windows PowerShell: venv\Scripts\Activate.ps1
# Windows CMD: venv\Scripts\activate
# Mac/Linux: source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
