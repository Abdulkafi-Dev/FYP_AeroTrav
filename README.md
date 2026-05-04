# AeroTrav - Travel Booking Platform

A modern full-stack travel booking application built with React, Node.js, and MySQL.

## 🏗️ Project Structure

```
FYP_AeroTrav_Final/
├── apps/
│   ├── client/          # React + TypeScript Frontend
│   └── server/          # Node.js + Express Backend
├── database/            # Database schemas and migrations
├── docs/               # Documentation
├── legacy/             # Archived legacy code
└── scripts/           # Build and deployment scripts
```

## 🚀 Quick Start

### Prerequisites
- Node.js (v18+)
- MySQL (v8.0+)
- XAMPP (for local development)

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd FYP_AeroTrav_Final
```

2. Install dependencies
```bash
npm install
```

3. Setup environment variables
- Copy `apps/client/.env.local.example` to `apps/client/.env.local`
- Copy `apps/server/.env.example` to `apps/server/.env`

4. Setup database
```bash
# Import the database schema
mysql -u root -p < database/schema.sql
```

5. Start development servers
```bash
npm run dev
```

## 🛠️ Available Scripts

- `npm run dev` - Start both client and server in development mode
- `npm run dev:client` - Start only the frontend
- `npm run dev:server` - Start only the backend
- `npm run build` - Build client for production
- `npm run clean` - Clean all dependencies and build files

## 📱 Features

- **Flight Booking** - Search and book flights
- **Hotel Reservations** - Find and book accommodations
- **Car Rentals** - Rent vehicles for travel
- **Travel Packages** - Complete travel solutions
- **User Authentication** - Secure login and registration
- **Admin Dashboard** - Manage bookings and users
- **AI Recommendations** - Personalized travel suggestions

## 🏛️ Architecture

- **Frontend**: React + TypeScript + Vite + Tailwind CSS
- **Backend**: Node.js + Express + MySQL
- **Database**: MySQL with structured schemas
- **Authentication**: JWT-based authentication
- **State Management**: React Context API

## 📊 Development

### Client Development
```bash
cd apps/client
npm run dev
```

### Server Development
```bash
cd apps/server
npm run dev
```


