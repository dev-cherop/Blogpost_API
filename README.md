# 📝 Blogpost APIA RESTful API built using Django REST Framework for managing blog posts.
This API provides all the necessary endpoints to perform CRUD (Create, Read, Update, Delete) operations on blog posts.

# ✨ FeaturesFull CRUD: Complete functionality for creating, reading, updating, and deleting blog posts.

Django Backend: Leverages the power and security of the Django framework.

RESTful Design: Clean, resource-oriented endpoint design following REST best practices.

Dockerized: Ready-to-use DOCKERFILE for easy containerization and deployment.

# 🛠️ Tech Stack Category Technology Framework 
Django & Django REST Framework (DRF)LanguagePythonDatabaseSQLite (Default, for development)ContainerizationDocker

# 🚀 Getting StartedPrerequisitesMake sure you have the following installed:

Python (3.8+)
pip (Python package installer)

Docker (Optional, but recommended for easy setup)

Local Setup (Without Docker)

Clone the repository:

git clone https://github.com/dev-cherop/Blogpost_API.git

cd Blogpost_API

Create and activate a virtual environment:
python -m venv venv

source venv/bin/activate  # macOS/Linux

# venv\Scripts\activate  # Windows

Install dependencies:
pip install -r requirements.txt

Run migrations:
python manage.py makemigrations

python manage.py migrate

Create a superuser (for accessing the Admin panel and testing authenticated endpoints):

python manage.py createsuperuser

Start the server:
python manage.py runserver

The API should now be running at http://127.0.0.1:8000/.



📄 LicenseDistributed under the MIT License. See LICENSE for more information.
📧 Contactdev-cherop - GitHub ProfileProject Link: https://github.com/dev-cherop/Blogpost_API
