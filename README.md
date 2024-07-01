# sabaripro

## Project Description
sabaripro is a Django-based project that provides a web interface for managing student details and their subject marks. The project includes the following features:
- Student model with fields: Name, Age, Email, and City.
- Subject Marks model with fields: Student (ForeignKey), Language 1, Language 2, Acting, and Dance.
- Django Admin interface for data entry.
- A detailed view displaying student information and their subject marks.



markdown
Copy code

## Getting Started

### Prerequisites
- Python 
- Django 

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/sabaripro.git
   cd sabaripro
Create and activate a virtual environment:


python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install the required packages:


pip install -r requirements.txt
Run migrations:


python manage.py makemigrations
python manage.py migrate
Create a superuser:


python manage.py createsuperuser
Start the development server:


python manage.py runserver

# admin:
userneme:sabari
password:djangosabari

# Usage
Access the Django Admin interface at http://127.0.0.1:8000/admin/ and log in with the superuser credentials.
Add student and subject marks entries via the admin interface.
View student details and their subject marks at http://127.0.0.1:8000/student/<id>/.
# Project Structure
pro/: Project folder containing settings and configuration files.
sabaripro/: Main Django project folder.
sabariapp/: Django app folder containing models, views, templates, and admin configuration.
