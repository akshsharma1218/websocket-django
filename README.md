# websocket-django

## set-up

intall requirements `pip install -r requirements.txt`

run redis server `sudo systemctl run redis`

run django server `python3 manage.py runserver`

go to url : `http:127.0.0.1/chat/<room_name>/` from any two browser and you will be able to chat with each other.

Note : create two superusers first and log_in to the django admin in the both browser, otherwise username will be empty(''). 
