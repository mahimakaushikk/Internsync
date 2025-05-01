# Internsync
Internsync is a role-based internship management platform built with Django, Tailwind CSS. It streamlines the internship process for students, TPOs ,companies, and admins through clean dashboards and an efficient workflow. A key feature includes allowing students to submit internship deferment requests directly to companies.

Features:-
Students: Browse internships, apply, track status, upload documents.
TPOs: Approve/defer applications, manage students, coordinate with companies.
Companies: Post internships, review applications, shortlist candidates.
Admin: Manage users, oversee platform activity, maintain records.

Tech Stack:-
Frontend: HTML, CSS, Tailwind CSS
Backend: Django, Django REST Framework
Database: SQLite (default), PostgreSQL/MySQL (optional)

Setup:-
1. Clone: git clone https://github.com/yourusername/internsync.git && cd internsync
2. Create venv: python -m venv venv && source venv/bin/activate (Windows: venv\Scripts\activate)
3. Install: pip install -r requirements.txt
4. Migrate: python manage.py migrate
5. Run: python manage.py runserver


