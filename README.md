# install poetry

brew install poetry

# poetry init - make venv

poetry init

poetry add django

# env start

poetry shell

django-admin

# env end

exit

# start server

python manage.py runserver

# migration

python manage.py migrate

# create superuser

python manage.py createsuperuser

# create new apps

python manage.py startapp houses

# create migrations

python manage.py makemigrations
