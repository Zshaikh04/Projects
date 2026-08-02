# AI Resume Chatbot with Custom Markdown Skill

## Overview

This project is an AI-powered Resume Chatbot that answers questions about my resume using a custom Markdown skill. The chatbot uses the information stored in the markdown file to provide accurate, context-aware responses about my education, skills, projects, certifications, and experience.

The project demonstrates how custom skills can be integrated with a Large Language Model (LLM) to create a personalized AI assistant.

---

## Features

- Answers questions based on my resume
- Uses a custom Markdown skill as the knowledge base
- Built using Python and Jupyter Notebook
- Context-aware responses
- Easy to update by editing the markdown file

---

## Project Structure

```
LLM/
│── skill.md          # Resume knowledge base
│── Zaid_llm.ipynb    # Chatbot implementation
```

---

## Technologies Used

- Python
- Jupyter Notebook
- Markdown
- Large Language Model (LLM)

---

## Example Questions

- What is the candidate's name?
- What programming languages does the candidate know?
- What projects has the candidate completed?
- What are the candidate's technical skills?
- What certifications does the candidate have?
- What is the candidate's educational background?

---

## How It Works

1. The chatbot loads the custom `skill.md` file.
2. The markdown file acts as the chatbot's knowledge base.
3. When a user asks a question, the LLM retrieves relevant information from the markdown skill.
4. The chatbot generates an accurate response based on the resume content.

---

## Future Improvements

- Gradio web interface
- Resume upload support
- Multiple resume support
- PDF resume parsing
- RAG (Retrieval-Augmented Generation) integration

---

## Author

**Zaid Shaikh**

B.Sc. Information Technology Student
