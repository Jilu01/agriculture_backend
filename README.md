# Agriculture Backend

This repository contains the Django backend for the agriculture data platform.

## Stack
- Python 3.12
- Django
- Django REST Framework
- SQLite (default)

## Setup

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Project structure

- `config/` – project settings and URL configuration
- `accounts/` – user and account-related logic
- `soil/`, `crops/`, `weather/`, `farms/`, `iot/`, `predictions/`, `recommendations/`, `chatbot/` – domain modules
