# Authenticated API

### Installation
First of all, create a new **virtualenv** called env inside the root folder
    
    virtualenv env
    source env/bin/activate

Now you can install all the requirements

    pip install -r requirements.txt

So far so good, now migration and super user

    python manage.py migrate
    python manage.py createsuperuser

And now you can test your new API server at http://localhost:8000/api/v1/snippets

    python manage.py runserver
