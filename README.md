# django-app

## Create app

### Create a project

Auto-generate a Django project.

```console
django-admin startproject mysite
```

### The development server

Verify that the Django project works.

```console
python manage.py runserver
```

### Create a app

```console
cd mysite
python manage.py startapp polls
```

## Create models

[https://docs.djangoproject.com/en/3.1/intro/tutorial02/]

### Create initial database

```console
python manage.py migrate
```

### Create models

After adding the models for the poll app and updating mysite/settings.py store
the updates as a *migration*.

```console
python manage.py makemigrations polls
python manage.py migrate
```

## Admin site

### Create admin user

Create a test admin user. *Currently it's admin admin.*

```console
python manage.py createsuperuser
```

### Modify the app

After registering your modules in polls/admin.py you can adminster the models on the admin site.

## Views


