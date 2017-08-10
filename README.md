# Django-AngularJS-Scrumcard
The goal is to develop a Scrumboard where one can create various scrumcards for different lists such as To do list, In progress etc. The project is developed using AngularJS for front-end, Django for writing server-side code. The REST (Django REST framework) is used to pass data between front-end JS and back-end python code.

## Prerequisites
* Install python (version 3.5) from [here](https://www.python.org/downloads/)

* A recommended step is to create a virtual environment, it keeps the setup independent of other projects.
```
python -m venv myvenv
```

* Next step is to install Django, you may use pip for it. 
```
pip install django
```

* Check out the project code
```
git clone https://github.com/saritabhateja/Django-AngularJS-Scrumcard.git
```
* Create database tables and do the migrate step, create superuser account and run development server.
```
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

The website will run at `http://127.0.0.1:8000/`. In order to visit site as admin (superuser), go to url `http://127.0.0.1:8000/admin`
