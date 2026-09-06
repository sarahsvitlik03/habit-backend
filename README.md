
# Chore Tracker

A lightweight **Node.js + Express** backend powering the Habit Tracker application. This service provides RESTful API endpoints for managing chores, storing habit data, and connecting to a MongoDB database.

This backend is designed to be simple, fast, and easy to deploy — ideal for small productivity apps and personal habit‑tracking tools.

---

## Features

- **Express.js REST API** for chore and habit management  
- **MongoDB database integration** via a custom `db.js` connection file  
- **CRUD operations** for chores  
- **Lightweight server architecture** (no unnecessary dependencies)  

---

## Tech Stack

- Node.js  
- Express.js  
- MongoDB  
- JavaScript  

---

## API Endpoints

### `GET /api/chores`
Returns all chores stored in the database.

### `POST /api/chores`
Creates a new chore.

### `PUT /api/chores/:id`
Updates an existing chore.

---

## Getting Started

### Install dependencies
```bash
npm install
```

### Start development server
```bash
npm start
```

### Environment Variables

Create a `.env` file in the root directory:

```
MONGO_URI=your_mongodb_connection_string
PORT=3000
```

### Project Structure

```
habit-backend/
├── db.js            # MongoDB connection logic
├── server.js        # Express server + routes
├── package.json
├── package-lock.json
└── .gitignore
```

---

## Related Projects

- **Habit Frontend** — Vue.js UI for interacting with this backend  

---
