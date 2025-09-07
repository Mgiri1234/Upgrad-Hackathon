# Upgrad-Hackathon Repository Overview

## Project Purpose
This repository contains the codebase for the Upgrad CodeSmashers Hackathon project. The project appears to be an educational platform with features such as course management, learner analytics, risk tracking, notifications, and machine learning integration for personalized recommendations and insights.

## Tech Stack

### Backend
- **Node.js** (Express.js): Main server-side framework
- **Python**: Used for data generation and possibly ML integration
- **PostgreSQL / MongoDB** (assumed): For data persistence (based on typical stack, not explicitly shown)
- **Postman**: For API testing (inferred from instruction files)

### Frontend
- **Next.js** (React): Modern frontend framework for building the web UI
- **TypeScript**: For type-safe frontend development
- **Tailwind CSS / PostCSS**: For styling (inferred from config files)
- **ESLint**: For code linting and quality

## Key Features
- **User Authentication**: Auth routes and middleware for secure access
- **Course Management**: CRUD operations for courses and modules
- **Learner Analytics**: Dashboards and analytics for tracking learner progress and engagement
- **Risk Tracking**: Daily risk tracking and intervention system for at-risk learners
- **Notifications**: Real-time and scheduled notifications for users
- **Machine Learning Integration**: ML services for recommendations and insights (Gemini, custom ML)
- **Admin Panel**: Admin routes and dashboards for managing the platform

## Directory Structure
- `backend/` - Node.js backend with Express routes, models, services, and scripts
- `frontend/` - Next.js frontend with pages, components, and context providers
- `test_*.py` - Python scripts for integration and system testing
- `data/` - Data generation scripts
- `middleware/` - Express middleware for authentication
- `models/` - Mongoose or Sequelize models for DB entities
- `routes/` - Express route handlers for various features
- `services/` - Business logic and integrations (ML, notifications, risk tracking)
- `scripts/` - Utility scripts for data population and maintenance
- `components/` - React components for UI
- `contexts/` - React context providers (e.g., Auth)
- `lib/` - Utility functions for frontend

## Getting Started
1. **Backend**: Install dependencies (`npm install`), configure environment, and run the server (`node app.js` or `npm start`).
2. **Frontend**: Install dependencies (`npm install` or `pnpm install`), then run the development server (`npm run dev`).
3. **Testing**: Use provided Python scripts for integration and system tests.

## Notable Integrations
- **Gemini ML Service**: For advanced analytics and recommendations
- **Postman**: For API testing and documentation

---

*For more details, see the `README.md` files in the respective folders.*
