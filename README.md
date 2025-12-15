<div align="center">

# ✈️ SkyPath: AI-Powered Travel Assistant

### 🏆 Proudly awarded **4th place** at the UiPath Future Forward Hackathon 2025!

<p>
<img src="https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Django-5.0-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
<img src="https://img.shields.io/badge/React-18.3-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-5.5-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Tailwind_CSS-3.4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind" />
<img src="https://img.shields.io/badge/OpenAI-API-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
<img src="https://img.shields.io/badge/Amadeus-API-1B69BC?style=for-the-badge&logo=amadeus&logoColor=white" alt="Amadeus" />
</p>

*Revolutionizing travel planning with AI-powered multi-agent orchestration*

</div>

---

## 📖 Overview

**SkyPath** is an AI-powered travel assistant designed to streamline the entire trip-planning experience. Instead of dealing with chaotic aggregators and irrelevant options, SkyPath uses specialized AI agents connected directly to real Amadeus data to deliver accurate and personalized travel plans.

---

## ✨ Key Features

### 🛫 Flight Optimization Engine
- Refines schedules, budgets, layovers, luggage rules, and travel constraints
- **No hallucinations**: uses clean, real Amadeus data

### 🏨 Hotel Recommendations
- Suggests accommodations based on location, price, preferences, and style
- Powered by Amadeus hotel datasets

### 📅 Custom Itinerary Generator
- Builds tailored day-by-day itineraries using user interests
- Time optimization, context awareness, and local activity data

### 🤖 Multi-Agent AI System
- Smart agents collaborate to enhance accuracy, filtering, and relevance
- Seamless orchestration throughout the planning flow

---

## 🏗️ Architecture

┌─────────────────────────────────────────────────────────────┐ │ 🎯 ORCHESTRATOR AGENT │ │ (Receives & Coordinates Requests) │ └─────────────────────┬───────────────────────────────────────┘ │ ┌─────────────┼─────────────┐ ▼ ▼ ▼ ┌───────────┐ ┌───────────┐ ┌───────────┐ │ ✈️ Flight │ │ 🏨 Hotel │ │ 📋 Itinerary│ │ Agent │ │ Agent │ │ Agent │ └─────┬─────┘ └─────┬─────┘ └─────┬─────┘ │ │ │ └──────────────┼──────────────┘ ▼ ┌─────────────────────┐ │ 🔗 AMADEUS API │ │ (Real-Time Data) │ └─────────────────────┘


---

## 🛠️ Tech Stack

| Layer | Technology | Description |
|-------|------------|-------------|
| **Backend** | Django (Python) | Multi-agent orchestration, Amadeus API integration |
| **Frontend** | React + TypeScript | Modern UI with Vite & Tailwind CSS |
| **AI** | OpenAI + Custom Agents | LLM coordination, data validation, context sharing |
| **Data** | Amadeus API | Real-time flight, hotel, and activity data |

---

## 📁 Project Structure

```text
📦 UiPath-Hackathon-2025
├── 📂 backend/
│   ├── 📂 apps/           # Django applications
│   ├── 📂 config/         # Django configuration
│   ├── 📂 services/       # Business logic & agents
│   └── 📄 manage.py       # Django management script
├── 📂 frontend/
│   ├── 📂 src/            # React source code
│   ├── 📄 package.json    # Node dependencies
│   └── 📄 vite.config.ts  # Vite configuration
├── 📄 requirements.txt    # Python dependencies
└── 📄 README.md           # This file
