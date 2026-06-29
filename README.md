# 🌍 AI-Powered Travel Planner using CrewAI 

An **AI-powered Travel Planner** built with **CrewAI, Google Gemini, Streamlit, and SerperDevTool** that demonstrates the power of **Agentic AI**. This application uses multiple AI agents working together to research destinations, optimize budgets, and generate personalized travel itineraries.

---

## 🚀 Project Overview

Planning a trip requires researching destinations, estimating budgets, and creating an itinerary. This project automates the entire process using **CrewAI**, where multiple AI agents collaborate to generate a complete travel plan.

The application accepts a **destination** and **budget** from the user and produces:

- 📍 Tourist & historical attractions
- 🏨 Hotel recommendations
- 🌦 Weather information
- 💰 Budget breakdown
- 📅 Detailed day-wise itinerary

---

## ✨ Features

- 🤖 **Agentic AI Architecture using CrewAI**
- 🧠 **Google Gemini Integration**
- 🌐 **Real-Time Web Search using SerperDevTool**
- 💰 **Smart Budget Planning**
- 🗺 Personalized Travel Itinerary
- 📍 Historical Place Recommendations
- 🏨 Hotel Suggestions
- 🌦 Weather Information
- 💻 Interactive Streamlit Interface
- 🚀 Easy Deployment using Ngrok

---

# 🏗 Project Architecture

```
                    User Input
           (Destination + Budget)
                     │
                     ▼
            Streamlit User Interface
                     │
                     ▼
                 CrewAI Crew
     ┌──────────────┼──────────────┐
     │              │              │
     ▼              ▼              ▼
Travel          Budget        Itinerary
Researcher      Planner        Planner
     │              │              │
     └──────────────┼──────────────┘
                    │
                    ▼
           Google Gemini API
                    │
                    ▼
             SerperDevTool
            (Live Web Search)
                    │
                    ▼
          Final Travel Plan Output
```

---

# 🧠 AI Agents

## 1️⃣ Travel Researcher

### Responsibilities

- Search tourist attractions
- Find historical places
- Suggest hotels
- Collect weather information
- Gather destination details

---

## 2️⃣ Budget Planner

### Responsibilities

- Calculate travel expenses
- Hotel cost estimation
- Food expenses
- Local transportation
- Keep total expenses within user budget

---

## 3️⃣ Itinerary Planner

### Responsibilities

- Create a complete day-wise itinerary
- Recommend places to visit
- Schedule activities
- Optimize travel time

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| CrewAI | Multi-Agent Framework |
| Google Gemini | Large Language Model |
| Streamlit | Web Application |
| SerperDevTool | Real-Time Search |
| Ngrok | Deployment |
| dotenv | Environment Variables |

---

# 📂 Project Structure

```
AI-Travel-Planner/
│
├── app.py
├── main.py
├── agents.py
├── tasks.py
├── crew.py
├── requirements.txt
├── .env
├── README.md
└── assets/
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/pushparajsalunkhe/AI-Travel-Planner-.git
```

```bash
cd AI-Travel-Planner
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux/Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file.

```env
GOOGLE_API_KEY=GEMINI_API_KEY
SERPER_API_KEY=SERPER_API_KEY
```

---

# ▶ Running the Application

```bash
streamlit run app.py
```

---

# 🚀 Deployment

Deploy the Streamlit application using **Ngrok**.

```bash
streamlit run app.py
```

In another terminal:

```bash
ngrok http 8501
```

Share the generated public URL.

---

# 📌 Workflow

1. User enters destination.
2. User enters travel budget.
3. CrewAI activates multiple AI agents.
4. Travel Research Agent gathers destination information.
5. Budget Agent calculates estimated expenses.
6. Itinerary Agent creates a complete travel schedule.
7. Final travel plan is displayed.

---

# 📸 Sample Output

```
Destination:
Jaipur

Budget:
₹20,000

-----------------------------------

Historical Places

• Amber Fort
• Hawa Mahal
• City Palace
• Jantar Mantar

Hotels

• Hotel A
• Hotel B
• Hotel C

Budget Breakdown

Hotel : ₹8,000
Food : ₹4,000
Transport : ₹3,000
Miscellaneous : ₹2,000

Remaining Budget : ₹3,000

3-Day Itinerary

Day 1
• Amber Fort
• Jal Mahal

Day 2
• Hawa Mahal
• City Palace

Day 3
• Jantar Mantar
• Local Shopping
```

---

# 🎯 Learning Outcomes

- Understanding Agentic AI
- Working with CrewAI
- Multi-Agent Collaboration
- Prompt Engineering
- Google Gemini API Integration
- Real-Time Web Search
- Streamlit Application Development
- AI Workflow Automation
- Deployment using Ngrok

---

# 🔮 Future Improvements

- Flight Booking Integration
- Hotel Booking APIs
- Google Maps Integration
- Restaurant Recommendations
- Voice Assistant
- PDF Travel Report
- Multi-Language Support
- Currency Converter
- Email Travel Plan
- Mobile Responsive UI

---

### ⭐ "Agentic AI is not about one intelligent model—it's about multiple intelligent agents collaborating to solve complex real-world problems."
