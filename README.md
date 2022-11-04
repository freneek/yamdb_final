ReadMe
# YaMDB
## Учебный проект рейтингового сайта



### Технологии
- Python 
- Django 
- DjangoRest Framework

### Запуск
- Создайте и активируйте виртуальное окружение
- Установите зависимости из файла requirements.txt
' pip install -r requirements.txt '
- выполните миграции:
 1) ' python3 manage.py makemigrations '
 2) ' python3 manage.py migrate '
- наполните базу данных:
 python manage.py import_csv
- В папке с файлом manage.py выполните команду:
' python3 manage.py runserver ' 

### шаблон наполнения env-файла:
- DB_ENGINE=django.db.backends.postgresql # указать, что работаем с postgresql
- DB_NAME=postgres # имя БД
- POSTGRES_USER=postgres # имя пользователя БД
- POSTGRES_PASSWORD=postgres # пароль для БД (необходимо указать свой)
- DB_HOST=db # название контейнера БД
- DB_PORT=5432 # порт для подключения к БД

### Авторы
Nikita Feyuk
Igor Polyakov
Andrey Rodin

### Проект развернут по адресу
http://62.84.115.127/

https://github.com/freneek/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg