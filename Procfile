web: gunicorn config.wsgi:application
worker: celery worker --app=sample_django_app.taskapp --loglevel=info
