# Company Management System

Django проект для управления информацией о рабочих местах и сотрудниках.

## Технологии

- Python 3.14.3
- Django 5.x
- Black (форматирование)
- isort (сортировка импортов)

## Установка и запуск

1. Клонировать репозиторий:
   git clone https://github.com/fedlow/company_management.git
   cd company_management

2. Создать виртуальное окружение и активировать:
   python -m venv venv
   source venv/bin/activate  # или venv\Scripts\activate на Windows

3. Установить зависимости:
   pip install -r requirements.txt

4. Выполнить миграции (если будут модели в будущем):
   python manage.py migrate

5. Запустить сервер разработки:
   python manage.py runserver

## Структура проекта

- `company_management/` – настройки проекта
- `workplaces/` – приложение для рабочих мест
- `employees/` – приложение для сотрудников

## Автор

[fedlow]