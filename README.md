# Django_Books_Management

To run the project:

1. Python manage.py makemigrations
2. Python manage.py migrate
3. python manage.py runserver (Make sure the port is free)

Install all these packages from the requirements.txt file:

asgiref==3.6.0
Django==3.2
django-bootstrap-modal-forms==2.2.0
django-bootstrap3==22.2
django-forms-bootstrap==3.1.0
django-widget-tweaks==1.4.12
Pillow==9.4.0
pytz==2022.7.1
sqlparse==0.4.3


Login Credentials: (There are two dashboards, one for the user(publisher) and the other for admin

Admin: (Only admin has the access to add, view, delete and update books and users from the app)

username: varniha
password: 1234

User(Publisher): (User can only add a new book and request the admin to delete books that has been created by the user alone)

username: kodeesh
password: kodeesh

(You can also craete a new user and login using the register and login page and a new admin using the createsuperuser command.)
