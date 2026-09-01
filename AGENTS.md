# AGENTS.md — django-file-captcha

## What this is
A Django CAPTCHA application with file-based storage backend support. Enhanced fork of django-simple-captcha.

## Stack
- Python (>=3.10)
- Django (>=5.0)
- Pillow
- django-ranged-response
- Hatchling (build)
- tox (testing)

## Build
```bash
pip install -e .
```

## Run
Install as a Django app, add `'captcha'` to `INSTALLED_APPS`, include `captcha.urls` in urls.py.

## Structure
- `captcha/` — Django app package (fields, storage backends, helpers, views)
- `testproject/` — test Django project
- `docs/` — documentation source
- `pyproject.toml` — build config

## Conventions
- No comments in code unless asked.
- Verify: `tox` (requires tox>=4.31, tox-uv>=1.23)
