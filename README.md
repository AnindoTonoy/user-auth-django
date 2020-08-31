# user-auth-django
a simple login/homepage/logout django app for learning
## Prerequisites
```bash
python== 3.8 or up and django==3.1
```
## Run
```bash
python manage.py makemigrations
python manage.py migrate
```
## To use admin panel you need to create super user using this command
```bash
python manage.py createsuperuser
```
## To run the program in local server use the following command
```bash
python manage.py runserver
```
Then go to http://127.0.0.1:8000 in your browser

## Project snapshot

### Login page - UI
![screencapture-127-0-0-1-8000-login-2020-08-31-18_39_18](https://user-images.githubusercontent.com/26842902/91720798-89b46700-ebb9-11ea-8bf7-8364599e0dfb.png)

### Homepage and logout button after login authetication - UI
(you can costomize this page as you needed)

![screencapture-127-0-0-1-8000-2020-08-31-18_39_52](https://user-images.githubusercontent.com/26842902/91721030-e6b01d00-ebb9-11ea-88df-73440667ee08.png)
