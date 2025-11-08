# Car Rental Management System

A minimal full-stack car rental management system example.

## Features
- Backend: Node.js + Express + SQLite (better-sqlite3)
- Frontend: React (single-file demo)
- Docker & docker-compose configuration for easy deployment
- Endpoints: cars, bookings, users (basic)

## Quick start (local)
Requires Node.js (v16+) and npm.

### Backend
```bash
cd backend
npm install
npm run init-db
npm start
```

### Frontend
```bash
cd frontend
npm install
npm start
```

The frontend assumes the backend runs at http://localhost:4000

## Docker
From repo root:
```bash
docker-compose up --build
```

## API Endpoints (examples)
- `GET /api/cars` - list cars
- `POST /api/cars` - add car
- `GET /api/bookings` - list bookings
- `POST /api/bookings` - create booking

## Notes
This is a minimal template to get you started. Extend with authentication, validation, payments, admin UI, etc.
