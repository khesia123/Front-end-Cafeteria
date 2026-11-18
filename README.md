# Bookstore Front-End — Academic Project

An academic front-end developed for the Web Programming 3 (PW3) course. The application uses Node.js, Express, EJS, and Axios to render bookstore pages and consume a separate REST API.

## Technology stack

- Node.js
- Express
- EJS
- Axios
- Bootstrap
- JavaScript

## Current functionality

The source code includes pages and routes for:

- Home screen
- Category registration
- Category listing
- Category editing
- Requests to a local backend API using Axios

The front-end server listens on port `3001` and currently calls the backend at `http://localhost:3000`.

## Run locally

1. Install Node.js.
2. Open the application folder:

```bash
cd "Front-end Cafeteria"
```

3. Install dependencies:

```bash
npm install
```

4. Start the backend API separately on port `3000`.
5. Start the front-end server:

```bash
node index.js
```

6. Open `http://localhost:3001` in your browser.

## Notes

This is an academic demonstration project, not a production application. The API URL is currently configured for local development. The code and dependencies may require updates before use in a modern production environment.
