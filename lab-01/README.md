# Lab 1: Node.js and Express Server

## Student Details

- **Name:** Saivarun Yenishetty
- **Registration Number:** 252U1R9174
- **Section:** CSE-GAI-2C

## Objective

To create a web server using Node.js and Express.js, implement GET routes, and handle unknown routes with appropriate HTTP status codes.

## Technologies Used

- Node.js
- Express.js
- JavaScript
- Visual Studio Code

## Installation

Install Node.js and run the following command in the project folder:

```bash
npm install
```

## How to Run

### Basic Node.js HTTP Server

```bash
node basic-server.js
```

Open http://localhost:3000.

Expected output: `Hello`

Stop the server with Ctrl + C before starting the Express server.

### Express Server

```bash
node server.js
```

Open http://localhost:3000 in your browser.

## Endpoints

| Method | Path | Description | Status |
|---|---|---|---|
| GET | / | Displays a welcome message | 200 OK |
| GET | /about | Returns name and section as JSON | 200 OK |
| GET | /time | Returns the current date and time | 200 OK |
| GET | /unknown | Returns a page-not-found message | 404 Not Found |

## Screenshots

### Home Page

![Home Page](screenshots/home.png)

### About Page

![About Page](screenshots/about.png)

### Current Date and Time

![Time Page](screenshots/time.png)

### Unknown Route

![404 Page](screenshots/404.png)

## Notes

This lab demonstrates creating a basic HTTP server using Node.js and a web server using Express.js. It implements multiple GET routes and handles unknown routes with appropriate HTTP status codes.

## Live Link

Not deployed yet.