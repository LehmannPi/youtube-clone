# YouTube Clone Backend

(Under development)

This is a YouTube clone project created as practice of fullstack development. The stacks for front and back-end will be:

Back-end: Express, Mongoose, TypeScript, argon2, busboy, pino, and Zod.

Front-end: Next.js, Mantine, TypeScript, React Query

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)

## Features

- User authentication and authorization
- Video upload and streaming
- Video metadata management
- User profile management
- Secure password hashing with argon2
- Form data parsing with busboy
- Robust logging with pino
- Schema validation with Zod

## Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/yourusername/youtube-clone-backend.git
    ```

2.  Navigate to the project directory:

    ```bash
    cd youtube-clone-backend
    ```

3.  Install dependencies:

    ```bash
    npm install
    ```

4.  Set up environment variables by creating a .env file in the root directory:

    ```bash
    PORT=5000
    MONGODB_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

5.  Run the development server:
    ```bash
    npm run dev
    ```

## Usage

Make sure MongoDB is running.
Use an API client like Postman to interact with the backend.

## API Documentation

At this stage, the envisioned endpoints will be:

### Authentication

- POST /api/auth/register: Register a new user
- POST /api/auth/login: Login a user

### User

- GET /api/user/: Get user profile
- PUT /api/user/: Update user profile

### Videos

- POST /api/videos: Upload a new video
- GET /api/videos/: Get video details
- GET /api/videos: Get a list of all videos
- PUT /api/videos/: Update video details
- DELETE /api/videos/: Delete a video
