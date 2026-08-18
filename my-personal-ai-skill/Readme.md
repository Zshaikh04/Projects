# Personal AI Chatbot Skill

A personal AI chatbot built with **Python, Ollama, Llama 3.2, and Gradio**. The chatbot works as a general-purpose AI assistant while also having access to a Markdown-based knowledge base containing information about Zaid.

The personal knowledge feature is activated using the keyword **"Zaid"**.

## Features

* General-purpose AI chatbot
* Personal knowledge skill using a Markdown file
* Keyword-based activation using `Zaid`
* Case-insensitive keyword detection
* Local LLM inference using Ollama
* Powered by Llama 3.2
* Simple Gradio chat interface
* Personal information stored separately from the Python code
* No external API key required when running Ollama locally

## How It Works

The chatbot uses a Markdown file as its knowledge and instruction source.

```text
User Message
     |
     v
Does the message contain "Zaid"?
     |
   +---+---+
   |       |
  YES      NO
   |       |
   v       v
Skill.md  Skill.md
   |       |
   +---+---+
       |
       v
    Llama 3.2
       |
       v
    Response
```

When `Zaid` is mentioned, the chatbot can answer questions about Zaid using the information stored in `Skill.md`.

For normal questions, the chatbot behaves as a general-purpose AI assistant.

### Example

```text
User: Zaid what projects have you worked on?

Chatbot: [Answers using Zaid's personal information]
```

```text
User: What is Retrieval-Augmented Generation?

Chatbot: [Answers normally using the LLM]
```

## Project Structure

```text
my-personal-ai-skill/
│
├── Skill.md
├── Llm_chat_bot.ipynb
└── README.md
```

### `Skill.md`

Contains:

* Chatbot behavior instructions
* Zaid's personal information
* Skills
* Education
* Projects
* Professional background
* Hobbies

### `Llm_chat_bot.ipynb`

Contains the Python code responsible for:

* Loading the Markdown skill
* Connecting to Ollama
* Sending prompts to Llama 3.2
* Detecting the `Zaid` keyword
* Running the Gradio chatbot

## Technologies Used

* **Python**
* **Ollama**
* **Llama 3.2**
* **Gradio**
* **OpenAI Python SDK**
* **Markdown**

## Requirements

Make sure you have:

* Python installed
* Ollama installed
* Llama 3.2 downloaded through Ollama
* Required Python packages installed

Install the Python dependencies:

```bash
pip install openai gradio
```

Install and run the Llama 3.2 model with Ollama:

```bash
ollama pull llama3.2
```

Make sure Ollama is running before launching the chatbot.

## Running the Project

Clone the repository:

```bash
git clone <your-repository-url>
```

Move into the project directory:

```bash
cd my-personal-ai-skill
```

Start the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Llm_chat_bot.ipynb
```

Run the cells and launch the Gradio interface.

## Example Questions

### Personal Questions

Use `Zaid` when asking about the personal knowledge base:

```text
Zaid what are your skills?
```

```text
Zaid what projects have you worked on?
```

```text
Zaid tell me about your education
```

```text
Zaid tell me about your Agentic AI Study Assistant
```

### General Questions

The chatbot can also answer normal questions without the keyword:

```text
What is RAG?
```

```text
Explain LangGraph
```

```text
What is Python?
```

## Privacy

The chatbot uses **Ollama and Llama 3.2 locally**, allowing the project to run without sending personal resume information to a hosted AI API.

Personal information is stored in the local `Skill.md` file.

## Personal Knowledge Base

The Markdown knowledge base contains information about:

* AI Engineering skills
* Python and FastAPI
* Generative AI and Agentic AI
* RAG
* LangGraph
* CrewAI
* LangFuse
* ChromaDB
* Docker
* Academic background
* AI projects
* Hobbies

## Future Improvements

Possible improvements include:

* Conversation history support
* Better intent detection for personal questions
* More structured personal knowledge
* Retrieval-based searching through the Markdown file
* Voice interaction
* Improved Gradio UI
* Multiple personal knowledge files
* Authentication and privacy controls

## Author

**Zaid Shaikh**

Aspiring AI Engineer interested in Machine Learning, Generative AI, Agentic AI, LLMs, and building intelligent applications.
