Django With Firebase Cloud Messaging
===================================

send notification fron Django to The Firebase Cloud Messaging.


Getting Started
---------------

1. Clone this project
1. Edit `your_api_key` for your key of server(Firebase).
### In settings.py
```
FCM_DJANGO_SETTINGS = {
    "FCM_SERVER_KEY": "your_api_key"
}
```
1. Install `pip install -r requirements.txt`
1. Run in the console `python manage.py migrate`
1. Create a superuser `python manage.py createsuperuser`
1. Finally  execute `python manage.py runserver`


License
-------

2018. Licensed
