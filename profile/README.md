<p align="center">
  <img src="./banner.svg" width="100%" alt="Bidar Banner">
</p>

# Bidar

## Sleep peacefully. Bidar is watching.

**Website Monitoring • SSL Checks • Instant Telegram Alerts**

---

Bidar is a lightweight website monitoring platform that helps developers and businesses stay informed about their website availability and SSL certificate status.

Receive instant Telegram notifications when your website goes down or when an SSL certificate is close to expiration.

### Features

- Uptime Monitoring
- SSL Certificate Monitoring
- Instant Telegram Alerts
- Fast & Lightweight
- No Dashboard Required
- Telegram-First Experience

### How It Works

1. Submit your website URL.
2. Generate a secure connection token.
3. Open `@BidarMonitorBot`.
4. Connect your monitor using:

```text
/connect YOUR_TOKEN
```

5. Receive instant alerts directly in Telegram.

### Architecture

```text
Telegram User
      │
      ▼
BidarMonitorBot
      │
      ▼
Django API
      │
      ▼
PostgreSQL
      │
      ▼
Monitoring Workers
```

### Tech Stack

- Django
- Django REST Framework
- PostgreSQL
- Redis
- Celery
- Telegram Bot API
- Docker

---

Built with ❤️ by CyberHuginn.
