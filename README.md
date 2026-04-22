# Foodlytics Backend

Backend server for Foodlytics - Nutrient Analysis Made Easy, built with Node.js.

## Project Structure
Foodlytics-Backend/
├── config/
│   └── database.js        
├── controllers/
│   ├── analyticsController.js
│   ├── authController.js
│   ├── chatbotController.js
│   ├── historyController.js
│   └── productController.js
├── middleware/
│   ├── auth.js
│   └── consoleLogger.js
├── models/
│   ├── ChatConversation.js
│   ├── ScanHistory.js
│   ├── User.js
│   └── UserAnalytics.js
├── routes/
├── services/
├── uploads/
└── server.js

## Features
- User Authentication & Authorization
- Food Product Scanning & Analysis
- Nutrient Analytics
- Chat History Management
- AI Chatbot Integration

## Tech Stack
- Runtime: Node.js
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)

## Getting Started

### Prerequisites
- Node.js installed
- MongoDB connection

### Installation
npm install

### Run Server
node server.js
