# Урок 51 — Django: регистрация, вход и выход

Классная работа и домашнее задание.

## Запуск

```bash
cd site_auth
pip install django
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

http://127.0.0.1:8000/

## Страницы

- `/` — главная, все записи
- `/signup/` — регистрация
- `/accounts/login/` — вход
- `/profile/` — профиль и мои записи (только после входа)
- `/notes/new/` — новая запись (только после входа)
- `/accounts/password_change/` — смена пароля
