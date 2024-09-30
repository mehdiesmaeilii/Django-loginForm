
# SIMPLE LOGIN-LOGOUT FORM
in this project I created a simple form using Django's default setting 
I used {{form.as_p}} tag that Django automatically creat a form that you can login and logout by creating super user in your terminal and this will provide both admin page and 
this simple form



## Installation
activate your virtual environment

```bash
  py -3 -m venv .venv
.venv\scripts\activate

```
then install the requirements

```bash
  pip install -r requirements.txt
```

inside the project folder open your terminal  and create a superuser
```bash
  python manage.py createsuperuser
```

again inside your terminal run the server and enjoy

```bash
  python manage.py runserver
```

