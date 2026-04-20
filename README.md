# API для социальной сети Yatube

## Описание
Проект позволяет взаимодействовать с платформой Yatube через REST API: создавать посты, оставлять комментарии, подписываться на авторов и просматривать группы. 

## Технологии
- Python 3.11
- Django 3.2.16
- Django Rest Framework
- Simple-JWT
- Djoser

## Инструкция по запуску
1. Клонируйте репозиторий.
2. Установите зависимости: `pip install -r requirements.txt`.
3. Примените миграции: `python manage.py migrate`.
4. Запустите сервер: `python manage.py runserver`.