# 👋 Привет, я Батраз!

### 🎯 **Python Backend Developer**

[![Telegram](https://img.shields.io/badge/Telegram-@bsekinaev-0088cc?style=flat&logo=telegram)](https://t.me/bsekinaev)
[![Email](https://img.shields.io/badge/Email-bsekinaev@ya.ru-red?style=flat&logo=mail.ru)](mailto:bsekinaev@ya.ru)
[![GitHub](https://img.shields.io/badge/GitHub-bsekinaev-black?style=flat&logo=github)](https://github.com/bsekinaev)

📍 **Ставрополь, Россия**
💼 **Открыт к сотрудничеству:** open-source проекты, стартапы, коммерческая разработка, удалённая работа.

---

## 🛠 **Технологический стек**

### **Backend**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-red?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)

### **Базы данных**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

### **DevOps & Инструменты**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

### **Тестирование**
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Factory Boy](https://img.shields.io/badge/Factory_Boy-FF6F00?style=for-the-badge)

### **Дополнительно**
![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-34A853?style=for-the-badge&logo=google&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

---

## 🚀 **Мои ключевые проекты**

### 🛒 Retail Procurement API — автоматизация закупок (дипломный проект)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-red?style=flat)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

Backend для автоматизации закупок в розничной сети с каталогом, корзиной, заказами.
*   **JWT-авторизация** с подтверждением email
*   Бизнес-логика с **защитой от race condition** (select_for_update)
*   **Асинхронная отправка** уведомлений и импорт товаров через Celery
*   **Права доступа** (IsSupplier, IsAdmin) и админские эндпоинты
*   **CI/CD** — GitHub Actions запускает тесты при пуше в main
*   **Контейнеризация** — Docker Compose (PostgreSQL, Redis, Django, Celery)
*   Экспорт товаров в CSV, пагинация, поиск, Swagger‑документация

**🔗 [Исходный код →](https://github.com/bsekinaev/retail-procurement)**

### 🤖 Code Review Bot — Автоматический ревьюер Python-кода в Pull Requests
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-ADFF2F?style=flat&logo=ruff&logoColor=black)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat&logo=telegram&logoColor=white)

Микросервис, который автоматически проверяет Python-код при создании или обновлении Pull Request на GitHub.
*   **Анализ только изменённых строк** — не спамит старыми предупреждениями
*   **Гибкая настройка** через `.codereview.yml` в репозитории клиента
*   **CI/CD** — автоматический деплой на VPS через GitHub Actions после тестов
*   **Контейнеризация** — Docker Compose с монтированием ключей и переменных
*   **Безопасность** — вебхуки с HMAC-подписью, GitHub App с JWT
*   **Уведомления** — результаты ревью дублируются в Telegram

**🔗 [Исходный код →](https://github.com/bsekinaev/code-review-bot)**

### 🆙 Upscale Service — Асинхронный сервис апскейлинга изображений
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

Сервис для увеличения разрешения изображений с помощью нейросети EDSR.
*   **Асинхронная обработка** через Celery + Redis без сохранения на диск
*   Модель загружается **единожды** и не перечитывается с диска
*   Три эндпоинта: загрузка, статус задачи, скачивание результата
*   Полная контейнеризация (Docker Compose)

**🔗 [Исходный код →](https://github.com/bsekinaev/upscale_service)**

### 🔐 FastAPI Ads API — Сервис объявлений с JWT и ролями
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

REST API для сервиса объявлений купли/продажи с аутентификацией, ролями и гибкой фильтрацией.
*   **JWT-аутентификация** и система ролей (USER/ADMIN)
*   Поиск объявлений с **пагинацией** и фильтрацией
*   Асинхронная работа с БД (SQLAlchemy 2.0 + aiosqlite)
*   Документация через Swagger UI, запуск через Docker

**🔗 [Исходный код →](https://github.com/bsekinaev/FastAPI)**

### 🤖 LinguaBot — Умный бот для изучения английского
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)

Telegram-бот с системой интервальных повторений.
*   Повышение запоминаемости на ~40% в тестовой группе
*   Расширенная статистика и аналитика ответов

**🔗 [Исходный код →](https://github.com/bsekinaev/LinguaBot)**

### ❤️ VKinder — Бот для поиска пар в VK
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![VK API](https://img.shields.io/badge/VK_API-0077FF)

Интеллектуальный поиск людей по критериям. Ведущий backend-разработчик в команде из 3 человек.

**🔗 [Исходный код →](https://github.com/bsekinaev/VKinder)**

### 📱 UserManager — Веб-приложение для управления пользователями
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)

Full-stack CRUD приложение с AJAX-обновлениями и валидацией.

**🔗 [Исходный код →](https://github.com/bsekinaev/UserManager)**

### 📰 Habr Parser — Многопоточный парсер статей
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-44CC11)

Инструмент для сбора и структурирования технических статей с Хабра.
*   Обрабатывает до 500 статей за один запуск

**🔗 [Исходный код →](https://github.com/bsekinaev/Habr_parser)**

---

### 📚 Другие проекты
*   **Org Structure API** — REST API организационной структуры на FastAPI + PostgreSQL [Ссылка](https://github.com/bsekinaev/org-structure-api)
*   **aiohttp-ads** — Асинхронное REST API с JWT на aiohttp [Ссылка](https://github.com/bsekinaev/aiohttp-ads)
*   **Cat & Dog Image Backup** — Автоматический бэкап изображений на Яндекс.Диск [Ссылка](https://github.com/bsekinaev/cat_and_dog)
*   **Portfolio** — Сайт-визитка с неоновым дизайном и живым API [Ссылка](https://github.com/bsekinaev/portfolio)

---
## 🎓 **Образование и сертификаты**
- **Нетология** – расширенный курс «Python-разработчик» (2026)
- **Ставропольский региональный многопрофильный колледж** – Программирование в компьютерных системах (2017)

---
## 📚 **Чему я сейчас учусь**
- **Kubernetes** – оркестрация контейнеров после Docker Compose
- **Алгоритмы и структуры данных** на LeetCode
- **PostgreSQL оптимизация** и индексы
- **Микросервисная архитектура** и брокеры сообщений

---

## 🎯 **Мои цели на ближайшее время**
- [x] Освоить Docker и Docker Compose
- [x] Изучить асинхронное программирование на практике
- [x] Создать полноценный REST API с FastAPI и аутентификацией
- [x] Разработать микросервисное приложение с оркестрацией через Docker Compose
- [x] Пройти 50 задач на LeetCode
- [ ] Внести вклад в популярный open-source проект
- [ ] Пройти сертификацию по облачным технологиям (AWS/GCP)

---

## 📊 **GitHub Статистика**

<div align="center">

![Profile Stats](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=bsekinaev&theme=github)
![Most Used Languages](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=bsekinaev&theme=github)
![GitHub Streak](https://streak-stats.demolab.com/?user=bsekinaev&theme=default)

</div>

---

## 💡 **Мои принципы разработки**

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

## 📫 **Связь со мной**


---
<div align="center">


[![Email](https://img.shields.io/badge/bsekinaev@ya.ru-Email-critical?style=for-the-badge&logo=mail.ru&logoColor=white)](mailto:bsekinaev@ya.ru)
[![Telegram](https://img.shields.io/badge/@bsekinaev-0088cc?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/bsekinaev)
[![GitHub](https://img.shields.io/badge/bsekinaev-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bsekinaev)

</div>
