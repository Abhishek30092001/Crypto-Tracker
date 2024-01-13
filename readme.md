# Instructuction To Run the Project.

# Just follow  these simple steps.

# clone the repo
git clone 'https://github.com/Abhishek30092001/Crypto-Tracker.git'

# cd into the project folder
cd django-Crypto-Tracker

# create a virtualenv
python -m venv env

# activate the virtualenv
env\Scripts\activate

# install the needed packages
pip install -r requirements.txt

# make migrations
python manage.py makemigrations 
python manage.py migrate

# delete existing database if necessary, overwrite and make your own migrations and users

# start the server
python manage.py runserver
# Django will start the server on port 8000 so open the browser and go to http://localhost:8000/


# create a superuser to login to the admin panel
python manage.py createsuperuser

# Visit http://localhost:8000/admin to login to the admin panel
