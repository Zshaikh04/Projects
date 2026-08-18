# Personal Resume Skill

## Purpose

This skill gives the chatbot access to the user's personal information
stored in `Resume.md`.

The chatbot should continue behaving like a normal general-purpose
chatbot while also being able to answer questions about the user.

## Personal Information

When the user asks about themselves, their background, education,
skills, projects, experience, hobbies, or career-related information,
use `Resume.md` as the source of truth.

## Rules

1. Read `Resume.md` when answering questions about the user.
2. Only state personal information that is present in `Resume.md`.
3. Do not invent personal information.
4. If the requested information is not present in `Resume.md`, say that
   the information is not available in the resume.
5. For general questions unrelated to the user, behave normally as a
   general-purpose chatbot.
6. Do not unnecessarily mention that you are using `Resume.md`.
7. If the user asks for information about a project listed in the
   resume, use the project's details from `Resume.md`.
8. If the user asks about the user's skills, provide the relevant skills
   from `Resume.md`.
9. If the user asks about the user's education or professional
   background, use the information in `Resume.md`.

## Examples

User:
"What skills does Zaid have?"

The chatbot should answer using the skills listed in `Resume.md`.

User:
"What projects has Zaid worked on?"

The chatbot should answer using the Projects section of `Resume.md`.

User:
"What is Zaid's education?"

The chatbot should answer using the Education section of `Resume.md`.

User:
"Explain what RAG is."

The chatbot should answer normally as a general-purpose AI assistant.

User:
"What is Zaid's favorite programming language?"

If this information is not present in `Resume.md`, the chatbot should
not guess. It should say that this information is not available.



# Zaid's Personal Information

## Role
AI Engineer

## Skills
- Python / FastAPI
- NumPy / Pandas / Matplotlib
- Generative AI
- Agentic AI
- RAG
- Prompt Engineering
- Context Engineering
- CrewAI
- LangGraph
- LangFuse
- MySQL
- ChromaDB
- Harness Engineering
- Git / GitHub Copilot
- Docker

## Professional Summary

Aspiring AI Engineer with a strong foundation in Machine Learning,
Generative AI and Large Language Models (LLMs). Hands-on experience
building AI agents, RAG applications, chatbots and evaluating LLM
workflows using tools like LangGraph, LangChain and Langfuse.

## Projects

### Agentic AI Study Assistant
December 2025 — March 2026

- Developed an Agentic AI-powered Study Assistant using RAG, LangGraph
  and Python.
- Built a PDF processing pipeline with vector embeddings and semantic
  search.
- Integrated Ollama with Llama 3.2 for privacy-focused offline AI.
- Designed an agent-driven architecture for context-aware answers.

### AI Gym Assistant Chatbot
August 2024 — September 2024

- Developed an AI-powered Gym Assistant Chatbot.
- Built conversational workflows for workout and nutrition
  recommendations.
- Implemented LLM-based responses.
- Developed the backend in Python.

## Education

Bachelor of Science in Information Technology
University of Mumbai, Mumbai

April 2022 — April 2026

## Hobbies

- Chess
- Fitness & Strength Training
- Rubik's Cube Solving