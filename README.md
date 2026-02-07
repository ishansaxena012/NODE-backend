A minimal Node.js backend starter built with clean architecture and separation of concerns.

### Structure
src/
  config/        → app & library setup  
  routes/        → route definitions  
  middlewares/   → request interceptors  
  controllers/   → handle HTTP layer  
  services/      → business logic  
  repositories/  → DB access  
  utils/         → helpers & common code


### Flow:
Route → Middleware → Controller → Service → Repository

### Setup
Install dependencies
npm install

Create .env
PORT=3000

Sequelize (if using DB)
npx sequelize init


Update config/config.json with your database credentials.

### Run server
npm run dev
