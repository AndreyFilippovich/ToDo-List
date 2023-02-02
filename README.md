# Планировщик задач

### Технологии:
[![Python](https://img.shields.io/badge/-Python-464646?style=flat-square&logo=Python)](https://www.python.org/) [![Django](https://img.shields.io/badge/-Django-464646?style=flat-square&logo=Django)](https://www.djangoproject.com/) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=flat&logo=bootstrap&logoColor=white)

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

