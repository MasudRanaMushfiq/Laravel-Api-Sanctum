# Laravel Authentication & Authorization API

**Secure, Scalable Backend for User Management**

**Framework:** Laravel 12  
**Language:** PHP 8.2  
**Authentication:** Laravel Sanctum  
**API Docs:** Swagger (L5-Swagger), Scribe  

---

## Project Overview

This project is a RESTful backend API built with Laravel, providing secure user authentication and authorization mechanisms. It is designed to serve as a scalable foundation for mobile and web applications.

The system supports user registration, login, protected routes, and role-based access control, ensuring secure communication between client and server.

---

## Key Features

- User registration and login system  
- Token-based authentication using Laravel Sanctum  
- Protected API routes with middleware  
- Role-based authorization for secure access control  
- API documentation using Swagger and Scribe  
- Clean and scalable project structure  

---

## Authentication & Authorization

- Implemented secure authentication using Laravel Sanctum  
- Users receive API tokens upon login  
- Protected routes require valid authentication tokens  
- Middleware ensures only authorized users can access specific endpoints  

---

## API Documentation

- Integrated Swagger (L5-Swagger) for interactive API documentation  
- Added Scribe for clean and developer-friendly API docs  

---

## Tech Stack

- Laravel 12  
- PHP 8.2  
- Laravel Sanctum  
- L5-Swagger  
- Scribe  

---

## Project Structure

- `app/` – Core application logic (Controllers, Models, Middleware)  
- `routes/` – API route definitions  
- `database/` – Migrations, seeders, factories  
- `config/` – Application configuration  
- `tests/` – Unit and feature tests  

---

## API Flow

Register → Login → Receive Token → Access Protected Routes → Perform Authorized Actions  

---

## Installation

### Prerequisites

- PHP 8.2+  
- Composer  
- Node.js & npm  

### Setup

```bash
git clone <your-repo-link>
cd <project-folder>
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm install
npm run build
php artisan serve
```

---

## Development

Run all services (server, queue, logs, vite):

```bash
composer run dev
```

---

## Testing

```bash
php artisan test
```

---

## Future Improvements

- Role & permission management (advanced RBAC)  
- Email verification and password reset  
- OAuth / social login integration  
- Rate limiting and API security enhancements  

---

## License

This project is open-source under the MIT License.

---

## Developer

**Masud Rana Mushfiq**
