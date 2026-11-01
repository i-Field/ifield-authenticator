# ifield-authenticator
Secure, lightweight, and offline-first client-side 2FA TOTP authenticator with zero data leaks. Built for privacy.
# 🔐 iField Auth — Secure 2FA Authenticator

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![JavaScript](https://img.shields.io/badge/javascript-vanilla-yellow.svg)
![Privacy](https://img.shields.io/badge/privacy-100%25%20client--side-green.svg)

**iField Auth** — это быстрый, безопасный и полностью автономный веб-аутентификатор (двухфакторная аутентификация TOTP), который работает прямо в вашем браузере. Разработан как приватная и легкая альтернатива громоздким корпоративным аналогам.

---

## ✨ Основные особенности

* 🔒 **Абсолютная приватность (Zero-Knowledge):** Все ваши секретные ключи хранятся исключительно в локальном хранилище браузера (`localStorage`). Никакие данные никогда не отправляются на сторонние сервера.
* ⚡ **Стандарты RFC 6238:** Полная совместимость со стандартными 2FA-ключами (Base32) для Google, GitHub, Telegram, Discord и сотен других сервисов.
* ⏱ **Динамическое обновление:** Синхронизированный с системным временем таймер обратного отсчета (30 секунд) и мгновенное копирование кодов по клику.
* 💻 **Offline-First / PWA:** Работает без подключения к интернету после первой загрузки.
* 🎨 **Современный UI/UX:** Приятный темный дизайн с акцентами в стиле Glassmorphism.

---

## 🚀 Быстрый запуск

Проект работает «из коробки» без сборщиков и Node.js:

1. Склонируйте репозиторий:
   ```bash
   git clone [https://github.com/i-field/ifield-authenticator.git](https://github.com/i-field/ifield-authenticator.git)
