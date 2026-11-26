# StockRoom Phase 1: Inventory Core

## Run locally
1. Use Node 22 (`nvm use 22`)
2. `docker compose up -d` (starts PostgreSQL and Redis)
3. Backend: `cd backend && npm install && npm run dev` (http://localhost:4000/health)
4. Frontend: `cd frontend && npm install && npm run dev`