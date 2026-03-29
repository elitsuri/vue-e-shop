# vue-e-shop

> Vue E-Shop: E-commerce app with Pinia state, cart, wishlist, and payments

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Nuxt.js, TypeScript, PostgreSQL, Prisma, Pinia

## 🏗️ Architecture
Three-tier architecture: Nuxt.js, TypeScript backend, React/TypeScript frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/vue-e-shop
cd vue-e-shop

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
