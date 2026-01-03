**Developed by : Pearl Viralkumar Patel**

- This AI Agent is an AI coding helper built with LangGraph
- It works like a small team of developers. You can give it a request in normal language, and it will turn it into a complete working project — creating each file step by step like real developers do.

## Architecture

- Planner Agent – Analyzes your request and generates a detailed project plan.
- Architect Agent – Breaks down the plan into specific engineering tasks with explicit context for each file.
- Coder Agent – Implements each task, writes directly into files, and uses available tools like a real developer.

## Requirements

- Make sure you have uv installed, follow the instructions - (https://docs.astral.sh/uv/getting-started/installation/) to install it.
- Ensure that you have created a groq account and have your API key ready. Create an API key - (https://console.groq.com/keys).

## Instsllstion guide

- Create a virtual environment using: `uv venv`
- Install the dependencies using: `uv pip install -r pyproject.toml`
- Create a `.env` file and add the variables and their respective values mentioned in the `.sample_env` file
- Run project using 'python main.py'

## Example Prompts

- Create a note-taking application using HTML, CSS, and JavaScript.
- Create a to-do list application using html, css, and javascript.
- Create a simple calculator web application.
- Create a portfolio website with responsive design using HTML, CSS, and Tailwind CSS.

**Developed by : Pearl Viralkumar Patel**
Contact : pearl31patelus@gmail.com
