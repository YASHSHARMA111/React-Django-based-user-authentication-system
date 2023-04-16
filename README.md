Django setup:
pip install virtualenvwrapper
virtualenv authenv
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
authenv\Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

React Setup:
npm install
npm start
npm install @reduxjs/toolkit redux

If any error comes copy the error & try ChatGPT to solve them

