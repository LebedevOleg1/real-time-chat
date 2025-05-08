# Real-Time Chat Application with Django

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.0.2-green)](https://www.djangoproject.com/)
[![Channels](https://img.shields.io/badge/Channels-3.0.4-red)](https://channels.readthedocs.io/)

Вебинарный чат с поддержкой комнат и мгновенной доставкой сообщений через WebSockets.

## Содержание
- [Особенности](#особенности)
- [Технологии](#технологии)
- [Установка](#установка)
- [Настройка](#настройка)
- [Использование](#использование)

## Особенности

- Создание и управление чат-комнатами через админ-панель Django
- Аутентификация пользователей (регистрация/вход/выход)
- Обмен сообщениями в реальном времени
- История сообщений в рамках комнаты
- Гибкая настройка бэкенда (InMemory/Redis)

## Технологии

- **Backend**: 
  - [Django 4.0.2](https://www.djangoproject.com/)
  - [Channels 3.0.4](https://channels.readthedocs.io/)
- **Frontend**: 
  - HTML
  - [Tailwind CSS](https://tailwindcss.com/)
- **База данных**: SQLite (по умолчанию)
- **Асинхронный слой**: 
  - `InMemoryChannelLayer` (разработка)
  - [Redis](https://redis.io/) (продакшен)

## Установка

1. Клонируйте репозиторий:
```bash
git clone https://github.com/LebedevOleg1/real-time-chat.git
cd real-time-chat