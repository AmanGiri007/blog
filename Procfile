web: gunicorn blog_project.wsgi --log-file -
python manage.py collectstatic --noinput
manage.py migrate