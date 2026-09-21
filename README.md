<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/bc35603f-093e-4936-b46a-90a4bbef9d73

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GROQ_API_KEY` in [.env](.env) to your Groq API key
3. Run the app:
   `npm run dev`
# ✈️ Travel With Me AI

### Your AI Travel Companion for Gujarat 🌍

Travel With Me AI is an AI-powered travel planning web and mobile application designed to make trip planning easier, smarter, and more personalized.

The application uses **Artificial Intelligence, Google Maps/Places, and real-time travel information** to help users discover destinations, generate itineraries, find nearby places, estimate travel budgets, and manage their journeys from one platform.

---

## 🌟 Features

### 🤖 AI Travel Planner
Generate personalized travel itineraries based on:

- Destination
- Number of days
- Travel style
- Interests
- Budget
- Food preferences
- Activities

The AI creates a structured day-by-day travel plan with activities, meals, estimated costs, and travel tips.

### 🗺️ Google Maps & Places Integration

Discover real places using Google Maps and Places services:

- 📍 Tourist attractions
- 🏨 Hotels
- 🍴 Restaurants
- 🚉 Transportation points
- 📌 Nearby places
- 🧭 Location information

The application uses real place information instead of generating random businesses.

### 💰 Smart Budget Estimation

Travel With Me AI provides estimated trip expenses including:

- 🏨 Hotel
- 🍴 Food
- 🚗 Transportation
- 🎟️ Activities
- 🛍️ Miscellaneous expenses
- 💵 Total estimated cost

All prices are displayed in **Indian Rupees (₹)**.

### 👤 User Authentication

Users can create and access their accounts through:

- Email & password registration
- Email & password login
- Google Sign-In
- Guest mode

### 👤 Profile

Users can manage their travel profile including:

- Name
- Email
- Profile picture
- Travel preferences
- Favorite destinations
- Trip information
- Account settings

### 💬 AI Travel Assistant

Users can interact with an AI travel assistant to ask questions about:

- Destinations
- Activities
- Food
- Transportation
- Travel planning
- Local attractions
- Travel tips

### 📔 Travel Diary

Users can record their travel experiences, memories, and visited places.

### 💳 Expense Tracking

Track travel expenses and organize spending during trips.

### 🎒 Packing List

Create and manage personalized packing lists for trips.

### 🛡️ Travel Safety

Access useful safety information and travel recommendations.

### 👥 Travel Community

Users can share travel experiences, posts, recommendations, and discover experiences from other travelers.

### 📱 Android Application

The web application can also be packaged as an Android application using **Capacitor**.

---

# 🏗️ Technology Stack

## Frontend

- React.js
- TypeScript
- Vite
- HTML5
- CSS3
- Tailwind CSS
- Lucide Icons

## Backend

- Node.js
- Express.js
- TypeScript
- REST APIs

## Artificial Intelligence

- Groq API
- Large Language Models (LLM)
- Prompt Engineering
- Structured JSON AI Responses

## Maps & Location

- Google Maps API
- Google Places API
- Google Geocoding Services

## Database

- PostgreSQL
- pgAdmin 4

## Authentication

- Email & Password Authentication
- Google OAuth
- Secure password hashing

## Mobile

- Capacitor
- Android Studio
- Android SDK
- Gradle

## Development Tools

- Visual Studio Code
- Antigravity
- Git
- GitHub
- npm
- Chrome DevTools
- Android Studio
- pgAdmin

---

# 🧠 How It Works

The main AI travel planning workflow is:

```text
User Input
    ↓
Destination & Trip Preferences
    ↓
Google Maps / Places
    ↓
Real Hotels, Restaurants & Attractions
    ↓
Groq AI
    ↓
Structured Itinerary
    ↓
Budget Estimation
    ↓
Travel Plan UI
    ↓
Google Maps Navigation
