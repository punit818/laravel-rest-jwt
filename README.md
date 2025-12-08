
---

## 📘 **2. README — Laravel REST API with JWT (laravel-rest-jwt)**

```md
# Laravel REST API with JWT Authentication

A production-ready REST API with JWT-based authentication, CRUD endpoints, validation, and role-based access.

---

## 🚀 Features
- User Registration & Login
- JWT Authentication
- CRUD API for Posts
- Pagination
- Validation
- Protected Routes
- Clean Controllers + Service Layer

---

## 📂 API Endpoints

### Auth
- `POST /api/register`
- `POST /api/login`
- `GET /api/me`
- `POST /api/logout`

### Posts
- `GET /api/posts`
- `POST /api/posts`
- `GET /api/posts/{id}`
- `PUT /api/posts/{id}`
- `DELETE /api/posts/{id}`

---

## 🔧 Installation

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
