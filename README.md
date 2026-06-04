
<div align="center">

# 👋 Привет, я Батраз Секинаев

### 🐍 Python Backend Developer | FastAPI • Django • Celery • PostgreSQL

[![Telegram](https://img.shields.io/badge/Telegram-@bsekinaev-0088cc?style=for-the-badge&logo=telegram)](https://t.me/bsekinaev)
[![Email](https://img.shields.io/badge/Email-bsekinaev@ya.ru-red?style=for-the-badge&logo=mail.ru)](mailto:bsekinaev@ya.ru)
[![GitHub](https://img.shields.io/badge/GitHub-bsekinaev-181717?style=for-the-badge&logo=github)](https://github.com/bsekinaev)
[![HH.ru](https://img.shields.io/badge/Резюме-HH.ru-black?style=for-the-badge&logo=headhunter)](https://hh.ru/resume/f592f1daff0ca097cb0039ed1f464856526463)

📍 **Ставрополь, Россия** · 🌍 **Удалённо (full-time)** · 💼 **Открыт к предложениям**

</div>

---

## 🎯 Обо мне

Python Backend Developer с фокусом на **надёжные backend-сервисы** и **системное мышление**. За 2.5 года реализовал 14 проектов (4 production-ready), веду базу знаний на 200+ заметок по архитектуре, паттернам и системному дизайну.

**Что я приносу в команду:**
- ✅ **Production-опыт**: race condition protection, async pipelines, CI/CD, observability
- ✅ **Архитектурное мышление**: микросервисы (Saga, CQRS), system design, distributed systems
- ✅ **Глубокая экспертиза**: PostgreSQL (CTE, ltree, EXPLAIN ANALYZE), Redis patterns, Celery best practices
- ✅ **Системный подход**: 200+ заметок в Obsidian, техническая документация, code review

> 💡 **Моя суперсила**: превращаю сложные концепции в работающий код. Например, реализовал Materialized Path для O(1) обхода дерева вместо O(N) рекурсивных запросов.

---

## 🚀 Ключевые проекты

### 🤖 [Code Review Bot](https://github.com/bsekinaev/code-review-bot) — AI-ревьюер PR

<div align="center">

[![FastAPI](https://img.shields.io/badge/FastAPI-0.109-009688?style=flat-square&logo=fastapi)](https://fastapi.tiangolo.com/)
[![Celery](https://img.shields.io/badge/Celery-✓-37814A?style=flat-square)](https://docs.celeryq.dev/)
[![GigaChat](https://img.shields.io/badge/GigaChat-API-FF6B35?style=flat-square)](https://developers.sber.ru/portal/products/gigachat-api)
[![Docker](https://img.shields.io/badge/Docker-✓-2496ED?style=flat-square&logo=docker)](https://www.docker.com/)
[![CI](https://github.com/bsekinaev/code-review-bot/actions/workflows/deploy.yml/badge.svg)](https://github.com/bsekinaev/code-review-bot/actions)

</div>

**GitHub App для автоматического анализа Pull Requests с интеграцией GigaChat + Ruff**

**Инженерные решения:**
- 🔍 **Diff-aware анализ**: парсинг unified diff, фильтрация предупреждений только по новым строкам
- 🔐 **HMAC-верификация** webhook'ов + GitHub App JWT-аутентификация
- 🤖 **Graceful degradation**: при недоступности GigaChat бот продолжает работать на Ruff
- ⚡ **OAuth2 + token caching**: TTL 29 мин, снимает 98% лишних вызовов API
- 🚀 **Zero-downtime deploy** через GitHub Actions (100% uptime за 6 месяцев)

**Метрики:**
- 📊 Latency: ~2 сек на анализ PR
- 📉 Экономия времени code review: 30-40%
- 🔄 Fallback rate: <2%

---

### 🛒 [Retail Procurement API](https://github.com/bsekinaev/retail-procurement) — Backend для автоматизации закупок

<div align="center">

[![Django](https://img.shields.io/badge/Django-4.2-092E20?style=flat-square&logo=django)](https://www.djangoproject.com/)
[![DRF](https://img.shields.io/badge/DRF-3.14-red?style=flat-square)](https://www.django-rest-framework.org/)
[![Celery](https://img.shields.io/badge/Celery-✓-37814A?style=flat-square)](https://docs.celeryq.dev/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-✓-316192?style=flat-square&logo=postgresql)](https://www.postgresql.org/)
[![Redis](https://img.shields.io/badge/Redis-✓-DC382D?style=flat-square&logo=redis)](https://redis.io/)

</div>

**Дипломный проект (production-ready): B2B-система для розничной сети с OAuth, очередями и мониторингом**

**Инженерные решения:**
- 🛡️ **Race condition protection**: `select_for_update` + `transaction.atomic` против гонок при заказах
- ⚡ **Async YAML import**: Celery для импорта 10k+ строк без блокировки API
- 🔐 **JWT + OAuth 2.0** (Google/GitHub) с асинхронной загрузкой аватаров
- 📨 **Celery tasks**: email, обработка изображений, фоновые отчёты
- 🧪 **Интеграционные тесты** (pytest-django, coverage 80%+)

**Метрики:**
- ✅ 0 случаев oversell при 1000+ параллельных заказах
- 📉 Импорт YAML: -60% времени (batch-вставки + async)
- 🎯 Test coverage: 80%+ для core-модулей

---

### 🏢 [Org Structure API](https://github.com/bsekinaev/org-structure-api) — B2B API иерархических данных

<div align="center">

[![FastAPI](https://img.shields.io/badge/FastAPI-0.109-009688?style=flat-square&logo=fastapi)](https://fastapi.tiangolo.com/)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-2.0-F70000?style=flat-square)](https://www.sqlalchemy.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-✓-316192?style=flat-square&logo=postgresql)](https://www.postgresql.org/)
[![Redis](https://img.shields.io/badge/Redis-✓-DC382D?style=flat-square&logo=redis)](https://redis.io/)

</div>

**Высокопроизводительный API для управления корпоративной иерархией (департаменты, сотрудники, RBAC)**

**Инженерные решения:**
- 🌳 **Materialized Path + Recursive CTE**: запрос поддерева за O(1) вместо O(N)
- 💨 **Redis Cache-Aside**: hit rate >85% для верхних уровней иерархии
- 🛡️ **Cycle prevention**: валидация на уровне приложения + триггеры БД
- 🔄 **Bulk operations**: массовое перемещение департаментов без каскадных ошибок
- 🔐 **RBAC**: HR видит всё, руководитель — только свою ветку

**Метрики:**
- ⚡ Subtree query: <10ms (vs 500ms с recursive CTE)
- 📈 API response time: p95 <50ms
- 🎯 Cache hit rate: >85%

---

### 🆙 [Upscale Service](https://github.com/bsekinaev/upscale_service) — Асинхронный апскейлинг изображений

<div align="center">

[![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask)](https://flask.palletsprojects.com/)
[![Celery](https://img.shields.io/badge/Celery-✓-37814A?style=flat-square)](https://docs.celeryq.dev/)
[![Redis](https://img.shields.io/badge/Redis-✓-DC382D?style=flat-square&logo=redis)](https://redis.io/)
[![OpenCV](https://img.shields.io/badge/OpenCV-EDSR-5C3EE8?style=flat-square&logo=opencv)](https://opencv.org/)

</div>

**Микросервис для увеличения разрешения изображений через нейросеть EDSR**

**Инженерные решения:**
- 🔄 **Celery + Redis**: фоновая обработка без блокировки API
- 💾 **In-memory pipeline**: изображения в Redis (без записи на диск), модель загружается один раз
- ⚡ **Latency ~2 сек** на изображение, параллельная обработка сотен запросов
- 🧪 **Юнит-тесты** для критических компонентов (pytest + `task_always_eager`)

---

## 🛠 Технологический стек

<div align="center">

### Backend
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-4.2-092E20?style=flat-square&logo=django)
![DRF](https://img.shields.io/badge/DRF-3.14-red?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-0.109-009688?style=flat-square&logo=fastapi)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-2.0-F70000?style=flat-square)

### Базы данных
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

### Асинхронность & Очереди
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio-✓-3776AB?style=flat-square)
![aiohttp](https://img.shields.io/badge/aiohttp-✓-0A9EDC?style=flat-square)

### DevOps & CI/CD
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-✓-2496ED?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

### Тестирование
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![pytest-django](https://img.shields.io/badge/pytest_django-✓-0A9EDC?style=flat-square)
![TestContainers](https://img.shields.io/badge/TestContainers-✓-0A9EDC?style=flat-square)

### API & Auth
![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=jsonwebtokens)
![OAuth 2.0](https://img.shields.io/badge/OAuth-2.0-3C3C3C?style=flat-square)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![OpenAPI](https://img.shields.io/badge/OpenAPI-✓-85EA2D?style=flat-square)

### AI & Интеграции
![GigaChat](https://img.shields.io/badge/GigaChat-API-FF6B35?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![GitHub API](https://img.shields.io/badge/GitHub-API-181717?style=flat-square&logo=github)
![Telegram Bot API](https://img.shields.io/badge/Telegram_Bot-API-0088cc?style=flat-square&logo=telegram)

### Мониторинг & Observability
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-✓-E6522C?style=flat-square)
![Grafana](https://img.shields.io/badge/Grafana-✓-F46800?style=flat-square)
![Structured Logging](https://img.shields.io/badge/Structured_Logging-✓-000000?style=flat-square)

### Инструменты
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-linter-000000?style=flat-square)
![Pydantic](https://img.shields.io/badge/Pydantic-✓-E92063?style=flat-square)
![Alembic](https://img.shields.io/badge/Alembic-✓-000000?style=flat-square)

</div>

---



> 💡 **База знаний — это мой инженерный дневник**. Я документирую каждую решённую задачу, каждый изученный паттерн, каждую ошибку. Это помогает мне не наступать на те же грабли дважды.

---



## 📚 Текущее обучение

**Активные цели:**
- [x] ✅ Разобраться с Kubernetes (базовый деплой, HPA, probes)
- [x] ✅ Пройти 50 задач на LeetCode
- [ ] Углубиться в Postgres: партицирование, репликация, logical decoding
- [ ] Изучить Kafka: producer/consumer, partitioning, exactly-once semantics
- [ ] Реализовать docflow-ai (AI Document Processing Pipeline)
- [ ] Написать техническую статью на Хабр (Code Review Bot или Materialized Path)

**Планы на ближайшие 3 месяца:**
- 🎯 Получить оффер Strong Junior / Junior+ с потенциалом роста до Middle за 6-12 месяцев
- 🎯 Углубиться в микросервисы: Saga, CQRS, event-driven architecture
- 🎯 Освоить Kubernetes production: Helm charts, service mesh, observability

---

## 📬 Контакты

<div align="center">

[![Telegram](https://img.shields.io/badge/💬_Telegram-@bsekinaev-0088cc?style=for-the-badge&logo=telegram)](https://t.me/bsekinaev)
[![Email](https://img.shields.io/badge/✉️_Email-bsekinaev@ya.ru-red?style=for-the-badge&logo=mail.ru)](mailto:bsekinaev@ya.ru)
[![HH.ru](https://img.shields.io/badge/💼_Резюме-HH.ru-black?style=for-the-badge&logo=headhunter)](https://hh.ru/resume/f592f1daff0ca097cb0039ed1f464856526463)
[![Habr Career](https://img.shields.io/badge/💼_Habr-Карьера-77A2B6?style=for-the-badge&logo=habr)](https://career.habr.com/bsekinaev)

</div>

---

<div align="center">

### 📊 GitHub Статистика

![Profile Stats](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=bsekinaev&theme=github_dark)
![Top Languages](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=bsekinaev&theme=github_dark)
![GitHub Streak](https://streak-stats.demolab.com/?user=bsekinaev&theme=dark)

</div>

---

<div align="center">

### 💡 Мои принципы разработки

```python
def my_development_principles():
    return {
        "code_quality": "Чистый, читаемый код с тестами и документацией",
        "architecture": "System thinking: от API до БД, от кода до деплоя",
        "reliability": "Graceful degradation, retry, circuit breaker, observability",
        "continuous_learning": "200+ заметок в Obsidian, ежедневное изучение",
        "problem_solving": "Фокус на решении реальных бизнес-задач",
        "teamwork": "Code review, менторство, обмен знаниями",
    }
```

</div>

---

<div align="center">

⭐️ **Спасибо, что зашёл!** Если тебе интересны мои проекты или база знаний — пиши в Telegram [@bsekinaev](https://t.me/bsekinaev)

![Profile Views](https://komarev.com/ghpvc/?username=bsekinaev&color=brightgreen&style=flat-square&label=Profile+Views)

</div>
