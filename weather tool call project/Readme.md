# 🌤️ Weather Agentic AI

An intelligent weather assistant built using **LangGraph**, **Llama 3.2**, **OpenWeatherMap API**, and **Gradio**.

The application fetches real-time weather data, analyzes it using a Large Language Model (LLM), and autonomously decides whether the heater should be turned **ON** or **OFF** through an agentic workflow.

---

## 🚀 Features

- 🌍 Real-time weather using OpenWeatherMap API
- 🤖 AI-powered reasoning with Llama 3.2 (Ollama)
- 🔄 LangGraph workflow orchestration
- 🔥 Smart heater ON/OFF decision
- 🖥️ Interactive Gradio web interface
- 📊 Displays temperature, humidity, and weather condition

---

## 🛠️ Tech Stack

- Python
- LangGraph
- LangChain
- Ollama
- Llama 3.2
- OpenWeatherMap API
- Requests
- Gradio

---

## 🧠 Workflow

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

---

## 📷 Application

The user enters a city name through the Gradio interface.

The AI:

1. Fetches live weather data.
2. Analyzes the temperature and weather conditions.
3. Decides whether the heater should be ON or OFF.
4. Displays the final recommendation.

---

## ▶️ Installation

```bash
pip install langgraph
pip install langchain
pip install langchain-ollama
pip install requests
pip install gradio
```

Run Ollama:

```bash
ollama serve
```

Download the model:

```bash
ollama pull llama3.2
```

Start the application by running the Jupyter Notebook.

---

## 📌 Future Improvements

- Fan/AC control
- Umbrella recommendation
- Weather alerts
- Voice assistant
- Multi-city weather comparison
- Smart home IoT integration

---

## 👨‍💻 Author

**Zaid Shaikh**

Built as an Agentic AI project using LangGraph and Llama 3.2.
