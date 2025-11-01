# Node.js Backend App

A basic Node.js backend application with Express framework.

## Features

- Express.js server
- CORS enabled
- Helmet security middleware
- JSON body parsing
- Basic routing
- Error handling
- Health check endpoint

## Setup

1. Make sure you have Node.js installed
2. Clone this repository
3. Run `npm install` to install dependencies
4. Run `npm run dev` to start the development server with nodemon
5. Or run `npm start` to start the production server

## Scripts

- `npm start` - Start the server
- `npm run dev` - Start the server with nodemon for development
- `npm test` - Run tests (placeholder)

## Endpoints

- `GET /` - Welcome message
- `GET /health` - Health check
- Any other route will return a 404 error

## Port

The server runs on port 8000 by default (can be changed via PORT environment variable).

## Dependencies

- express: Web framework
- cors: Cross-origin resource sharing
- helmet: Security headers

## Dev Dependencies

- nodemon: Development server with auto-restart
