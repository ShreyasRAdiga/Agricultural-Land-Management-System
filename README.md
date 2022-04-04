# Agricultural-Land-Management-System
Note # is used to highlight the line do not copy it on command promt and type commands on command promt or vs cmd promt

# follow this method 

# pip install django
# python manage.py makemigrations <app_name>
# python manage.py migrate <app_name>



 # For email verification do some changes
 follow this code
# Under ALMSproject>main>settings.py // follow this file location
in setttings .py


DEFAULT_AUTO_FIELD = "django.db.models.BigAutoField"
MEDIA_URL = "agri/media/"
media_root = os.path.join(BASE_DIR, "agri/media")

EMAIL_HOST='smtp.gmail.com'  

# EMAIL_HOST_USER='enter your email' Enter your mail id

# EMAIL_HOST_PASSWORD='enter your password'  Enter you mail id password

EMAIL_PORT=465

EMAIL_USE_SSL=True

# Under # Under ALMSproject>agri>views.py // follow this file location
in views.py

# Change email 'ALMSproject123.com' to your mail id that you have given in Under ALMSproject>main>settings.py
