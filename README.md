# 👋 Привет, я Батраз Секинаев

### 🐍 Python Backend Developer | Django • FastAPI • Production-ready решения

[![Telegram](https://img.shields.io/badge/Telegram-@bsekinaev-0088cc?style=flat-square&logo=telegram)](https://t.me/bsekinaev)
[![Email](https://img.shields.io/badge/Email-bsekinaev@ya.ru-red?style=flat-square&logo=mail.ru)](mailto:bsekinaev@ya.ru)
[![GitHub](https://img.shields.io/badge/GitHub-bsekinaev-181717?style=flat-square&logo=github)](https://github.com/bsekinaev)
[![HH.ru](https://img.shields.io/badge/Резюме-на%20HH-black?style=flat-square&logo=headhunter)](https://hh.ru/resume/f592f1daff0ca097cb0039ed1f464856526463)

---
📍 Ставрополь, Россия | 🌍 Открыт к удалённой работе (full-time) | 💼 Ищу позицию Python Backend / AI-автоматизации

---

## 🗂️ Навигация
- [🎯 Обо мне](#-обо-мне)
- [🛠 Стек](#-технологический-стек)
- [🚀 Проекты](#-ключевые-проекты)
- [📬 Контакты](#-давайте-работать-вместе)

---

## 🎯 Обо мне

Python-разработчик с фокусом на **надёжные backend-сервисы**. Создаю решения, которые работают в production: с тестами, мониторингом, CI/CD и продуманной архитектурой.

**Что я приношу в команду:**
- ✅ Опыт проектирования сложной бизнес-логики: транзакции, защита от race condition, ролевая модель
- ✅ Практику асинхронной обработки задач (Celery + Redis) и оптимизации запросов к БД
- ✅ Привычку писать тестируемый код и автоматизировать рутину (GitHub Actions, Docker)
- ✅ Понимание полного цикла: от проектирования API до деплоя и мониторинга

---

## 🛠 Технологический стек

**Backend:** ![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-4.2-092E20?style=flat-square&logo=django) ![DRF](https://img.shields.io/badge/DRF-3.14-red?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask)

**Базы данных:** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite)

**Асинхронность:** ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery)

**DevOps:** ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker) ![GitHub Actions](https://img.shields.io/badge/CI/CD-2088FF?style=flat-square&logo=githubactions) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux)

**Тесты:** ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest)

**API & Auth:** ![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=jsonwebtokens) ![OAuth](https://img.shields.io/badge/OAuth-2.0-3C3C3C?style=flat-square) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger)

**Мониторинг:** ![Glitchtip](https://img.shields.io/badge/Glitchtip-Sentry_SDK-362D59?style=flat-square&logo=sentry)

---

## 🚀 Ключевые проекты

### 🛒 Retail Procurement API — Backend для автоматизации закупок
[![Django](https://img.shields.io/badge/Django-4.2-092E20?style=flat-square)](https://www.djangoproject.com/)
[![CI](https://github.com/bsekinaev/retail-procurement/actions/workflows/tests.yml/badge.svg)](https://github.com/bsekinaev/retail-procurement/actions)

> Дипломный проект курса «Python-разработчик» (Нетология). Полноценный backend для розничной сети с OAuth, очередями задач и мониторингом.

**Ключевые решения:**
- 🔐 JWT + OAuth 2.0 (Google/GitHub) с асинхронной загрузкой аватаров
- 🛡️ `select_for_update` + `transaction.atomic` против гонок при заказах
- ⚡ Кэширование каталога в Redis, оптимизация ORM-запросов
- 📨 Celery для email, импорта YAML-прайсов и обработки изображений
- 🧪 Интеграционные тесты (pytest), CI/CD, Swagger-документация
- 🐳 Docker Compose (PostgreSQL, Redis, worker, Django) с healthcheck

**🔗 [Посмотреть код →](https://github.com/bsekinaev/retail-procurement)**

---

### 🤖 Code Review Bot — Авто-ревьюер Python-кода в GitHub PR
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square)](https://fastapi.tiangolo.com/)
[![Docker](https://img.shields.io/badge/Docker-✓-2496ED?style=flat-square)](https://www.docker.com/)
[![CI](https://github.com/bsekinaev/code-review-bot/actions/workflows/deploy.yml/badge.svg)](https://github.com/bsekinaev/code-review-bot/actions)

> GitHub App, который автоматически проверяет код в Pull Request и оставляет комментарии только по изменённым строкам.

**Особенности:**
- 🎯 Парсинг unified diff → фильтрация предупреждений по новым строкам
- ⚙️ Конфигурация через `.codereview.yml` в репозитории клиента
- 🔒 Вебхуки с HMAC-подписью, GitHub App с JWT
- 🚀 Авто-деплой на VPS через GitHub Actions после тестов

**🔗 [Посмотреть код →](https://github.com/bsekinaev/code-review-bot)**

---

### 🆙 Upscale Service — Асинхронный сервис апскейлинга изображений
[![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square)](https://flask.palletsprojects.com/)
[![Celery](https://img.shields.io/badge/Celery-✓-37814A?style=flat-square)](https://docs.celeryq.dev/)

> Микросервис для увеличения разрешения изображений через нейросеть EDSR с очередью задач.

**Технические решения:**
- 🔄 Celery + Redis для фоновой обработки без блокировки
- 💾 Модель загружается один раз, изображения — потоково
- 🧪 Юнит-тесты для критических компонентов

**🔗 [Посмотреть код →](https://github.com/bsekinaev/upscale_service)**

---

### 🏢 Org Structure API — REST API организационной структуры
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-✓-316192?style=flat-square)](https://www.postgresql.org/)

> API для управления иерархией департаментов с защитой от циклических ссылок и каскадным удалением.

**Ключевые фичи:**
- 🌳 Защита от циклов при перемещении департаментов
- 🗑️ Каскадное удаление с зависимостями
- 🧪 Полный набор тестов (factory-boy)

**🔗 [Посмотреть код →](https://github.com/bsekinaev/org-structure-api)**

---

## 📦 Другие проекты

| Проект                                                        | Описание | Стек |
|---------------------------------------------------------------|----------|------|
| **[UserManager](https://github.com/bsekinaev/UserManager)** | CRUD-приложение для управления пользователями. Задача для Digital агентства «Победа» (Нетология). **Production-ready**: Docker, pytest (~98%), CI/CD, Gunicorn, healthcheck. [Release v2.0.0](https://github.com/bsekinaev/UserManager/releases/tag/v2.0.0) | Flask, Vanilla JS, Docker, pytest, GitHub Actions |
| **[LinguaBot](https://github.com/bsekinaev/LinguaBot)**       | Telegram-бот для изучения английского с интервальными повторениями | Python, PostgreSQL, Telegram API |
| **[VKinder](https://github.com/bsekinaev/VKinder)**           | Бот для поиска пар в ВКонтакте по критериям | Python, VK API, SQLAlchemy |
| **[FastAPI Ads API](https://github.com/bsekinaev/FastAPI)**   | CRUD API объявлений с ролями и пагинацией | FastAPI, JWT, SQLite |
| **[Habr Parser](https://github.com/bsekinaev/Habr_parser)**   | Многопоточный парсер статей с Хабра | Python, BeautifulSoup, threading |

👉 [Посмотреть все репозитории →](https://github.com/bsekinaev?tab=repositories)

---

## 📚 Сейчас изучаю и внедряю

- 🧠 **PostgreSQL**: углублённая оптимизация запросов, планировщик, индексы
- ☸️ **Kubernetes**: оркестрация контейнеров после Docker Compose
- 🏗️ **Микросервисы**: паттерны взаимодействия, брокеры сообщений (RabbitMQ/Kafka)
- 🤖 **AI-интеграции**: работа с LLM-апи, RAG-подходы, векторные БД

---

## 🎯 Мои цели на ближайшее время

- [x] Освоить Docker и CI/CD (GitHub Actions)
- [x] Пройти 50 задач на LeetCode
- [x] Получить диплом Нетологии (расширенный курс Python-разработчик)
- [ ] Опубликовать технический разбор Retail Procurement API на Хабре
- [ ] Добавить e2e-тесты в ключевые проекты
- [ ] Реализовать AI-проект с LLM-интеграцией для портфолио
- [ ] Внести вклад в open-source (Django/DRF или FastAPI)

---

## 📊 GitHub Статистика

<div align="center">

![Profile Stats](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=bsekinaev&theme=github)
![GitHub Streak](https://streak-stats.demolab.com/?user=bsekinaev&theme=default)

</div>

---

## 💡 Мои принципы разработки

```python
def my_development_principles():
    return {
        "code_quality": "Чистый, читаемый и документированный код",
        "testing": "Тестирование критических компонентов",
        "documentation": "Понятная документация для каждого проекта",
        "continuous_learning": "Постоянное изучение новых технологий",
        "problem_solving": "Фокус на решении реальных проблем",
    }
```

---

## 📬 Давайте работать вместе!

Я ищу **удалённую позицию Python Backend Developer** (full-time), где смогу:
- Разрабатывать и масштабировать backend-сервисы
- Работать с интересными техническими задачами и современным стеком
- Расти как инженер в сильной команде

🎯 **Зарплатные ожидания:** 100–150 тыс. ₽ (на испытательный срок — 80–100 тыс. ₽)

### 📩 Свяжитесь со мной:
- 💬 **Telegram:** [@bsekinaev](https://t.me/bsekinaev) *(предпочтительный способ связи)*
- ✉️ **Email:** [bsekinaev@ya.ru](mailto:bsekinaev@ya.ru)
- 💼 **Резюме:** [HH.ru](https://hh.ru/resume/f592f1daff0ca097cb0039ed1f464856526463) | [Хабр Карьера](https://career.habr.com/bsekinaev)

---
