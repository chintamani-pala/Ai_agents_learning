# Agentic AI Learning

This repository is a hands-on learning project focused on foundational Python concepts used in agentic AI and modern LLM-driven applications.

It contains practical notebook-based exercises for:
- asynchronous programming in Python
- data validation and schema enforcement with Pydantic
- building more robust, reliable agent workflows

## Project Structure

- `1_Async_programming/` - notebooks and examples covering synchronous vs asynchronous execution, delays, and concurrency patterns.
- `2_pydantic_for_agents/` - notebooks focused on Pydantic, type-safe validation, and why runtime validation matters in agent pipelines.
- `requirements.txt` - Python dependencies used across the project.

## Topics Covered

### 1. Async Programming
The async notebook demonstrates:
- how synchronous code blocks execution
- the impact of waiting on multiple operations
- how asynchronous patterns can improve responsiveness and efficiency

### 2. Pydantic for Agents
The Pydantic notebook introduces:
- validating user and model input data
- enforcing type constraints
- preventing runtime errors caused by malformed data
- building safer AI and automation workflows through structured validation

## Requirements

- Python 3.10+
- Jupyter Notebook / VS Code with Python extensions

## Setup

```bash
python -m venv .venv
```

On Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Running the Notebooks

Open the notebooks in VS Code or Jupyter and run the cells in order:

- `1_Async_programming/asyncronous.ipynb`
- `2_pydantic_for_agents/pydantic for agent.ipynb`

## Goals

This project is intended as a learning space for understanding two core building blocks of agentic AI systems:
- efficient execution patterns
- reliable data validation and schema handling

## Notes

The repository is intentionally lightweight and beginner-focused, designed for experimentation and learning rather than production deployment.
