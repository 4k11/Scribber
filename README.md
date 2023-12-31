# Scribber - Django Blog App

Scribber is a powerful and customizable Django-based blog app that empowers you to share your thoughts, stories, and ideas with the world. It is designed with simplicity and flexibility in mind, allowing you to focus on what matters most – Your content.

## Getting Started

### Prerequisites

- Python 3.x
- Django (latest version recommended)

### Installation

1. Clone the repository and create a virtual env:

   ```bash
   conda create --name myEnv django
   ```

2. Navigate to the project directory and activate the env:

   ```bash
   conda activate myEnv
   ```

3. Install dependencies

   ```bash
   conda install packagename
   pip install packagename
   ```

4. Apply migrations:

   ```bash
   python manage.py migrate
   python manage.py makemigrations
   ```

5. Create a superuser account:

   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:

   ```bash
   python manage.py runserver
   ```

Visit [http://localhost:8000/admin](http://localhost:8000/admin) to log in with your superuser account and start creating blog posts.

Happy Scribbing! 📝
