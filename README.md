# AI-Powered Personal Finance Management Platform

A production-ready full-stack personal finance management system with AI-powered insights, real-time analytics, collaborative family finance management, and intelligent financial monitoring.

Built using modern web technologies, real-time communication systems, and machine learning integrations to provide users with a secure and scalable financial management experience.

---

# Features

## Personal Finance Management
- Add, edit, and manage income & expense transactions
- Budget tracking with category-wise spending analysis
- Financial goal creation and progress monitoring
- Interactive analytics dashboard with charts and reports
- CSV/JSON transaction export support
- Real-time financial summaries and monitoring

## AI-Powered Insights
- Google Gemini AI integration for intelligent financial analysis
- Spending pattern detection and recommendations
- Smart budgeting and saving suggestions
- Trend analysis and anomaly detection
- AI-generated financial insights based on transaction history

## Family Collaboration System
- Multi-user family finance management
- Shared family budgets and savings goals
- Role-based access control (Admin / Member)
- Real-time synchronization across family members
- Contribution tracking for collaborative goals
- Optional transaction sharing with privacy controls

## Real-Time Notifications
- SMS alerts using Twilio API
- Budget threshold notifications
- Goal milestone notifications
- Real-time updates using WebSockets
- Configurable notification preferences

---

# Tech Stack

## Frontend
- React.js
- TypeScript
- Tailwind CSS
- Recharts
- Socket.IO Client
- Vite

## Backend
- Node.js
- Express.js
- TypeScript
- Prisma ORM
- MongoDB
- JWT Authentication
- Socket.IO

## Integrations
- Google Gemini AI
- Twilio SMS API

---

# System Architecture

- REST API-based backend architecture
- Modular service-oriented backend design
- Real-time communication using WebSockets
- Secure authentication & authorization system
- Scalable MongoDB schema design using Prisma ORM
- AI service integration for intelligent recommendations

---

# Core Modules

## Authentication & Security
- JWT-based secure authentication
- Password hashing using bcrypt
- Protected API routes
- Input validation and sanitization
- CORS and rate limiting implementation

## Transaction Management
- Income and expense tracking
- Category-wise organization
- Filtering and search functionality
- Real-time balance updates
- Data export support

## Budget Management
- Monthly and category-based budgets
- Budget utilization tracking
- Automated budget alerts
- Spending analysis dashboard

## Goal Tracking
- Personal and family financial goals
- Contribution history tracking
- Goal milestone notifications
- Progress visualization

## Family Room
- Shared financial collaboration
- Family-wide analytics dashboard
- Shared budgets and goals
- Real-time member activity synchronization

---

# AI Features

The application integrates Google Gemini AI to provide intelligent financial assistance.

### AI Capabilities
- Spending behavior analysis
- Personalized savings recommendations
- Financial trend identification
- Smart budgeting suggestions
- AI-generated financial summaries

---

# Real-Time Features

- Live dashboard synchronization
- Instant family data updates
- Real-time goal progress tracking
- WebSocket-based event communication

---

# Database Design

The backend uses MongoDB with Prisma ORM for:
- Scalable document-based storage
- Efficient schema management
- Relationship handling
- Query optimization
- Secure data operations

---

# Installation & Setup

## Clone Repository

```bash
git clone <repository-url>
cd financial-management-project
Install Dependencies
Frontend
npm install
Backend
cd backend
npm install
Environment Variables

Create a .env file inside the backend directory:

DATABASE_URL=

JWT_SECRET=

GEMINI_API_KEY=

TWILIO_ACCOUNT_SID=
TWILIO_AUTH_TOKEN=
TWILIO_PHONE_NUMBER=
Run Application
Start Backend
cd backend
npm run dev
Start Frontend
npm run dev
Application URLs

Frontend:

http://localhost:5173

Backend:

http://localhost:3000
Project Structure
financial-management-project/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── utils/
│   │   └── config/
│   │
│   ├── prisma/
│   └── package.json
│
├── src/
│   ├── components/
│   ├── contexts/
│   ├── services/
│   └── App.tsx
│
├── README.md
└── package.json
Security Features
JWT Authentication
bcrypt password hashing
Protected API endpoints
Input validation
Rate limiting
Secure environment variable management
Privacy-focused transaction sharing controls
Key Highlights
Full-stack enterprise-level application
AI-integrated financial management system
Real-time collaborative architecture
Secure authentication & authorization
Modular and scalable backend design
Production-ready project structure
Academic Context

Developed as part of the EDAI (Emerging Domains in AI) course at VIT Pune.

Contributors
Sakshi Aswale
Team Members
Future Enhancements
Expense prediction using ML models
Multi-currency support
Investment portfolio tracking
Mobile application support
Advanced analytics dashboard
AI chatbot for financial assistance
