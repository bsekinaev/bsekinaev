<div align="center">

# Батраз Секинаев

### Python Backend Developer

FastAPI · Django/DRF · PostgreSQL · Redis · Celery · Docker

[![Telegram](https://img.shields.io/badge/Telegram-@bsekinaev-0088cc?style=flat-square&logo=telegram)](https://t.me/bsekinaev)
[![Email](https://img.shields.io/badge/Email-b%40sekinaev.ru-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:b@sekinaev.ru)
[![HH.ru](https://img.shields.io/badge/Резюме-HH.ru-E1011C?style=flat-square)](https://hh.ru/resume/f592f1daff0ca097cb0039ed1f464856526463)

Ставрополь · удалённая работа · открыт к предложениям

</div>

## Обо мне

Python Backend Developer с фокусом на REST API, асинхронные сервисы и интеграции с внешними системами. В собственных и учебно-прикладных проектах работаю с FastAPI, Django/DRF, PostgreSQL, SQLAlchemy, Redis, Celery и Docker.

Реализовывал Telegram- и GitHub-webhook'и, фоновые задачи, транзакционную бизнес-логику, JWT/OAuth2-аутентификацию, интеграции с GigaChat, RAG, тестирование и CI через GitHub Actions.

Ищу позицию Python Backend Developer в продуктовой команде с практиками code review и автоматизированного тестирования.

## Основной стек

- **Backend:** Python, FastAPI, Django, Django REST Framework, SQLAlchemy, Pydantic
- **Data:** PostgreSQL, Redis, Alembic, Django ORM
- **Async:** Celery, asyncio, webhooks, retry/backoff
- **Quality:** pytest, Ruff, GitHub Actions, OpenAPI
- **Infrastructure:** Docker, Docker Compose, Linux, Nginx
- **Integrations:** Telegram Bot API, GitHub API, GigaChat API, JWT, OAuth2

## Ключевые проекты

### [TATTOTOYOU](https://github.com/bsekinaev/tattotoyou) — AI-ассистент для тату-студии

Telegram-ассистент для обработки типовых обращений клиентов и передачи сложных случаев мастеру.

- FastAPI webhook и асинхронная обработка через Celery + Redis
- PostgreSQL, SQLAlchemy и Alembic
- GigaChat и поиск контекста в базе знаний через RAG
- Redis + Lua rate limiting до постановки задач в очередь
- маскирование персональных данных, TLS-верификация и health endpoints
- Docker Compose, pytest, Ruff и GitHub Actions

### [Code Review Bot](https://github.com/bsekinaev/code-review-bot) — анализ Pull Request

GitHub App для автоматизированного анализа изменённого Python-кода через Ruff и GigaChat.

- diff-aware анализ только изменённых строк
- HMAC-проверка webhook'ов и GitHub App JWT
- FastAPI, Celery, Redis, PostgreSQL и Alembic
- graceful fallback на Ruff при недоступности AI
- Docker Compose, тесты и CI

### [Retail Procurement API](https://github.com/bsekinaev/retail-procurement) — автоматизация закупок

Дипломный backend-проект на Django/DRF для работы с каталогом, корзиной, заказами и поставщиками.

- JWT и OAuth2 через Google/GitHub
- транзакционное оформление заказа через `transaction.atomic` и `select_for_update`
- Celery-задачи для импорта YAML и уведомлений
- Redis-кэширование каталога
- pytest-django, Docker Compose и GitHub Actions

## Дополнительные проекты

- [Org Structure API](https://github.com/bsekinaev/org-structure-api) — FastAPI API для подразделений и сотрудников с древовидной структурой
- [Upscale Service](https://github.com/bsekinaev/upscale_service) — асинхронная обработка изображений через Celery и Redis

## Контакты

- Telegram: [@bsekinaev](https://t.me/bsekinaev)
- Email: [bsekinaev@ya.ru](mailto:bsekinaev@ya.ru)
- Резюме: [HH.ru](https://hh.ru/resume/f592f1daff0ca097cb0039ed1f464856526463)
