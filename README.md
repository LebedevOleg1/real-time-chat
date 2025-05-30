# Django Real-Time Chat

[![Django](https://img.shields.io/badge/Django-4.0.2-green.svg)](https://www.djangoproject.com/)
[![Channels](https://img.shields.io/badge/Channels-3.0.4-blue.svg)](https://channels.readthedocs.io/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-yellow.svg)](https://www.python.org/)

Веб-приложение для обмена сообщениями в реальном времени с использованием Django Channels и WebSocket.

## Основные возможности
- 📨 Реальное взаимодействие через WebSocket
- 🔐 Система аутентификации пользователей
- 🚪 Создание и управление чат-комнатами
- 📝 Сохранение истории сообщений
- 👥 Поддержка множества пользователей

## Технологии
- **Backend**: Django 4.0 + Channels 3.0
- **Frontend**: HTML5, Tailwind CSS
- **База данных**: SQLite (по умолчанию)
- **Асинхронный слой**: InMemoryChannelLayer

## Быстрый старт
### Требования
- Python 3.10+
- pip

### Установка
```bash
# Клонируйте репозиторий
git clone https://github.com/yourusername/django-chat.git
cd django-chat
```
# Создайте и активируйте виртуальное окружение
```bash
python -m venv venv
source venv/bin/activate  # Linux/MacOS
# venv\Scripts\activate  # Windows
```

# Установите зависимости
```bash
pip install -r requirements.txt
```

# Примените миграции
```bash
python manage.py makemigrations
python manage.py migrate
```

# Создайте администратора
```bash
python manage.py createsuperuser
```

# Запустите сервер
```bash
python manage.py runserver
```


## Использование
# Регистрация:
Откройте /signup/ и создайте аккаунт.

# Создание комнаты:
Войдите в админку (/admin/), добавьте новую комнату в разделе Room.

# Общение:

Откройте /rooms/

Выберите комнату

Начните обмен сообщениями в реальном времени!