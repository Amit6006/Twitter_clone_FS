# Tweeter_clone_FS
This is a full-stack Twitter clone built using Django (backend) and Bootstrap (frontend). It features user authentication, tweet creation with optional image uploads, and CRUD operations for tweets.
Features
User Authentication (Sign Up, Login)
Tweet Creation with Text and Photo
Edit, Delete, and View Tweets
Simple and intuitive UI
Tech Stack
Backend: Django
Frontend: HTML, CSS (Bootstrap)
Database: SQLite (Django default)
Prerequisites
Python 3.9+
Pip (Python package manager)
Installation & Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-repo/twitter-clone.git
cd twitter-clone
Create and activate a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Apply migrations:

bash
Copy code
python manage.py migrate
Create a superuser (admin user):

bash
Copy code
python manage.py createsuperuser
Run the development server:

bash
Copy code
python manage.py runserver
Access the application:

Open your browser and navigate to http://127.0.0.1:8000/
