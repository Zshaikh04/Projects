# 🌤️ Weather Agentic AI

An Agentic AI application that uses **LangGraph**, **Llama 3.2**, **OpenWeatherMap API**, and **Gradio** to analyze real-time weather conditions and autonomously decide whether a heater should be turned **ON** or **OFF**.

Unlike a traditional weather application, this project demonstrates an **agentic workflow**, where the AI retrieves live weather data, reasons about it, invokes the appropriate tool, and provides a final recommendation.

## 🚀 Features

- 🌍 Live weather information using OpenWeatherMap API
- 🤖 AI reasoning powered by Llama 3.2 (Ollama)
- 🔄 LangGraph workflow orchestration
- 🔥 Smart heater ON/OFF decision
- 🖥️ Interactive Gradio web interface
- 📊 Displays temperature, humidity, and weather conditions

## 🛠️ Tech Stack

- Python
- LangGraph
- LangChain
- Ollama
- Llama 3.2
- OpenWeatherMap API
- Gradio
- Requests

## 🔄 Workflow

```
User
   │
   ▼
Enter City
   │
   ▼
Weather API
   │
   ▼
LangGraph
   │
   ▼
Llama 3.2
   │
   ▼
Heater Tool
   │
   ▼
Final Recommendation
```

## 📂 Project Structure

```
Weather-Agentic-AI/
│── Weather_Agent.ipynb
│── README.md
│── requirements.txt
```

## 🎯 Project Goal

This project showcases how Agentic AI systems can combine LLM reasoning with external tools to perform intelligent, real-world tasks rather than simply answering questions.

## 👨‍💻 Author

**Zaid Shaikh**
