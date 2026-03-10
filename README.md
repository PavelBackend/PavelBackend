# Самохин Павел — Python Backend Developer

> Backend-инженер с 3+ годами опыта в высоконагруженных и продуктовых системах (платежи, realtime, очереди, PostgreSQL, CI/CD).

---

## 📌 О себе

Привет! Я Python Backend Developer. Проектирую архитектуру и отвечаю за стабильность продакшена.
Имею опыт в платежных системах, real-time коммуникациях, очередях сообщений и CI/CD.

<details>
<summary><h2>Опыт работы 3+ года:</h2></summary>
  <h4>
    <a href="https://kareta-egame.ru" target="_blank" rel="noopener noreferrer">
      <span>Kareta-egame</span>
    </a>
  </h4>
  <div>
    <span>Python Backend Developer</span>
    <span>Февраль 2024 — настоящее время</span>
  </div>
  <div>
    <h4>Обязанности:</h4>
    <br><strong>Мобильное приложение для организации игровых турниров с призовым фондом.</strong>
    <br><br><strong>1. Платежи и монетизация</strong>
    <br>- Руководил процессом интеграции безакцептной оплаты в 1 клик через API Т-Банка по картам и СБП, увеличив выручку компании на 10 млн. руб за первый месяц.
    <br><br><strong>2. Оптимизация производительности</strong>
    <br>- Перепроектировал backend-агрегацию данных и схему API-ответов, сократив время ответа с ~5s до ~200ms за счёт устранения N+1 запросов и избыточных вычислений.
    <br><br><strong>3. CI/CD и инфраструктура</strong>
    <br>- Спроектировал zero-downtime CI/CD-флоу, обеспечив быстрые и безопасные релизы без остановки сервиса.
    <br><br><strong>4. Проектирование БД</strong>
    <br>- Спроектировал схему БД для турнирной платформы (пользователи, команды, турниры, транзакции, статусы) с использованием PostgreSQL, триггеров и фоновых задач Celery.
    <br><br><strong>5. Real-time и коммуникации</strong>
    <br>- Спроектировал архитектуру real-time обновления ленты постов, чатов и уведомлений приложения при помощи WebSockets.
    <br><br><strong>6. Хранение файлов</strong>
    <br>- Интегрировал загрузку изображений партициями через AWS S3.
    <br><br><strong>7. Управление командой</strong>
    <br>- Управлял командой стажёров, наставлял, декомпозировал задачи, делегируя несложные задачи по backend-части на FastAPI.
    <br><br><strong>8. Тестирование</strong>
    <br>- Покрыл ключевые бизнес-сценарии unit и интеграционными тестами, повысив стабильность релизов.
  </div>
  <h4>
    <a href="https://arevord.com" target="_blank" rel="noopener noreferrer">
      <span>Arevord</span>
    </a>
  </h4>
  <div>
    <span>Python Backend Developer</span>
    <span>Январь 2023 — Февраль 2024</span>
  </div>
  <div>
    <h4>Обязанности:</h4>
    <br><strong>Web-приложение для мониторинга и оценки эффективности коммуникаций.</strong>
    <br><br><strong>1. Data Pipeline</strong>
    <br>- Спроектировал pipeline обработки данных (приём данных с сервиса парсинга → RabbitMQ → NLP кластеризация → ElasticSearch → API) для обработки новостей с 50К источников, обеспечив асинхронную и масштабируемую обработку потока данных даже в пиковых нагрузках.
    <br><br><strong>2. Рефакторинг и архитектура</strong>
    <br>- Провёл полный рефактор легаси-кода и спроектировал новую отказоустойчивую архитектуру на Django + DRF.
    <br><br><strong>3. NLP-интеграция</strong>
    <br>- Интегрировал NLP-скрипт на сервер в фоновый процесс Celery для автоматической кластеризации до 10K новостей в час в связанные события.
  </div>
</details>

## Ниже представлены мои навыки и проекты.

### Веб-фреймворки и серверы
![FastAPI](https://img.shields.io/badge/FastAPI-009588?logo=fastapi&logoColor=white) * ![Django](https://img.shields.io/badge/Django-0C4B33?logo=django&logoColor=white) *
![Django REST Framework](https://img.shields.io/badge/Django%20REST%20Framework-2C2C2C?logo=django&logoColor=white) * ![Uvicorn](https://img.shields.io/badge/Uvicorn-2094f3?logo=uvicorn&logoColor=white) *
![Gunicorn](https://img.shields.io/badge/Gunicorn-298729?logo=gunicorn&logoColor=white)

### Базы данных и кэширование
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-396c94?logo=postgresql&logoColor=white) * ![Redis](https://img.shields.io/badge/Redis-d93327?logo=redis&logoColor=red) *
![MySQL](https://img.shields.io/badge/MySQL-3E6E93?logo=mysql&logoColor=white) * ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) *
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black) * ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-B00?logo=sqlalchemy&logoColor=white) *
![Django ORM](https://img.shields.io/badge/Django%20ORM-0C4B33?logo=django&logoColor=white)

### Асинхронность и задачи
![Celery](https://img.shields.io/badge/Celery-348613?logo=celery&logoColor=white) * ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white) *
![AsyncIO](https://img.shields.io/badge/AsyncIO-3776AB?logo=python&logoColor=white) * ![WebSockets](https://img.shields.io/badge/WebSockets-black?logo=websocket&logoColor=white)

### Тестирование и CI/CD
![Pytest](https://img.shields.io/badge/Pytest-FF4500?logo=pytest&logoColor=white) * ![Unittest](https://img.shields.io/badge/Unittest-3776AB?logo=python&logoColor=white) *
![CI/CD](https://img.shields.io/badge/CI/CD-278cff?logo=githubactions&logoColor=white) * ![Swagger](https://img.shields.io/badge/Swagger-white?logo=swagger&logoColor=black)

### Облачные сервисы и хранение
![AWS S3](https://img.shields.io/badge/AWS%20S3-232f3e?logo=amazonaws&logoColor=white) * ![ELK Stack](https://img.shields.io/badge/ELK%20Stack-005571?logo=elastic&logoColor=white)

### Контейнеризация и оркестрация
![Docker](https://img.shields.io/badge/Docker-00084d?logo=docker&logoColor=white) * ![Docker Compose](https://img.shields.io/badge/Docker%20Compose-00084d?logo=docker&logoColor=white) *
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)

### Фронтенд
![React](https://img.shields.io/badge/React-404756?logo=react&logoColor=61DAFB) * ![JavaScript](https://img.shields.io/badge/JavaScript-f7e025?logo=javascript&logoColor=white) *
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?logo=typescript&logoColor=white) * ![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-04AA6D?logo=html5&logoColor=white)

### Языки и утилиты
![Python](https://img.shields.io/badge/Python-2b5b84?logo=python&logoColor=white) * ![Linux](https://img.shields.io/badge/Linux-f9cb09?logo=linux&logoColor=black) *
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) * ![GitHub](https://img.shields.io/badge/GitHub-white?logo=github&logoColor=black) *
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?logo=gitlab&logoColor=white) * ![Nginx](https://img.shields.io/badge/Nginx-00B140?logo=nginx&logoColor=white)

### Управление проектами
![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white) * ![Scrum](https://img.shields.io/badge/Scrum-6DB33F?logo=scrumalliance&logoColor=white)

---

## 🧩 Мои проекты

### 1. Kareta-egame — Турнирная платформа
**Описание:**
Мобильное приложение для организации игровых турниров с призовым фондом. Интеграция платежей через API Т-Банка, real-time обновления через WebSockets, управление командами и турнирами.

🛠 Технологии: `Python`, `FastAPI`, `RabbitMQ`, `PostgreSQL`, `Redis`, `AWS S3`, `Kubernetes`, `Celery`, `CI/CD`, `WebSockets`.

**Детали:**
- **Какой эффект достигнут?**
Интеграция безакцептной оплаты увеличила выручку на 10 млн. руб/мес. Оптимизация API сократила время ответа с ~5s до ~200ms. Zero-downtime деплой обеспечил безостановочные релизы.

---

### 2. Arevord — Мониторинг коммуникаций
**Описание:**
Web-приложение для мониторинга и оценки эффективности коммуникаций. Pipeline обработки новостей с 50К источников через RabbitMQ, NLP-кластеризацию и ElasticSearch.

🛠 Технологии: `Python`, `Django`, `Django REST Framework`, `RabbitMQ`, `PostgreSQL`, `Redis`, `Docker`, `ELK`, `Celery`.

**Детали:**
- **Какой эффект достигнут?**
Спроектирован масштабируемый pipeline обработки данных. NLP-кластеризация обрабатывает до 10K новостей в час. Полный рефакторинг легаси-кода с новой отказоустойчивой архитектурой.

---

## 📬 Связь со мной
📧 Email: pavelsamo555@gmail.com
<br>💬 Telegram: [@PavelBackendDev](https://t.me/PavelBackendDev)
<br>🐙 GitHub: [PavelBackend](https://github.com/PavelBackend)
<br>📄 [Резюме (Google Drive)](https://drive.google.com/file/d/1kHW8oKLg-txXA-asjITJRRnBvl_qMXyj/view?usp=sharing)

---

## 📚 Иностранные языки
- Русский (носитель)
- Английский (C1)
