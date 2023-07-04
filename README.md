# Python-Test-Project

#To install django

pip install django

#other libraries(required for this project)

pip install streamlit, plotly, whitenoise, heroku, django-heroku

#To create a Django project

django-admin.py startproject coolsentimentsanalyzer

#To create an app inside a Django project

cd coolsentimentsanalyzer

python manage.py startapp aisentimentsanalyzer

#Migrate the database
python manage.py migrate

#To run this app, use:
python manage.py runserver
