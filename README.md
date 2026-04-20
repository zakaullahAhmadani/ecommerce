# NovaCart MERN Store

Basic e-commerce project using React, Express, and MongoDB with:

- Product listing page
- Product details page
- Shopping cart
- User registration and login
- Order processing
- Search and category filters
- Customer profile and order history

## Project structure

- `client/` React frontend built with Vite
- `server/` Express API with MongoDB models for products, users, and orders

## Run locally

### 1. Install dependencies

```bash
cd server
npm install
cd ../client
npm install
```

### 2. Configure environment

Copy `server/.env.example` to `server/.env` and update values if needed:

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/novacart
JWT_SECRET=change-this-secret
CLIENT_URL=http://localhost:5173
```

### 3. Seed products

```bash
cd server
npm run seed
```

### 4. Start both apps

In one terminal:

```bash
cd server
npm run dev
```

In another terminal:

```bash
cd client
npm run dev
```

Frontend: `http://localhost:5173`
Backend: `http://localhost:5000`
