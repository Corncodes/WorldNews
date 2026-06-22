# WorldNews

A Django project scaffolded for displaying news, currently at the project skeleton stage.

**Status:** Early — project and app created, no models or views implemented.

---

## Tech Stack

- Python / Django
- SQLite (default Django DB)

---

## Structure

- `usa/` — Django app scaffolded for US news (models and views empty)

---

## How to Run

```bash
python -m venv venv && source venv/bin/activate
pip install django
python manage.py migrate
python manage.py runserver
```

---

## Roadmap

- Define news article models
- Connect a news API (e.g., NewsAPI)
- Build views and templates
- Expand to other regions
