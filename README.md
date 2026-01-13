## 🤖 AI Coding Agent — Overview

This **AI Agent** is an AI coding helper built with **LangGraph**.  
It works like a **small team of developers** — you can give it a request in natural language, and it will turn it into a complete working project, creating each file step by step like real developers do.

---

## 🏗️ Architecture

- **Planner Agent** — Analyzes your request and generates a detailed project plan.  
- **Architect Agent** — Breaks down the plan into specific engineering tasks with explicit context for each file.  
- **Coder Agent** — Implements each task, writes directly into files, and uses available tools like a real developer.

---

## ⚙️ Requirements

- Make sure you have **uv** installed.  
  Follow the instructions here:  
  👉 https://docs.astral.sh/uv/getting-started/installation/

- Ensure that you have created a **Groq account** and have your **API key** ready.  
  Create an API key here:  
  👉 https://console.groq.com/keys

---


## 🧩 Installation Guide

- Create a virtual environment:
  ```bash
  uv venv
  ```

- Install the dependencies:
  ```bash
  uv pip install -r pyproject.toml
  ```

- Create a `.env` file and add the variables and their respective values mentioned in the `.sample_env` file.

- Run the project:
  ```bash
  python main.py
  ```

---

## 💡 Example Prompts

- **Create a note-taking application** using HTML, CSS, and JavaScript.
- **Create a to-do list application** using HTML, CSS, and JavaScript.
- **Create a simple calculator** web application.
- **Create a portfolio website** with responsive design using HTML, CSS, and Tailwind CSS.

---

## 👤 Author

**Pearl Viralkumar Patel**  
🎓 *Master’s in Computer Engineering*, University of South Florida — **May 2026**  
💼 *Aspiring Software Engineer / Machine Learning Engineer*  
📧 **pearl31patelus@gmail.com**



