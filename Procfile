web: gunicorn beer_charts.wsgi:dashboard --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate