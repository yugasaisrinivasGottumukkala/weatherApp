$ Python Django weather application
First install requirements.txt #Python3.7.6
**_
"pip install requirements.txt"

in cmd prompt :
run these cmnds
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser  	#to register as admin

to run program
python manage.py runserver


C:\Users\User-Name\Desktop\weather_app_django\the_weather>python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
September 27, 2019 - 13:29:17
Django version 2.2.5, using settings 'the_weather.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.

open browser and paste {the link of generated server} /admin-->{http://127.0.0.1:8000/admin}
login with superuser id password 
enjoy the web weather app