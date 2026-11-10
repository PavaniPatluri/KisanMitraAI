# 🌾 KisanMitra AI – Your Intelligent Farming Companion

### Every Farmer Deserves an AI Expert.

KisanMitra AI is a multilingual, voice-first AI-powered agricultural assistant designed to empower Indian farmers with accessible, intelligent, and personalized farming guidance.

The platform combines Generative AI, voice technology, image recognition, and agricultural intelligence to help farmers identify crop diseases, understand weather conditions, access market prices, and make informed farming decisions in their native languages.

**Built for: The Great Indian AI Internship Challenge**

---

## 🚀 Project Overview

Millions of Indian farmers face challenges such as crop diseases, unpredictable weather, limited access to agricultural experts, language barriers, and fragmented agricultural information.

KisanMitra AI addresses these challenges through a unified AI-powered platform that allows farmers to interact naturally using voice, text, and images.

Instead of navigating complicated applications, farmers can simply speak to their AI farming companion and receive understandable, actionable guidance.

### 🎯 Our Mission

To make intelligent agricultural assistance accessible to every Indian farmer, regardless of language, technical knowledge, or location.

---

## ✨ Key Features

### 1. 🌱 AI Crop Doctor
Identify potential crop diseases and pest-related problems using AI-powered image analysis.

- Upload crop photographs.
- Analyse visible symptoms.
- Identify possible diseases.
- Assess potential severity.
- Receive recommended next steps.
- Get preventive farming guidance.

### 2. 🎙️ Multilingual Voice Assistant

Interact with an intelligent farming assistant using natural voice conversations.

**Supported Languages:**
- Telugu
- Hindi
- English
- Tamil
- Kannada
- Marathi

Features:
- Speech-to-text conversion.
- AI-powered question answering.
- Natural voice responses.
- Conversation history.
- Regional language support.

### 3. 🌦️ Weather Intelligence

Get weather information and farming recommendations.

- Current weather conditions.
- Temperature and humidity.
- Rainfall forecasts.
- Weather alerts.
- Weather-based farming suggestions.

### 4. 💰 Smart Mandi Price Intelligence

Help farmers make informed decisions before selling their produce.

- Crop-wise market prices.
- Mandi price comparisons.
- Minimum and maximum prices.
- Historical price trends.
- Market intelligence.

### 5. 🏛️ Government Scheme Assistant

Access agricultural government scheme information in a simplified format.

Includes:
- PM-KISAN.
- Kisan Credit Card.
- Crop Insurance.
- Agricultural Subsidies.

Provides scheme explanations, eligibility information, required documents, and application guidance.

### 6. 🧠 Personalized Farm Intelligence

Maintain an individual farmer profile to generate contextual recommendations.

Farmer profile includes:
- Location.
- Land area.
- Soil type.
- Irrigation method.
- Crop type.
- Crop growth stage.
- Preferred language.

### 7. 🚨 Farm Risk Intelligence

Assess potential farming risks using available information.

- Weather-related risks.
- Crop health concerns.
- Irrigation conditions.
- Crop-stage-related risks.

Displays Low, Medium, and High risk classifications with explanations.

---

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Frontend | React, TypeScript |
| UI Framework | Tailwind CSS |
| Icons | Lucide React |
| Animations | Framer Motion |
| Charts | Recharts |
| Backend | Node.js / FastAPI |
| Database | Firebase / SQLite |
| AI Intelligence | Google Gemini |
| Speech-to-Text | Gnani AI Prisma |
| AI Language Processing | Gnani AI Evon |
| Text-to-Speech | Gnani AI Timbre |
| Image Analysis | Gemini Vision |
| Market Data | AGMARKNET |
| Weather Data | Weather API |
| Development | Google AI Studio |

*The actual backend and integrations should reflect the implementation in the repository.*

---

## 🏗️ System Architecture

```text
              FARMER
                 |
          KisanMitra AI
                 |
       +---------+---------+
       |         |         |
      Voice     Image     Text
       |         |         |
       v         v         v
    Gnani AI   Gemini    Gemini
     Prisma    Vision    AI
       |         |         |
       v         v         |
   Speech to   Crop        |
     Text     Analysis     |
       |         |         |
       +---------+---------+
                 |
          AI Processing
                 |
        Personalized Guidance
                 |
       +---------+---------+
       |         |         |
     Voice    Dashboard  Alerts
    Response   Reports   & Tasks
       |         |         |
       +---------+---------+
                 |
               FARMER
```

---

## 📸 Application Modules

| Module | Description |
|---|---|
| Dashboard | Overview of farm activities and insights |
| AI Crop Doctor | Image-based crop analysis |
| Voice Assistant | Multilingual voice interaction |
| Weather Intelligence | Weather monitoring and alerts |
| Mandi Prices | Agricultural market comparison |
| Government Schemes | Agricultural scheme information |
| My Farm | Farmer profile and crop management |
| Farm Intelligence | Personalized recommendations |

---

## 💡 Example Use Case

**Scenario: A cotton farmer from Warangal**

A farmer notices unusual spots on cotton leaves.

Instead of searching online or travelling immediately to an agricultural expert:

1. Opens KisanMitra AI.
2. Selects Telugu as the preferred language.
3. Opens the Voice Assistant.
4. Describes the crop problem.
5. Uploads a photograph of the affected leaves.
6. AI analyses the photograph.
7. Receives possible disease identification and preventive guidance.
8. Saves the consultation for future reference.

The farmer receives understandable agricultural guidance through a simple voice-first experience.

---

## ⚙️ Installation and Setup

### Prerequisites

- Node.js 18+
- npm
- Python 3.10+ (if using FastAPI backend)
- Git
- Google Gemini API key
- Gnani AI API credentials (for live voice integrations)

### 1. Clone the Repository

```bash
git clone https://github.com/PavaniPatluri/KisanMitraA
cd KisanMitra-AI
```

### 2. Install Dependencies

For the frontend:

```bash
npm install
```

For the backend, if using FastAPI:

```bash
pip install -r requirements.txt
```

### 3. Configure Environment Variables

Create a `.env` file.

```env
GEMINI_API_KEY=your_gemini_api_key

GNANI_API_KEY=your_gnani_api_key

WEATHER_API_KEY=your_weather_api_key

DATABASE_URL=your_database_url
```

Use the actual variable names expected by your implementation.

Never upload `.env` files or API credentials to GitHub.

### 4. Run the Application

Frontend:

```bash
npm run dev
```

FastAPI backend, if applicable:

```bash
uvicorn main:app --reload
```

Open the frontend URL displayed in your terminal.

---

## 🌍 Real-World Impact

KisanMitra AI aims to:

- Improve access to agricultural information.
- Reduce language barriers.
- Encourage early identification of crop problems.
- Support informed farming decisions.
- Make agricultural knowledge more accessible.
- Bridge the gap between farmers and agricultural experts.

Our vision is to make AI technology useful and accessible to India's agricultural community.

---

## 🔮 Future Enhancements

- WhatsApp-based farming assistant.
- Offline voice assistance.
- IoT-based soil monitoring.
- Satellite-based crop monitoring.
- Advanced crop disease detection.
- Personalized crop recommendations.
- Agricultural expert consultation.
- AI-powered yield estimation.
- Regional agricultural knowledge integration.

---

## 🏆 Hackathon

**The Great Indian AI Internship Challenge**

KisanMitra AI demonstrates how multilingual AI, voice technology, and intelligent image analysis can be applied to solve practical agricultural challenges in India.

---

## 👩‍💻 Built With

**KisanMitra AI – Every Farmer Deserves an AI Expert.**

Designed to make agricultural intelligence accessible through the power of AI.

---

## 📄 Disclaimer

KisanMitra AI provides AI-generated preliminary agricultural guidance for informational purposes. Crop disease identification and farming recommendations may not always be accurate. Farmers should consult qualified agricultural experts and verified government agricultural resources before making important crop treatment or financial decisions.

Weather forecasts and mandi prices depend on external data availability and may change.

---
