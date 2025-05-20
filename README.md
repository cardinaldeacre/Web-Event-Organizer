# Web Event Organizer

**Web Event Organizer** is a web-based application built as part of the MBKM internship program. The platform provides tools for creating and managing events effectively, complete with a responsive user interface and real-time event data monitoring.

## 🚀 Key Features

- Create and manage events
- Participant registration and monitoring
- Event scheduling with calendar support
- Dashboard with event statistics
- Responsive layout for various devices

## 🧩 Tech Stack

### Frontend
- **React.js** – for building a fast and modular Single Page Application (SPA)
- **Vite** – as a modern and lightweight build tool for faster development
- **Tailwind CSS** – for utility-first, responsive, and consistent styling

### Backend
- **Laravel** – a modern PHP framework that supports RESTful API development, authentication, and structured data management

### Database
- **MySQL** – a reliable relational database system used to store user data, event information, and participant registrations. It integrates seamlessly with Laravel.

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/cardinaldeacre/web-event-organizer.git
```

### 2. Front-End
```bash
cd frontend
npm install
npm run dev
```

### 3. Back-End
```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

Make sure to configure .env for database and API connections
