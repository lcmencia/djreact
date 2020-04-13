# Django + React

[alt text](https://github.com/justdjango/DjReact/blob/master/thumbnail.png "Logo")

This project is broken up into a backend and frontend. The backend contains the Django project which uses the Django Rest Framework to host a simple API. The frontend uses React and queries data from the API.

Run the following commands to get started:

```json
virtualenv env
pip install -r requirements.txt
npm i
npm run build
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
