# django-hit137-2026-week2-practicals-v3

Installation and run instructions (Windows):

1. Create and activate virtual environment:

```
python -m venv .venv
.\\.venv\\Scripts\\Activate.ps1   # PowerShell
# or
.venv\\Scripts\\activate.bat      # cmd
```

2. Upgrade pip and install dependencies:

```
python -m pip install --upgrade pip
pip install -r requirements.txt
```

3. Initialize database and run server:

```
python manage.py migrate
python manage.py runserver
```

4. Open http://127.0.0.1:8000 in your browser.

(If `requirements.txt` is not present yet, run `pip install django` before `migrate`.)
