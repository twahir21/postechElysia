# 🧠 myPostech Backend

**A blazing-fast backend for the myPostech POS ecosystem**, built with [Bun](https://bun.sh/), [Elysia.js](https://elysiajs.com/), [Drizzle ORM](https://orm.drizzle.team/), and PostgreSQL. Designed for speed, simplicity, and scale, myPostech empowers micro and medium businesses across Tanzania and beyond.

---

## 🚀 Features

- ✅ Blazing-fast server runtime via Bun
- 🔐 JWT-based authentication with access & refresh tokens
- 🧰 Modular and maintainable Elysia.js endpoints
- 🧠 Drizzle ORM for clean and type-safe database queries
- 🗃️ PostgreSQL for transactional integrity and robust storage
- 🌍 Multi-language support (Swahili, French, English, Arabic)
- 📊 Real-time analytics for sales, expenses, and debts
- 📦 QR-based product automation for inventory and POS
- 🌐 PWA-ready frontend (Qwik-based)

---

## 🏗️ Tech Stack

| Layer         | Technology        |
| ------------- | ----------------- |
| Runtime       | Bun               |
| Web Framework | Elysia.js         |
| ORM           | Drizzle ORM       |
| Database      | PostgreSQL        |
| Auth          | JWT (Access & Refresh) |
| Dev Tools     | Bunx, Elysia CLI, Postgres.js |
| Frontend      | Qwik (separate repo) |

---

## 🧪 Setup & Development

### 📦 Prerequisites

- [Bun](https://bun.sh/) installed
- PostgreSQL running locally or on cloud
- Node v20+ (optional fallback)
- `.env` file with environment configs

### ⚙️ Environment Variables

```env
DATABASE_URL=postgresql://user:password@localhost:5432/mypostech
JWT_SECRET=your_super_secret_key
PORT=3000
```

### 🤝 Other Dependencies

- Bunx
- Postgres.js
- clickpesa

---