The Twitter Clone is a simple full-stack web application built using Django (backend) and Bootstrap, Html, CSS (frontend). It allows users to create and manage tweets, including uploading images with each tweet. The app supports user authentication, and provides a user-friendly interface for creating, editing, and deleting tweets.

Steps to Run the Project:

1.Install Dependencies: Install required libraries using:

        pip install -r requirements.txt

2.Apply Migrations: Set up the database by applying migrations:

        python manage.py migrate
3.Create a Superuser: Create an admin user to manage the application:

        python manage.py createsuperuser
4.Run the App: Launch the Django development server with:

        python manage.py runserver
View the App: Open your browser and go to:

      http://127.0.0.1:8000/
