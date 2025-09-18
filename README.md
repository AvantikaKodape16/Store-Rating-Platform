# Store Rating Platform

## Setup Instructions

### Backend
1. Install dependencies:
   ```bash
   cd backend
   npm install
   ```
2. Setup PostgreSQL and create a database (`store_rating_db`).
3. Copy `.env.example` to `.env` and fill in your DB credentials.
4. Run migrations and seed:
   ```bash
   npm run migrate
   npm run seed
   ```
5. Start server:
   ```bash
   npm start
   ```

### Frontend
1. Install dependencies:
   ```bash
   cd frontend
   npm install
   ```
2. Start React app:
   ```bash
   npm start
   ```
3. App runs at [http://localhost:3000](http://localhost:3000)

### Default Admin
- Email: `admin@platform.com`
- Password: `Admin@123`

---

## Features
- Signup/Login/Logout for users
- Admin dashboard with stats
- Store listing/search
- Rating system (1-5)
- Password update

---

## Notes
- Backend: Express.js, PostgreSQL
- Frontend: React.js
- See code comments for extension points (store owner, ratings per user, filters, etc.)
