<div align="center">

# QPM — Quality Production Monitor

**Модульная платформа управления производством**  
*Modular Production Management Platform*

[![Live Demo](https://img.shields.io/badge/Live%20Demo-qpm--app.up.railway.app-D32F2F?style=for-the-badge)](https://qpm-app.up.railway.app)
[![Django](https://img.shields.io/badge/Django-5.2-092E20?style=for-the-badge&logo=django)](https://djangoproject.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Railway-4169E1?style=for-the-badge&logo=postgresql)](https://railway.app)

</div>

---

[🇷🇺 Русский](#-русский) · [🇬🇧 English](#-english)

### Что такое QPM?

QPM — это веб-платформа для управления производственными процессами, разработанная как замена Excel-таблицам и бумажным журналам. Система объединяет контроль качества, учёт дефектов, документооборот, управление задачами и аналитику в одном месте.

**Живая демонстрация:** [qpm-app.up.railway.app](https://qpm-app.up.railway.app)

---

### 🎯 Кому нужен QPM?

| Роль | Задача |
|------|--------|
| **Производственные компании** | Цифровизация контроля качества и учёта дефектов |
| **Операционные директора** | Единая картина по всем процессам в реальном времени |
| **HR и руководители** | Учёт персонала, посещаемость, задачи команды |
| **Технологи и ОТК** | Замеры ЛКП, регистрация дефектов, экспорт отчётов |
| **IT-директора** | Готовое white-label решение для внутренней автоматизации |

---

### 📦 Модули платформы

#### 🔍 Контроль качества
Замеры толщины ЛКП, шагрень, цветность. История по VIN номерам. Архив замеров с фильтрацией и аналитикой по трендам.

#### 🔎 Дефекты
Регистрация дефектов по линиям производства. Справочники дефектов, деталей, цветов по моделям. Методы устранения. Аналитика и экспорт в XLSX.

#### 🗂️ Реестры
Конструктор таблиц учёта — пользователь сам создаёт структуру. Типы полей: текст, число, дата, список, да/нет. Учёт остатков с историей операций (приход/расход). Аналитика и экспорт.

#### 📋 Таск-менеджер
Kanban-доски с drag & drop. Подзадачи, комментарии, назначение ответственных. История изменений.

#### 👥 Сотрудники
Учёт персонала, журнал посещаемости, рабочий календарь, профили сотрудников.

#### 📄 Документооборот
Версионирование файлов, уведомления адресатам, история изменений. Хранение в Backblaze B2.

#### 📊 Аналитика
Сводные дашборды по всем модулям. Тренды, динамика, фильтры по периодам.

#### 💬 Чат
Встроенный мессенджер — личные и групповые чаты. Push-уведомления.

---

### ⚙️ Технологии

```
Backend:    Django 5.2, Django REST Framework, PostgreSQL
Frontend:   Vanilla JS, HTML/CSS (без фреймворков)
Инфра:      Railway, Backblaze B2, Redis
Прочее:     Chart.js, openpyxl, APScheduler, WebSockets
```

---

### 🏭 Реальный кейс

Платформа разработана и внедрена на **автомобильном производстве** в Казахстане. Используется операторами контроля качества для регистрации дефектов ЛКП и замеров толщины покрытия.

**Что заменила:**
- Google Таблицы для учёта дефектов
- Бумажные журналы замеров
- Excel-отчёты по качеству

---

### 💡 Ключевые особенности

- **Адаптивный дизайн** — работает на планшете прямо в цехе
- **Тёмная тема** — для работы в условиях производства
- **Глобальный поиск** — по всем модулям включая VIN
- **QR-сканер** — поиск по штрихкодам прямо из браузера
- **Система уведомлений** — реальное время, push на мобиле
- **Ролевая модель** — суперадмин, администратор, пользователь
- **Модульный доступ** — каждому пользователю доступны только нужные модули

---

### 👨‍💻 Разработчик

**Islamov Ildar** — Full-stack разработчик, специализация на производственных системах и внутренней автоматизации.

- 🔗 [LinkedIn](https://www.linkedin.com/in/islamov-ildar/)
- ✈️ [Telegram](https://t.me/created_by_islamov_ildar)
- 🌐 [Demo](https://qpm-app.up.railway.app)

> *QPM создан как доказательство того, что внутренние инструменты не обязаны быть некрасивыми и неудобными. Это MVP платформы которая масштабируется под любой производственный процесс.*

---
---

## 🇬🇧 English

### What is QPM?

QPM is a web-based production management platform built to replace Excel spreadsheets and paper journals. It combines quality control, defect tracking, document management, task management, and analytics into a single system.

**Live Demo:** [qpm-app.up.railway.app](https://qpm-app.up.railway.app)

---

### 🎯 Who is it for?

| Role | Use case |
|------|----------|
| **Manufacturing companies** | Digitize quality control and defect tracking |
| **Operations directors** | Real-time unified view of all processes |
| **HR & team leads** | Staff management, attendance, team tasks |
| **QC engineers & technologists** | Coating measurements, defect registration, reports |
| **IT directors** | Ready-made white-label solution for internal automation |

---

### 📦 Platform Modules

#### 🔍 Quality Control
Paint coating thickness measurements, orange peel, colorimetry. Full history by VIN number. Archive with filtering and trend analytics.

#### 🔎 Defects
Defect registration by production lines. Reference books for defects, parts, and colors by car model. Repair methods. Analytics and XLSX export.

#### 🗂️ Registries
Table builder — users create their own data structure. Field types: text, number, date, dropdown, boolean. Balance tracking with operation history (income/expense). Analytics and export.

#### 📋 Task Manager
Kanban boards with drag & drop. Subtasks, comments, assignees. Change history.

#### 👥 Staff
Personnel records, attendance journal, work calendar, employee profiles.

#### 📄 Document Management
File versioning, recipient notifications, change history. Storage in Backblaze B2.

#### 📊 Analytics
Summary dashboards across all modules. Trends, dynamics, period filters.

#### 💬 Chat
Built-in messenger — personal and group chats. Push notifications.

---

### ⚙️ Tech Stack

```
Backend:    Django 5.2, Django REST Framework, PostgreSQL
Frontend:   Vanilla JS, HTML/CSS (no frameworks)
Infra:      Railway, Backblaze B2, Redis
Other:      Chart.js, openpyxl, APScheduler, WebSockets
```

---

### 🏭 Real-World Case

The platform was developed and deployed at an **automotive manufacturing facility** in Kazakhstan. Used by quality control operators to register paint coating defects and track coating thickness measurements.

**Replaced:**
- Google Sheets for defect tracking
- Paper measurement journals
- Excel quality reports

---

### 💡 Key Features

- **Responsive design** — works on a tablet right on the shop floor
- **Dark mode** — for production environments
- **Global search** — across all modules including VIN
- **QR scanner** — barcode search directly from the browser
- **Notification system** — real-time, mobile push notifications
- **Role-based access** — superadmin, admin, user
- **Module permissions** — each user sees only the modules they need

---

### 👨‍💻 Developer

**Islamov Ildar** — Full-stack developer specializing in production systems and internal automation.

- 🔗 [LinkedIn](https://www.linkedin.com/in/islamov-ildar/)
- ✈️ [Telegram](https://t.me/created_by_islamov_ildar)
- 🌐 [Demo](https://qpm-app.up.railway.app)

> *QPM was built to prove that internal tools don't have to be ugly and inconvenient. This is an MVP of a platform that scales to any production process.*

---

<div align="center">

**QPM — Built by Islamov Ildar · 2026**

</div>
