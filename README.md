🔥 Online Fire Reporting System

A web-based system built with Django and SQLite that allows users to quickly report fire incidents. The platform notifies fire departments in real-time and enables authorities to track, manage, and analyze reports efficiently.

🚀 Features

User-friendly interface to submit fire incident reports

Real-time alerts to fire stations

Track incident status (Pending, In Progress, Resolved)

Admin dashboard for managing reports and users

Secure authentication system (Django Auth)

🛠️ Tech Stack

Backend Framework: Django (Python)

Database: SQLite (default Django database)

Frontend: HTML, CSS, JavaScript, Bootstrap

📂 Project Structure
/fire_reporting_system
│── fire_reporting/        # Main app (incident reporting)  
│── fire_reporting_system/ # Django project files  
│── templates/             # HTML templates  
│── static/                # CSS, JS, and images  
│── db.sqlite3             # SQLite database  
│── manage.py              # Django project manager  

⚙️ Installation & Setup

Clone the repository:

git clone https://github.com/your-username/OnlineFireReportingSystem.git
cd OnlineFireReportingSystem


Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # On Linux/Mac  
venv\Scripts\activate      # On Windows  


Install dependencies:

pip install -r requirements.txt


Run database migrations:

python manage.py migrate


Create a superuser (for admin access):

python manage.py createsuperuser


Start the server:

python manage.py runserver


Open in browser:

http://127.0.0.1:8000/

🎯 Future Enhancements

Google Maps integration for location tracking

Email/SMS notifications to fire stations

AI-powered fire severity prediction

Mobile app integration
