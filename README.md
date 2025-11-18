# ✈️ AI Trip Planner Agent

This is an AI Agent built using **Python** and **Google Gemini** that functions as an intelligent travel concierge. 

Unlike a standard chatbot, this agent can **reason** and **use tools**. It autonomously searches the web for attractions and checks live weather data to build a realistic itinerary based on the user's request.

---

## 🤖 How It Works

The agent utilizes a **ReAct (Reasoning + Acting)** approach:
1.  **Thought:** The agent analyzes the user's request (e.g., "Plan a trip to London").
2.  **Tool Call:** It decides it needs information and calls the `Google Search` tool.
3.  **Observation:** It reads the search results.
4.  **Tool Call:** It realizes it needs weather data and calls the `Open-Meteo` tool.
5.  **Final Answer:** It synthesizes all data into a complete itinerary.

---

## 🛠️ Tech Stack

* **Language:** Python
* **AI Model:** Google Gemini Pro (via `google-generativeai`)
* **Search Tool:** Serper API (Google Search wrapper)
* **Weather Tool:** Open-Meteo API
* **Environment:** Kaggle Notebooks

---

## 🚀 How to Run

The easiest way to run this project is directly in Kaggle, as it handles the environment setup.

**👉 Click Here to View & Run on Kaggle: https://www.kaggle.com/code/mdsharikansari/ai-trip-planner**

### Prerequisites for Local Run
If you want to run this locally, you will need:
1.  `pip install google-generativeai requests`
2.  A Google AI Studio API Key
3.  A Serper.dev API Key
