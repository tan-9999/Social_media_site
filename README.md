# 🚀 Space Talk! - Social Media Site

A full-featured social media application built with Django 6.0 and Python 3.12. Users can join groups, post content, and interact with a community feed.

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-6.0-green?logo=django&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?logo=bootstrap&logoColor=white)

## ✨ Features
*   **User Authentication**: Sign up, Log in, and Log out functionality.
*   **Groups**: Create new communities or join existing ones.
*   **Posts**: Share thoughts within specific groups.
*   **Feed**: Personalized timeline of posts from groups you've joined.
*   **Modern UI**: Clean interface using Bootstrap 5.

## 🛠️ Tech Stack
*   **Backend**: Django 6.0
*   **Frontend**: HTML5, CSS3, Bootstrap 5
*   **Database**: SQLite (Development)
*   **Utilities**: Django Bootstrap 5

## ⚙️ Installation

Follow these steps to set up the project locally:

### 1. Clone the Repository
git clone https://github.com/tan-9999/Social_media_site.git
cd Social_media_site

text

### 2. Create a Virtual Environment
It's recommended to use a virtual environment to manage dependencies.
Windows
python -m venv .venv
.venv\Scripts\activate

Mac/Linux
python3 -m venv .venv
source .venv/bin/activate

text

### 3. Install Dependencies
pip install -r requirements.txt

text
*(Note: If `requirements.txt` is missing, install the core packages manually: `pip install django django-bootstrap5`)*

### 4. Apply Migrations
Set up the local database.
python manage.py makemigrations
python manage.py migrate

text

### 5. Create a Superuser (Optional)
To access the admin panel:
python manage.py createsuperuser

text

### 6. Run the Server
python manage.py runserver

text
Open your browser and visit: `http://127.0.0.1:8000/`

## 📂 Project Structure
Social_media_site/

├── accounts/ # User authentication app

├── groups/ # Community groups management

├── posts/ # Posting functionality

├── Social_media_site/# Main project settings & URLs

├── static/ # CSS, JS, and Images

├── templates/ # HTML Templates

├── manage.py # Django command-line utility

└── db.sqlite3 # Local database

text

## 🤝 Contributing
1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

## 📜 License
This project is open-source and available under the MIT License.
