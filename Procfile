web: gunicorn firstDjango.wsgi:my_site --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate