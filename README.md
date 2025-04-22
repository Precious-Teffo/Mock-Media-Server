 Mock Media Server

## Overview

This is a simple mock media server built using Node.js and Express.js. It exposes a set of RESTful API endpoints for managing a basic collection of movies, series, and songs. This project is ideal for learning the fundamentals of backend development, RESTful routing, and handling data using JSON.

The server handles basic CRUD operations for each media type, supports dynamic routing, and includes basic error handling and route validation.



## Features

- Built with Express.js for fast and lightweight routing
- In-memory data structure (no database required)
- RESTful API with full CRUD (Create, Read, Update, Delete)
- Auto-incrementing IDs for new media entries
- Handles 404 errors for undefined routes
- Clear, consistent JSON responses

---

## API Structure

The application defines three main resource groups:

- `/movies`
- `/series`
- `/songs`

Each resource supports the following HTTP methods:

### GET

- `GET /movies` – Returns all movie entries
- `GET /series` – Returns all series entries
- `GET /songs` – Returns all song entries

### POST

- `POST /movies` – Adds a new movie entry
- `POST /series` – Adds a new series entry
- `POST /songs` – Adds a new song entry

Request body must be in JSON format and include relevant fields (e.g., `title`, `artist`, `year`, etc.).

### PUT

- `PUT /movies/:id` – Updates a movie by ID
- `PUT /series/:id` – Updates a series by ID
- `PUT /songs/:id` – Updates a song by ID

### DELETE

- `DELETE /movies/:id` – Deletes a movie by ID
- `DELETE /series/:id` – Deletes a series by ID
- `DELETE /songs/:id` – Deletes a song by ID

### Invalid Routes

Any route other than those listed above will return a `404 Not Found` response with a simple message.

---

## Installation & Setup

To run the server locally:

1. Clone the repository

bash
git clone # Node.js Mock Media Server

## Overview

This is a simple mock media server built using Node.js and Express.js. It exposes a set of RESTful API endpoints for managing a basic collection of movies, series, and songs. This project is ideal for learning the fundamentals of backend development, RESTful routing, and handling data using JSON.

The server handles basic CRUD operations for each media type, supports dynamic routing, and includes basic error handling and route validation.

---

## Features

- Built with Express.js for fast and lightweight routing
- In-memory data structure (no database required)
- RESTful API with full CRUD (Create, Read, Update, Delete)
- Auto-incrementing IDs for new media entries
- Handles 404 errors for undefined routes
- Clear, consistent JSON responses

---

## API Structure

The application defines three main resource groups:

- `/movies`
- `/series`
- `/songs`

Each resource supports the following HTTP methods:

### GET

- `GET /movies` – Returns all movie entries
- `GET /series` – Returns all series entries
- `GET /songs` – Returns all song entries

### POST

- `POST /movies` – Adds a new movie entry
- `POST /series` – Adds a new series entry
- `POST /songs` – Adds a new song entry

Request body must be in JSON format and include relevant fields (e.g., `title`, `artist`, `year`, etc.).

### PUT

- `PUT /movies/:id` – Updates a movie by ID
- `PUT /series/:id` – Updates a series by ID
- `PUT /songs/:id` – Updates a song by ID

### DELETE

- `DELETE /movies/:id` – Deletes a movie by ID
- `DELETE /series/:id` – Deletes a series by ID
- `DELETE /songs/:id` – Deletes a song by ID

### Invalid Routes

Any route other than those listed above will return a `404 Not Found` response with a simple message.

---

## Installation & Setup

To run the server locally:

1. Clone the repository

bash
git clone hhttps://github.com/Precious-Teffo/Mock-Media-Server.git
cd media-server

2.npm install
3.node server.js
