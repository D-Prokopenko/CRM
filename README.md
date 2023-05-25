# CRM project

python manage.py startapp orders_app

# миграции
python manage.py makemigrations
python manage.py migrate

чтобы создать новую БД в консоли пишем:

**createdb mars_db**

удалить БД в консоли пишем:

**dropdb mars_db**

# админка

создание суперпользователя:

**python manage.py createsuperuser**