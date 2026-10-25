<!-- 1. Essential Commands -->
# Create project
django-admin startproject mysite

# Create app
python manage.py startapp blog

# Run development server
python manage.py runserver

# Database migrations (after model changes)
python manage.py makemigrations
python manage.py migrate

# Create admin user
python manage.py createsuperuser

<!-- 3. Key File Structure -->
mysite/
    manage.py          # Command-line utility
    mysite/
        settings.py    # Configuration
        urls.py        # URL routing

<!-- 3. Core Concepts (with short example snippets) -->

Model (models.py): Define data tables with Python classes, Django handles the database automatically .

View (views.py): Functions that receive requests and return responses, combined with render() for templates .

Template (HTML): Use {{ variable }} and {% for %} / {% if %} for dynamic content .

<!-- 4. What Beginners Actually Need to Remember -->
Django's "syntax" is essentially Python syntax plus framework conventions. You don't need to memorize Django-specific syntax; you should remember commands and the "model → migration → view → template" workflow. The official tutorial (Writing your first Django app) is the best entry point—it's more practical than any summary .