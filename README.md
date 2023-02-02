# Планировщик задач

### Технологии:
[![Python](https://img.shields.io/badge/-Python-464646?style=flat-square&logo=Python)](https://www.python.org/) [![Django](https://img.shields.io/badge/-Django-464646?style=flat-square&logo=Django)](https://www.djangoproject.com/) 

## Описание проекта

### Проект позволяет запустить сервер с планировщиком задач

## Реализованные функции:

#### - Регистрация пользователей;
#### - Вход/выход пользователей;
#### - Просмотр, добавление, редактирование и удаление собственных задач;
#### - Реализован поиск задач по частям слов;

## Запуск проекта:

#### Склонировать репозиторий:
> https://github.com/AndreyFilippovich/ToDo-List.git

#### Если ранее не пользовались, то скачать виртуальное окружение:
> pip install virtualenv

#### Установить виртуальное окружение:
> python -m venv venv

#### Активировать виртуальное окружение:
> source venv/scripts/activate

#### Установить зависимости командой:
> pip install -r requirements.txt

#### Перейдите в директорию проекта:
> cd ToDo_list

#### Создайте миграции:
> python manage.py makemigrations

#### Примените миграции:
> python manage.py migrate

#### Создайте суперпользователя:
> python manage.py createsuperuser

#### Запустите проект:
> python manage.py runserver

## Проект будет доступен по адресу:

http://127.0.0.1:8000/

