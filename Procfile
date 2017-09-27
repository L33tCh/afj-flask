worker: python manage.py create_db
worker: python manage.py db init
worker: python manage.py db migrate
web: gunicorn manage:app --log-file=-