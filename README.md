# Simple Blog Application

This is a simple blog application where users can:
1. View a list of blog posts.
2. Add new blog posts.
3. View details of individual blog posts.

## Technologies Used
- Backend: Django
- Database: MySQL
- Frontend: Bootstrap

## Requirements
- Python 3.6+
- Django 3.2+
- MySQL

## Installation

```bash

1. Clone the repository
git clone https://github.com/yourusername/blog-application.git
cd blog-application

2. Set up virtual environment
python -m venv myenv
source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`

3. Install dependencies
 pip install -r requirements.txt

4. Mysql database script
CREATE DATABASE blog_db;
CREATE USER 'blog_user'@'localhost' IDENTIFIED BY 'your_password';
GRANT ALL PRIVILEGES ON blog_db.* TO 'blog_user'@'localhost';
FLUSH PRIVILEGES;

5. Apply migrations(if any changes to data model)
python manage.py makemigrations
python manage.py migrate

6. Create superuser
python manage.py createsuperuser

7. Run development server
python manage.py runserver

8. Access the application
Open your web browser and go to http://127.0.0.1:8000/posts/ to see the list of blog posts.




