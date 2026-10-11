<div align="center">

# Батраз Секинаев

**Python Backend Developer · API · Integrations · Background Jobs**

FastAPI · Django/DRF · PostgreSQL · Redis · Celery · Docker · pytest

[Резюме на HH.ru](https://hh.ru/resume/f592f1daff0ca097cb0039ed1f464856526463) · [Telegram](https://t.me/bsekinaev) · [Email](mailto:bsekinaev@ya.ru)

**Открыт к удалённой работе Python Backend Developer**

</div>

## Обо мне

Разрабатываю backend-сервисы на Python: REST API, интеграции с внешними системами, фоновые задачи и обработку событий. Мой основной стек — **FastAPI, Django/DRF, PostgreSQL, SQLAlchemy, Redis, Celery и Docker**. Пишу тесты на pytest, работаю с GitHub Actions и миграциями БД.

Дополнительное направление — AI/LLM-интеграции, RAG и браузерная автоматизация с Playwright. В проектах уделяю внимание идемпотентности, обработке ошибок, наблюдаемости и безопасной работе с внешними API.

## Командный опыт

**Победа Digital / EGO · Python Backend Developer (стажировка, июнь — сентябрь 2026)**

Работал над backend-интеграциями в B2B-платформе управления репутацией, дорабатывал существующий код и участвовал в тестировании изменений. После завершения стажировки продолжаю выполнять отдельные проектные задачи.

- **Otzovik.com:** интеграция площадки без публичного API — Playwright-сессии, получение, нормализация и дедупликация отзывов.
- **MAX:** доработка обработки комментариев и публикаций, inline-клавиатур и событий.
- **Универсальный коннектор (POC):** типизированные манифесты, чтение данных через HTTP/DOM, пагинация и разделение AI Discovery и детерминированного Runtime.

Код корпоративной платформы не публикую. Здесь представлены мои собственные проекты и открытые технические примеры.

## Избранные проекты

### [Retail Procurement API](https://github.com/bsekinaev/retail-procurement) · Django/DRF

**Дипломный проект:** API для закупок, поставщиков, каталога, корзины и заказов.

- Транзакционное оформление заказов: `transaction.atomic` и `select_for_update` для защиты остатков.
- JWT, OAuth2, Redis-кэш, Celery-задачи и миграции.
- [Исходники](https://github.com/bsekinaev/retail-procurement) · [Тесты](https://github.com/bsekinaev/retail-procurement/tree/main/tests) · [GitHub Actions](https://github.com/bsekinaev/retail-procurement/actions)

### [ТАТТУТУЮ / TATTOTOYOU](https://github.com/bsekinaev/tattotoyou) · FastAPI

**Личный продуктовый MVP:** Telegram-ассистент для тату-студии с AI и базой знаний.

- Webhook → PostgreSQL Inbox → Celery → Outbox → Telegram: идемпотентность и повторная доставка.
- PostgreSQL, SQLAlchemy, Alembic, Redis/Lua rate limiting, GigaChat и RAG.
- [Исходники](https://github.com/bsekinaev/tattotoyou/tree/main/src) · [Тесты](https://github.com/bsekinaev/tattotoyou/tree/main/tests) · [GitHub Actions](https://github.com/bsekinaev/tattotoyou/actions)

### [AI Code Review Bot](https://github.com/bsekinaev/code-review-bot) · FastAPI / GitHub App

**Личный инструмент:** анализ изменённых строк в Pull Request через Ruff и GigaChat.

- Проверка подписи GitHub webhook, GitHub App JWT и diff-aware фильтрация замечаний.
- Celery, PostgreSQL; статический анализ сохраняется при недоступности AI API.
- [Исходники](https://github.com/bsekinaev/code-review-bot/tree/main/app) · [Тесты](https://github.com/bsekinaev/code-review-bot/tree/main/tests) · [GitHub Actions](https://github.com/bsekinaev/code-review-bot/actions)

### [CUDY Home Gateway](https://github.com/bsekinaev/cudy-home-gateway) · OpenWrt / Shell / ucode

**Личный инфраструктурный проект в разработке:** управление состоянием домашнего шлюза и безопасная диагностика.

- Health/incident engine, Telegram-уведомления, журналирование и сценарии восстановления.
- Ограниченные действия с подтверждением; data plane роутера остаётся независимым от control plane.
- [Архитектура](https://github.com/bsekinaev/cudy-home-gateway/blob/main/docs/ARCHITECTURE.md) · [Матрица приёмки](https://github.com/bsekinaev/cudy-home-gateway/blob/main/docs/ACCEPTANCE.md) · [GitHub Actions](https://github.com/bsekinaev/cudy-home-gateway/actions)
- **Статус:** разработка и приёмка продолжаются; релиз v1.0.0 не заявлен.

## Дополнительные проекты

- [Org Structure API](https://github.com/bsekinaev/org-structure-api) — FastAPI, PostgreSQL и иерархия подразделений.
- [Upscale Service](https://github.com/bsekinaev/upscale_service) — Flask, Celery, Redis и асинхронная обработка изображений.

## Стек и практики

| Направление | Инструменты |
| --- | --- |
| Backend | Python, FastAPI, Django, Django REST Framework, Flask, REST, OpenAPI |
| Данные | PostgreSQL, SQLAlchemy, Django ORM, Alembic, Redis |
| Асинхронность | Celery, asyncio, webhooks, retry/backoff |
| Качество | pytest, Ruff, Git, code review, GitHub Actions |
| Инфраструктура | Docker, Docker Compose, Linux, Nginx |
| Интеграции | Telegram Bot API, GitHub API, Playwright, GigaChat, OAuth2/JWT, RAG |

## Контакты

[Telegram: @bsekinaev](https://t.me/bsekinaev) · [Email: bsekinaev@ya.ru](mailto:bsekinaev@ya.ru) · [Резюме](https://hh.ru/resume/f592f1daff0ca097cb0039ed1f464856526463)
