# <p align="center">TaskPixie</p>

<p align="center">
  <img src="https://res.cloudinary.com/dntohhpee/image/upload/v1782942926/TaskPixie-Logo_tywydx.png" alt="TaskPixie Banner" width="100%">
</p>

<p align="center">
  <strong>Your AI-Powered Productivity Companion</strong>
</p>

---

## 🚀 About

**TaskPixie** is an AI-powered task management application built to make planning and productivity effortless. Instead of simply storing tasks, it intelligently understands, organizes, and optimizes your workflow.

With AI-assisted planning, smart prioritization, automatic task breakdown, personalized daily schedules, recurring task automation, and productivity insights, TaskPixie acts as your personal productivity assistant.

---

## ✨ Features

* 🤖 Smart task creation using natural language
* 📌 AI-powered task prioritization
* 🧩 Automatic task breakdown into subtasks
* 📅 Personalized daily planner
* ⏰ Intelligent reminders
* 🔄 Recurring task management
* 📊 Productivity analytics and reports
* 📝 AI-generated daily, weekly, and monthly summaries
* 🔐 Secure JWT Authentication
* 📱 Responsive modern interface

---

## 🛠 Tech Stack

### Frontend

* React
* Vite
* Tailwind CSS

### Backend

* Django
* Django REST Framework

### Database

* PostgreSQL

### Background Jobs

* Celery
* Redis

### AI

* LLM API Integration

---

## 🎯 Vision

TaskPixie is designed to be more than a to-do list. It aims to become an intelligent productivity assistant that helps users focus on what matters most, build better work habits, and accomplish goals more efficiently.

---

<p align="center">
  Built with ❤️ using Django, React, PostgreSQL, Celery, Redis, and AI.
</p>

## Project Structure

```text
TaskPixie/
├── backend/
│   ├── config/
│   │   ├── settings/
│   │   │   ├── __init__.py
│   │   │   ├── base.py
│   │   │   ├── development.py
│   │   │   ├── production.py
│   │   │   └── testing.py
│   │   ├── __init__.py
│   │   ├── urls.py
│   │   ├── asgi.py
│   │   └── wsgi.py
│   ├── common/
│   │   ├── constants.py
│   │   ├── enums.py
│   │   ├── exceptions.py
│   │   ├── permissions.py
│   │   ├── responses.py
│   │   ├── pagination.py
│   │   ├── validators.py
│   │   ├── middleware.py
│   │   ├── utils.py
│   │   └── decorators.py
│   ├── infrastructure/
│   │   ├── cache/
│   │   ├── database/
│   │   ├── email/
│   │   ├── storage/
│   │   ├── logging/
│   │   └── ai/
│   ├── shared/
│   │   ├── mixins.py
│   │   ├── managers.py
│   │   ├── services.py
│   │   └── choices.py
│   ├── features/
│   │   ├── accounts/
│   │   │   ├── migrations/
│   │   │   ├── models/
│   │   │   │   ├── __init__.py
│   │   │   │   ├── user.py
│   │   │   │   ├── profile.py
│   │   │   │   ├── email_verification.py
│   │   │   │   ├── password_reset.py
│   │   │   │   └── login_history.py
│   │   │   ├── serializers/
│   │   │   │   ├── __init__.py
│   │   │   │   ├── user.py
│   │   │   │   ├── auth.py
│   │   │   │   └── profile.py
│   │   │   ├── services/
│   │   │   │   ├── __init__.py
│   │   │   │   ├── auth.py
│   │   │   │   ├── user.py
│   │   │   │   ├── profile.py
│   │   │   │   └── email.py
│   │   │   ├── selectors/
│   │   │   │   ├── __init__.py
│   │   │   │   ├── user.py
│   │   │   │   └── profile.py
│   │   │   ├── views/
│   │   │   │   ├── __init__.py
│   │   │   │   ├── auth.py
│   │   │   │   ├── user.py
│   │   │   │   └── profile.py
│   │   │   ├── tests/
│   │   │   │   ├── __init__.py
│   │   │   │   ├── test_models.py
│   │   │   │   ├── test_services.py
│   │   │   │   └── test_views.py
│   │   │   ├── admin.py
│   │   │   ├── apps.py
│   │   │   ├── urls.py
│   │   │   ├── permissions.py
│   │   │   ├── managers.py
│   │   │   ├── signals.py
│   │   │   └── tasks.py
│   │   ├── workspaces/
│   │   ├── tasks/
│   │   ├── labels/
│   │   ├── reminders/
│   │   ├── notifications/
│   │   ├── dashboard/
│   │   └── ai/
│   ├── templates/
│   ├── static/
│   ├── media/
│   └── logs/
├── tests/
├── requirements/
│   ├── base.txt
│   ├── development.txt
│   └── production.txt
├── .env
├── .env.example
├── .gitignore
├── manage.py
├── README.md
└── docker-compose.yml
