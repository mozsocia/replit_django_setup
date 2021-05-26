# replit_django_setup

## use poetry package manager to create project
https://github.com/mozsocia/poetry_setup


## in settings.py add these lines in the last 

```
ALLOWED_HOSTS = ['*']
X_FRAME_OPTIONS = '*'

```

## create ".replit" file and add these lines
```
language = "python3"
run = "python manage.py runserver 0.0.0.0:3000"
```
