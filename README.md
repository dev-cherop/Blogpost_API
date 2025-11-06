📝 Blogpost APIA RESTful API built using Django REST Framework for managing blog posts.
This API provides all the necessary endpoints to perform CRUD (Create, Read, Update, Delete) operations on blog posts.

✨ FeaturesFull CRUD: Complete functionality for creating, reading, updating, and deleting blog posts.
Django Backend: Leverages the power and security of the Django framework.
RESTful Design: Clean, resource-oriented endpoint design following REST best practices.
Dockerized: Ready-to-use DOCKERFILE for easy containerization and deployment.
🛠️ Tech StackCategoryTechnologyFrameworkDjango & Django REST Framework (DRF)LanguagePythonDatabaseSQLite (Default, for development)ContainerizationDocker
🚀 Getting StartedPrerequisitesMake sure you have the following installed:
Python (3.8+)pip (Python package installer)
Docker (Optional, but recommended for easy setup)
Local Setup (Without Docker)
Clone the repository:
git clone https://github.com/dev-cherop/Blogpost_API.git
cd Blogpost_API
Create and activate a virtual environment:Bashpython -m venv venv
source venv/bin/activate  # macOS/Linux
# venv\Scripts\activate  # Windows
Install dependencies:Bashpip install -r requirements.txt
Run migrations:Bashpython manage.py makemigrations
python manage.py migrate
Create a superuser (for accessing the Admin panel and testing authenticated endpoints):Bashpython manage.py createsuperuser
Start the server:Bashpython manage.py runserver
The API should now be running at http://127.0.0.1:8000/.
Docker SetupUse the provided DOCKERFILE to build and run the application in a container.
Build the Docker image:Bashdocker build -t blogpost-api:latest .
Run the container:Bashdocker run -p 8000:8000 blogpost-api:latest
Access the application at http://localhost:8000/.
🗺️ API EndpointsThe API is structured around the /api/ path.
MethodEndpointDescriptionAuthenticationGET/api/posts/Retrieves a list of all blog posts.
NonePOST/api/posts/Creates a new blog post.
RequiredGET/api/posts/<id>/Retrieves a specific blog post by ID.
NonePUT/PATCH/api/posts/<id>/Updates an existing blog post.
RequiredDELETE/api/posts/<id>/Deletes a specific blog post.
RequiredPOST/api/token/Obtain an authentication token (JWT/Token Auth).
None🤝 ContributingWe welcome contributions! Please feel free to open an issue or submit a pull request.
Fork the Project.Create your Feature Branch (git checkout -b feature/NewFeature).
Commit your Changes (git commit -m 'feat: Add new feature').
Push to the Branch (git push origin feature/NewFeature).Open a Pull Request.
📄 LicenseDistributed under the MIT License. See LICENSE for more information.
📧 Contactdev-cherop - GitHub ProfileProject Link: https://github.com/dev-cherop/Blogpost_API
