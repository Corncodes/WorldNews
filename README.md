# WorldNews

A Django project for displaying news organized by region. Currently at the skeleton stage.

**Status:** Early. Project and app scaffolded, nothing implemented yet.

---

## Tech Stack

- Python / Django
- SQLite (default Django DB)

---

## Structure

- `usa/` — Django app for US news (scaffolded, models and views empty)

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
- Connect a news API (NewsAPI is the target)
- Build views and templates
- Expand to other regions
