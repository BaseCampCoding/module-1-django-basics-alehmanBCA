mkdir facebook-clone

cd facebook-clone

touch readme.md

python 3 - venv .venv (typo)

python3 -m venv .venv

source .venv/bin/activate

pip install django

django-admin startproject config .

python3 manage.py startapp facebook_clone

python3 manage.py migrate

python3 manage.py runserver