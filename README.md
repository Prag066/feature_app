# feature_app
Practice for adding multiple databases into the application

python manage.py makemigrations users books
python manage.py migrate --database=users_db
python manage.py migrate --database=books_db
python manage.py createsuperuser --database=users_db
