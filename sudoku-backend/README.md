
# Sudoku Backend

This is the backend for the Sudoku game built with NestJS and PostgreSQL.

## Setup

1. Navigate to the backend directory:
   ```sh
   cd backend
   ```

2. Install the dependencies:
   ```sh
   npm install
   ```

3. Create a `.env` file in the root of the project and configure your database connection:
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

## Project Structure

- `src/users/`: Contains user-related logic and entities.
- `src/auth/`: Contains authentication logic and strategies.
- `src/sudoku/`: Contains Sudoku game logic and entities.

## Notes

- The project uses NestJS with TypeORM for PostgreSQL.
