# Django Basic Project

A beginner-friendly Django project showcasing fundamental web development concepts.

## Project Overview

This is my first Django project, designed to learn and practice Django basics including models, views, templates, and URL routing.

## Features

- Django web framework setup
- SQLite database integration
- Template rendering
- URL routing and views
- Static files configuration

## Requirements

- Python 3.8+
- Django 3.2+
- pip (Python package manager)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/angeljosephads11/django-basic-project01.git
   cd django-basic-project01
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```

   The application will be available at `http://127.0.0.1:8000/`

## Project Structure

```
django-basic-project01/
├── manage.py
├── requirements.txt
├── README.md
├── db.sqlite3
└── [project_name]/
    ├── settings.py
    ├── urls.py
    ├── wsgi.py
    └── asgi.py
```

## Usage

To use this project:

1. Start the development server (see Installation step 6)
2. Navigate to `http://localhost:8000/` in your browser
3. Explore the various pages and features

## Creating a Superuser

To access the Django admin panel:

```bash
python manage.py createsuperuser
```

Then visit `http://127.0.0.1:8000/admin/` to manage your application.

## Learn More

- [Django Documentation](https://docs.djangoproject.com/)
- [Django for Beginners](https://www.djangoforbeginners.com/)

## License

This project is open source and available under the MIT License.

## Author

Created by [angeljosephads11](https://github.com/angeljosephads11)

---

Happy coding! 🚀
