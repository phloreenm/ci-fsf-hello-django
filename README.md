New Django project
    - pip install --upgrade pip
    - pip install django       
    - django-admin startproject django_todo .
    - python3 manage.py runserver
    - python manage.py migrate - convert python code into DB operations, so that the DB will work properly
        - python3 manage.py makemigrations --dry-run - without --dry-run when noew models written in Python,in order to convert them to database ops.
        - python3 manage.py showmigrations - 
        - python manage.py migrate --plan - 
    - python3 manage.py createsuperuser - first time to create a super user for the admin dashboard at .../admin/