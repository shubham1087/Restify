# Restify

A simple Express-based listing application built with MongoDB, EJS templates, and Mongoose.

## Features

- Create, read, update, and delete listings
- EJS view rendering with `ejs-mate` layout support
- MongoDB persistence via Mongoose
- Method override for form-based PUT and DELETE operations
- Static assets served from `public/`

## Requirements

- Node.js
- npm
- MongoDB running locally at `mongodb://127.0.0.1:27017/wanderlust`

## Installation

1. Clone the repository or copy the project files.
2. Install dependencies:

```bash
npm install
```

3. Start MongoDB if it is not already running.

## Run the app

```bash
node app.js
```

Open `http://localhost:8080` in your browser.

## Project structure

- `app.js` - main Express application
- `models/listing.js` - Mongoose schema for listings
- `views/` - EJS templates and layout files
- `public/` - static CSS and client-side JavaScript
- `utils/` - helper utilities for error handling and async wrapping

## Notes

- The app expects a local MongoDB instance using the database name `wanderlust`.
- If you want to change the port or database URL, edit `app.js`.
