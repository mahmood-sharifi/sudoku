
# Sudoku Frontend

This is the frontend for the Sudoku game built with Next.js.

## Setup

1. Navigate to the frontend directory:
   ```sh
   cd frontend
   ```

2. Install the dependencies:
   ```sh
   npm install
   ```

3. Create a `.env.local` file in the root of the project and add your environment variables:
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

## Project Structure

- `pages/`: Contains the pages of the application.
- `components/`: Contains the reusable components of the application.

## Notes

- The project uses NextAuth for authentication with GitHub as the provider.
