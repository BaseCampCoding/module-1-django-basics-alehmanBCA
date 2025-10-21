mkdir fake-movie-database

cd fake-movie-database

touch readme.md

python3 -m venv .venv

source .venv/bin/activate

pip install django

django-admin startproject config .

python3 manage.py startapp fake_movie_database

python3 manage.py migrate

python3 manage.py runserver