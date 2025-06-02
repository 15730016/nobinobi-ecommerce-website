# Nobinobi E-commerce Website

A modern e-commerce website built with React and Laravel.

## Tech Stack

### Frontend
- React
- React Router
- Redux Toolkit
- Axios
- Tailwind CSS

### Backend  
- Laravel
- MySQL
- Laravel Sanctum for authentication

## Project Structure

```
/
├── frontend/           # React frontend
└── backend/           # Laravel backend API
```

## Getting Started

### Frontend Setup
```bash
cd frontend
npm install
npm start
```

### Backend Setup  
```bash 
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
