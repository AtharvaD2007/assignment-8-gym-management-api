# Gym & Fitness Club API

This is the solution for Assignment 08: Gym & Fitness Club Management REST API.

## Setup Instructions

1. **Install Dependencies:**
   ```bash
   npm install
   ```

2. **Environment Variables:**
   Copy `.env.example` to `.env` and set your `MONGO_URI`.
   ```bash
   cp .env.example .env
   ```

3. **Start the Server:**
   ```bash
   npm run dev
   ```

## Note on Testing
- Ensure your MongoDB instance is running locally or provide a valid Atlas URI.
- The API relies on cookies for session management (`passport-local`). Ensure your client (Postman/ThunderClient) is configured to save cookies after hitting `/api/auth/login`.
