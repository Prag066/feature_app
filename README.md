# feature_app
just for practice

python manage.py makemigrations users books
python manage.py migrate --database=users_db
python manage.py migrate --database=books_db
python manage.py createsuperuser --database=users_db
