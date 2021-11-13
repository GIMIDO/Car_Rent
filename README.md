# CAR RENT SYSTEM

## Available Features:

- Customer Panel
- Car Dealer Panel
- Search Rental Cars
- Manage Orders
- Manage Rental Cars
- Earnings History
- Sales History

## Run Project


Install Python

Create Virtual Environment

```
python -m venv .venv
```

Install Packages

```
pip install -r requirements.txt
```

Requires **MySQL database**, so create a database named _ocrsdjango_.

Then, make database migrations:
```
python manage.py makemigrations
python manage.py migrate
```

And finally, after a successful migration run the application:
```
python manage.py runserver
```

Go to URL “http://127.0.0.1/[ PORT_NUMBER ]/“

For the Admin Panel credentials, you have to create one with a superuser.
