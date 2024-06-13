
# Sudoku Project

This repository contains both the frontend and backend for the Sudoku game.

## Frontend (Next.js)

The frontend is located in the `frontend` directory and is built with Next.js.

### Setup

1. Navigate to the frontend directory:
   ```sh
   cd frontend
   ```

2. Install the dependencies:
   ```sh
   npm install
   ```

3. Create a `.env.local` file in the root of the frontend directory and add your environment variables:
   ```
   NEXTAUTH_URL=http://localhost:3000
   GITHUB_CLIENT_ID=your_github_client_id
   GITHUB_CLIENT_SECRET=your_github_client_secret
   DATABASE_URL=your_database_url
   ```

4. Run the development server:
   ```sh
   npm run dev
   ```

### Project Structure

- `pages/`: Contains the pages of the application.
- `components/`: Contains the reusable components of the application.

## Backend (NestJS)

The backend is located in the `backend` directory and is built with NestJS and PostgreSQL.

### Setup

1. Navigate to the backend directory:
   ```sh
   cd backend
   ```

2. Install the dependencies:
   ```sh
   npm install
   ```

3. Create a `.env` file in the root of the backend directory and configure your database connection:
   ```
   DB_HOST=localhost
   DB_PORT=5432
   DB_USERNAME=your_username
   DB_PASSWORD=your_password
   DB_NAME=your_database
   JWT_SECRET=your_jwt_secret
   ```

4. Run the development server:
   ```sh
   npm run start:dev
   ```

### Project Structure

- `src/users/`: Contains user-related logic and entities.
- `src/auth/`: Contains authentication logic and strategies.
- `src/sudoku/`: Contains Sudoku game logic and entities.

## Notes

- The frontend uses NextAuth for authentication with GitHub as the provider.
- The backend uses NestJS with TypeORM for PostgreSQL.
