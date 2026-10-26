<div align="center">

# Батраз Секинаев

### Python Backend Developer · Backend Integrations

Python · FastAPI · Django/DRF · PostgreSQL · Redis · Celery · Docker · pytest

[![Telegram](https://img.shields.io/badge/Telegram-@bsekinaev-0088cc?style=flat-square&logo=telegram)](https://t.me/bsekinaev)
[![Email](https://img.shields.io/badge/Email-bsekinaev%40ya.ru-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:bsekinaev@ya.ru)
[![HH.ru](https://img.shields.io/badge/Resume-HH.ru-E1011C?style=flat-square)](https://hh.ru/resume/f592f1daff0ca097cb0039ed1f464856526463)
[![Habr Career](https://img.shields.io/badge/Profile-Habr%20Career-6799C6?style=flat-square)](https://career.habr.com/bsekinaev)

Ставрополь · рассматриваю удалённую работу

</div>

## Обо мне

Python Backend Developer. Разрабатываю REST API, интеграции внешних сервисов и фоновые обработчики. Основной стек: FastAPI, Django/DRF, PostgreSQL, SQLAlchemy, Redis, Celery, Docker и pytest. Дополнительно работаю с Playwright, webhooks и LLM/RAG.

**Командный опыт:** стажировка в «Победа Digital» / EGO, **25.06–25.09.2026**. После официального окончания выполнял отдельные проектные задачи; это не заявляется как продление стажировки или постоянное трудоустройство.

Ищу работу Python Backend Developer (Junior / Junior+). Интересны продуктовые команды, API, надёжные интеграции, тестирование и сопровождение сервисов.

## Опыт командной разработки — Победа Digital / EGO

B2B-платформа для управления репутацией и обработки отзывов.

- **Otzovik.com:** интеграция площадки без доступного публичного API: авторизованная браузерная сессия (Playwright), сбор и нормализация отзывов, дедупликация, сохранение данных, миграции и интеграция с существующими процессами платформы. В тестах на реальной площадке проверялись получение отзывов, повторное чтение и публикация ответа.
- **MAX:** доработка обработки комментариев и редактирования публикаций; работа с webhook-событиями, inline-клавиатурой, режимами MiniApp/Native, защитой от дублирования, регрессионным тестированием и совместимостью с существующим поведением.
- **Universal Reviews Connector (POC):** компоненты архитектуры AI Discovery → типизированный Connector Manifest / Operational Profile → универсальный детерминированный Runtime. Для Ozon Seller подтверждён read-only маршрут получения списка и деталей отзывов с UUID-корреляцией. Полная стабильность и сквозная приёмка всего POC **не заявляются**.

Работал в существующей кодовой базе с Git-ветками, слияниями, миграциями, unit/contract/regression и LIVE-проверками. Исходный код EGO закрыт; внутренние исходники и доступы не публикую.

## Основные публичные проекты

### [Retail Procurement API](https://github.com/bsekinaev/retail-procurement) — backend сервиса закупок

- Django REST Framework, PostgreSQL, JWT/OAuth2, API товаров, заказов и поставщиков.
- Транзакционное оформление заказов с блокировками `select_for_update`.
- Celery, Redis, Docker Compose, автоматические тесты и GitHub Actions.

### [TATTOTOYOU](https://github.com/bsekinaev/tattotoyou) — Telegram AI-ассистент для студии

- FastAPI webhook, PostgreSQL, SQLAlchemy, Alembic, Celery и Redis.
- Обработка сообщений, RAG-поиск по базе знаний и интеграция с LLM.
- Ограничение частоты запросов, тесты, Docker Compose и CI.

### [CUDY Home Gateway](https://github.com/bsekinaev/cudy-home-gateway) — инфраструктурный проект для OpenWrt

- Control plane домашнего шлюза: health/alerts, CLI, диагностика и Telegram read-only UI.
- Безопасные изменения с preflight/verification и контролем ошибок; проект не управляет сетевым data plane напрямую.
- Отдельный установочный baseline HGDEPLOY2 прошёл owner-проверки на реальном устройстве в октябре 2026. Текущая дорожная карта и новые изменения не объявляются полноценным production-релизом v1.0.

## Технологии

**Backend:** Python, FastAPI, Django/DRF, SQLAlchemy, Pydantic, REST API, HTTP, asyncio  
**Данные и фоновые процессы:** PostgreSQL, Django ORM, Alembic, Redis, Celery  
**Качество и инфраструктура:** pytest, Ruff, Git, GitHub Actions, Docker Compose, Linux  
**Интеграции:** Webhooks, Playwright, Telegram Bot API, OAuth2/JWT, GigaChat, RAG

## Контакты

- Telegram: [@bsekinaev](https://t.me/bsekinaev)
- Email: [bsekinaev@ya.ru](mailto:bsekinaev@ya.ru)
- [Резюме HH.ru](https://hh.ru/resume/f592f1daff0ca097cb0039ed1f464856526463)
- [Habr Career](https://career.habr.com/bsekinaev)

> Достижения по закрытой командной платформе описаны на уровне задач и подтверждённых проверок без публикации конфиденциальных данных.
