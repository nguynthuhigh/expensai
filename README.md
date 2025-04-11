<p align="center">
  <img src="./image.png" width="150" alt="Expensai Logo" />
</p>

<h1 align="center">Expensai</h1>

<p align="center">
  💸 Smart Expense Tracking powered by AI – automatic categorization, chatbot support, and financial clarity at your fingertips.
</p>

---

## 🚀 Features

- 🤖 **AI-powered auto-categorization** of your transactions (food, travel, shopping, etc.)
- 💬 **Chatbot assistant** for insights, reminders, and financial tips
- 🔐 **User authentication** with JWT
- 📁 Manage categories, users, transactions, and conversations
- ⚡️ Lightweight, easy-to-use RESTful API

---

## 🧠 Tech Stack

- **Express.js** – Powerful & scalable Node.js framework
- **TypeScript** – Strongly typed, clean codebase
- **MongoDB** – Flexible data storage
- **Gemini** _(planned)_ – NLP and AI-enhanced features
- **Docker** – Consistent deployment environment

---

## 📁 Project Structure (Coming Soon)

```

```

---

## 🐳 Run with Docker

> Make sure you have [Docker](https://www.docker.com/) installed.

### 1. Build & Run

```bash
docker build -t expensai-backend .
docker run -p 3000:3000 expensai-backend
```

### 2. (Optional) Using `docker-compose`

```yaml
# docker-compose.yml
version: "3.8"

services:
  backend:
    build: .
    ports:
      - "3000:3000"
    environment:
      - NODE_ENV=production
```

```bash
docker-compose up --build
```

---

## 🛠️ TODO (Coming Soon)

- [ ] Chatbot integration using Gemini
- [ ] Frontend (React)
- [ ] Analytics dashboard
- [ ] Dark mode support 😎

---

## 📬 Feedback / Contribution

Got an idea? Found a bug? PRs and issues are welcome!  
Let’s build the smartest budgeting app together. 💥

---

<p align="center">
  Made with ❤️ by <strong>Expensai</strong>  
  <br />
  If you like this project, <a href="https://github.com/nguynthuhigh/expensai" target="_blank">give it a ⭐️ on GitHub</a>!
</p>
