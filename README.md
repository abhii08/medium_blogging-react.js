# Application link:- https://medium-blogging-beryl.vercel.app/

# MEDIUM-BLOGGING

This is a full-stack Medium-like blogging platform built using modern web technologies. It includes features for user authentication, blog creation, editing, and viewing.
# Tech Stack
React in the frontend
Cloudflare workers in the backend
zod as the validation library, type inference for the frontend types
Typescript as the language
Prisma as the ORM, with connection pooling
Postgres as the database
jwt for authentication
## Project Structure

The project is organized into three main directories:

### 1. `backend`
   - **Description**: Contains the server-side code, handling APIs, user authentication, and database operations.
   - **Technologies**: Node.js, Hono, MongoDB.
   - **Files**:
     - `server.js`: Entry point for the backend.
     - `models/`: Mongoose schemas for users and posts.
     - `routes/`: API routes for authentication, posts, and user management.

### 2. `common`
   - **Description**: Houses shared utilities and constants used across both the frontend and backend.
   - **Files**:
     - `config.js`: Configuration files for environment variables.
     - `utils.js`: Common utility functions.

### 3. `frontend`
   - **Description**: Contains the client-side code, responsible for the UI and user interactions.
   - **Technologies**: React.js, Tailwind CSS.
   - **Files**:
     - `pages/`: Next.js pages for different routes (e.g., login, register, blog view).
     - `components/`: Reusable UI components like headers, footers, and forms.
     - `styles/`: Global and component-specific styles using Tailwind CSS.

## Setup

To run the project locally:

#### 1. Clone the repository:
   ```bash
   git clone https://github.com/abhii08/MEDIUM-BLOGGING.git
   cd MEDIUM-BLOGGING
   ```
   
#### 2. Install dependencies for both frontend and backend:
```bash
cd backend
npm install
cd ../frontend
npm install
```

#### 3. Set up environment variables:
Create a .env file in the backend directory with the necessary variables (e.g., MongoDB URI, JWT secret).

#### 4. Run the backend server:
```bash
cd backend
npm run dev
```
#### 5. Run the frontend:
```bash
cd frontend
npm run dev
```

#### 6. Access the application at
```bash
http://localhost:3000
```

