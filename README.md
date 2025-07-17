# 🗒️ Fullstack To Do List Using Django

A simple task management web app built using Django. Users can create, update, delete, and view their to-do items. Includes user authentication to ensure tasks are personalized per user.

---

## 🚀 Features

- 🧑‍💻 User Authentication (Login & Logout)
- ✅ Create / Read / Update / Delete tasks
- 📊 Task completion and remaining counters
- 🎨 Clean and User-friendly UI
- 🛠️ Admin panel to manage tasks and users

---

## 📸 UI Design 


![Task List UI](UI.png)

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS (with custom styles)
- **Database:** SQLite (default)
- **Admin Panel:** Enabled

---

## 📂 Project Structure

```text
Django_Todo-list/
├── base/               # Core app (models, views, templates)
│   ├── templates/
│   └── static/
├── todo_list/          # Project config (settings, urls)
├── db.sqlite3          # SQLite DB
├── manage.py
└── README.md
``` 
---
## 💻 How to Run Locally

Follow these steps to get the project running on your local machine:



### 1. 🧬 Clone the Repository

```bash
git clone https://github.com/Michiaki16/Django_Todo-list.git
cd Django_Todo-list
```

### 2. 🐍 Create a Virtual Environment

```bash
python -m venv venv
```



### 3. ✅ Activate the Virtual Environment

```bash
# On macOS/Linux:
source venv/bin/activate

# On Windows:
venv\Scripts\activate
```



### 4. 📦 Install Dependencies

```bash
pip install -r requirements.txt
```



### 5. 📂 Apply Migrations

```bash
python manage.py migrate
```



### 6. 🔐 Create a Superuser

```bash
python manage.py createsuperuser
```

> Follow the prompts to set your username, email, and password.



### 7. 🚀 Run the Server

```bash
python manage.py runserver
```



### 8. 🌐 Open the App in Your Browser

- Home: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
- Admin Panel: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)


