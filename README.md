# Django-loginForm
Install dependencies
uv pip install -r requirements.txt

# in development mode
uv pip install -r requirements-dev.txt
Configure the settings (connection to the database, connection to an SMTP server, and other options)
Edit source/app/conf/development/settings.py if you want to develop the project.

Edit source/app/conf/production/settings.py if you want to run the project in production.

Apply migrations
python source/manage.py migrate
Running
On development server
Start the local web server:

python source/manage.py runserver
