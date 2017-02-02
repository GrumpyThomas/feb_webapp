# feb_webapp
This is a Django project, started on Feb 1st 2017

How to start Django project
#creating a folder
mkdir feb_webapp
cd feb_webapp
#starting virtualenv
virtualenv env
source env/bin/activate
#installing django
pip install django
#making sure django is installed
pip freeze
pip freeze > requirements.txt
#starting a project
django-admin startproject project
#creating database
cd project
python manage.py migrate
#starting server
python manage.py runserver
#go to your browser enetr the server ip from terminal
http://127.0.0.1:8000/