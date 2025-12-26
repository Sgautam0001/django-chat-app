# django-chat-app 💬 (Django Chat Application)

A simple chat application built with **Django** using templates and static assets.  
This project demonstrates basic chat UI + backend setup and can be extended with real-time features (Channels/WebSockets) if needed.

Repo: https://github.com/Sgautam0001/django-chat-app

---

## ✨ Features
- Django project structure with a dedicated chat app
- Template-based UI (`templates/`)
- Static assets (`static/`)
- SQLite database for local development

> Feature set depends on the code inside `chat/` and `ChatApp/`.

---

## 🧰 Tech Stack
- Python 3.x
- Django
- SQLite (default)
- HTML / CSS / JS (Django Templates)

---

## 📁 Project Structure
.
├── manage.py
├── requirements.txt
├── db.sqlite3
├── ChatApp/ # Project settings / urls / wsgi
├── chat/ # Main chat app (views, models, urls, etc.)
├── templates/ # HTML templates
└── static/ # CSS/JS/images

yaml
Copy code

---

## ✅ Prerequisites
- Python 3.9+ recommended
- pip

Check:
```bash
python --version
pip --version
🚀 Setup & Run (Local)
1) Clone the repo
bash
Copy code
git clone https://github.com/Sgautam0001/django-chat-app.git
cd django-chat-app
2) Create & activate virtual environment
macOS/Linux

bash
Copy code
python3 -m venv .venv
source .venv/bin/activate
Windows (PowerShell)

powershell
Copy code
py -m venv .venv
.\.venv\Scripts\Activate.ps1
3) Install dependencies
bash
Copy code
pip install --upgrade pip
pip install -r requirements.txt
4) Apply migrations
bash
Copy code
python manage.py makemigrations
python manage.py migrate
5) Create admin user (optional)
bash
Copy code
python manage.py createsuperuser
6) Run the server
bash
Copy code
python manage.py runserver
Open:

App: http://127.0.0.1:8000/

Admin: http://127.0.0.1:8000/admin/

🧪 Run Tests (if available)
bash
Copy code
python manage.py test
🖼️ Static & Media
Static files are in static/ and served automatically in development.

If you add uploads later, configure MEDIA_URL / MEDIA_ROOT in settings.

🛠️ Common Commands
bash
Copy code
python manage.py check
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
📌 Notes / Next Improvements
Add Django Channels + WebSockets for real-time chat

Add authentication for private rooms and user-to-user chat

Store chat messages in DB and add message history

👤 Author
Shivam Gautam
GitHub: https://github.com/Sgautam0001
