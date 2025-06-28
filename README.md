# 📈 Bluestock IPO Web App

A Django + DRF-based web application to manage IPO listings and company profiles, with PostgreSQL as the backend database.

---

## 🚀 Features

- ✅ Add and manage companies
- ✅ Create and list IPOs
- ✅ Admin interface for managing users, IPOs, and companies
- ✅ API endpoints using Django REST Framework
- ✅ Bootstrap-powered frontend for quick UI interaction

---

## 🛠️ Tech Stack

- **Backend**: Django, Django REST Framework
- **Database**: PostgreSQL (or SQLite for local testing)
- **Frontend**: HTML + Bootstrap (optional enhancements)
- **Others**: Git, GitHub, Python virtual environment

---

## 📁 Project Structure

bluestock-ipo-webapp/
├── ipo/ # Django app for IPOs
├── ipoproject/ # Django project configuration
├── manage.py # Django entry point
├── .gitignore
└── README.md

yaml
Copy
Edit

---

## 🧪 Local Setup

### 1. Clone the repository

```bash
git clone https://github.com/pranee-v/bluestock-ipo-webapp.git
cd bluestock-ipo-webapp
2. Create and activate virtual environment
bash
Copy
Edit
python -m venv env
env\Scripts\activate  # On Windows
3. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt  # (or manually install)
bash
Copy
Edit
pip install django djangorestframework psycopg2-binary
4. Set up database
bash
Copy
Edit
python manage.py makemigrations
python manage.py migrate
5. Create superuser (optional, for admin panel)
bash
Copy
Edit
python manage.py createsuperuser
6. Run the server
bash
Copy
Edit
python manage.py runserver
Visit: http://127.0.0.1:8000

🔐 Admin Panel
Visit: http://127.0.0.1:8000/admin

Login using the superuser credentials you created.

🔌 API Endpoints
Endpoint	Description
/api/ipos/	List & Create IPOs
/api/company/	List & Create Companies

📦 Deployment (optional)
You can deploy this on platforms like:

Render

Railway

Vercel (Frontend) + Render (Backend)

📄 License
This project is for educational/demo purposes only.

yaml
Copy
Edit

---

## ✅ How to Use It

1. In VS Code, create a file `README.md` in your root project folder (same level as `manage.py`)
2. Paste the content above into it
3. Save the file and commit it:

```bash
git add README.md
git commit -m "Add README"
git push
