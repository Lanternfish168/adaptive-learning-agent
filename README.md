# Adaptive Learning Agent

An AI-powered adaptive learning system that analyzes quiz performance and automatically generates personalized learning feedback and one-week study plans using Google Gemini 2.5 Flash.

## Project Overview

This project demonstrates how an AI Agent can analyze quiz performance and automatically generate personalized learning feedback and study plans.

The goal is to provide adaptive learning recommendations for students based on their quiz results.

## Project Structure

```
adaptive-learning-agent/
│
├── adaptive-learning-agent.ipynb
└── README.md
```

---

## Features

- Quiz performance analysis
- Identify strengths
- Identify weaknesses
- Generate adaptive feedback
- Generate personalized one-week study plans
- Powered by Google Gemini 2.5 Flash

---

## Technologies

- Python
- Google Gemini 2.5 Flash
- Google GenAI SDK
- Kaggle Notebook
- Kaggle Secrets
- GitHub

---

## Workflow

```text
Student Quiz
      │
      ▼
Gemini Analysis
      │
      ▼
Strength & Weakness Detection
      │
      ▼
Adaptive Feedback
      │
      ▼
Personalized Study Plan
```

## Example Output

```text
============================================================
ADAPTIVE FEEDBACK
============================================================

Performance Summary
-------------------
Score: 2 / 5

Strengths
----------
- Motivation
- Engagement

Weaknesses
----------
- Control Flow
- Functions
- Python Basics

What to Study Next
------------------
- Variables
- Loops
- Functions
- Lists

One-Week Study Plan
-------------------
Day 1: Python Basics
Day 2: Operators
Day 3: If / Else
...
```

## How to Run

1. Open the notebook in Kaggle.
2. Add your `GOOGLE_API_KEY` to Kaggle Secrets.
3. Run all notebook cells.
4. The AI agent will analyze quiz performance.
5. Receive personalized adaptive learning feedback.

---

## Future Improvements

- Memory
- RAG (Retrieval-Augmented Generation)
- Tool Calling
- Multi-Agent Collaboration
- Web Interface (Streamlit)

---

## License

This project is intended for educational and portfolio purposes.

## Author

Lanternfish168
