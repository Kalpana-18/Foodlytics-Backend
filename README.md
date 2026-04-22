# Foodlytics - Nutrient Analysis Made Easy

A Flutter-based mobile application that simplifies nutritional label analysis 
using OCR, AI, and Machine Learning.

> Final Year B.Tech Project — Computer Science & Engineering  
> Institute of Engineering & Technology, Dr. APJ Abdul Kalam Technical University, Lucknow  
> June 2025

## Team Members
- Ayush Dixit (Roll No. 2100520100021)
- Kalpana Bharti (Roll No. 2100520100034)
- Lalit Kumar Singh (Roll No. 2100520100044)

## Guided By
- Prof. M.H. Khan
- Mr. Raghvendra Singh

---

## About the Project

Foodlytics helps users make informed food choices by scanning nutrition labels 
and barcodes using their phone's camera. It uses OCR to extract nutritional 
data, AI/ML to analyze it, and provides personalized health recommendations 
through a built-in chatbot powered by Google Gemini 2.0 Flash.

---

## Features

- Barcode & nutrition label scanning using OCR (Tesseract + OpenCV)
- AI-powered health score for each scanned product
- Healthier food alternatives suggested by Google Gemini AI
- Personalized dietary recommendations based on user goals and allergies
- Interactive nutrition chatbot (NutritionalAssistant)
- Analytics dashboard with macro breakdown and scan history
- Gamification — health points, badges, and leaderboard
- User authentication with JWT and bcrypt password hashing
- Scan history and dietary trend tracking

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Flutter (Android & iOS) |
| Backend | Node.js + Express.js |
| Database | MongoDB |
| OCR | Tesseract OCR + OpenCV |
| AI/ML | Google Gemini 2.0 Flash (google-genai) |
| Auth | JWT + bcrypt |

---

## Getting Started

### Prerequisites
- Node.js installed
- MongoDB connection
- Flutter SDK installed
- Google Gemini API key

### Backend Setup
```bash
cd Foodlytics-Backend
npm install
node server.js
```

### Frontend Setup
```bash
cd Foodlytics
flutter pub get
flutter run
```

---

## Turnitin Similarity
Overall Similarity: 8% — No integrity flags found.
