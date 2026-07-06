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

Hello Student,

Great job on taking the quiz!

1. Performance Summary

You scored 2 out of 5 on the recent quiz.

2. Strengths

- Effort and Engagement
- Partial Understanding
- Clear Goal

3. Weaknesses

- Basic Data Structures
- Control Flow
- Functions

4. What to Study Next

1. Variables
2. Operators
3. Conditionals
4. Loops
5. Functions

5. Revised One-Week Study Plan

Day 1: Python Basics
Day 2: Data Structures
Day 3: Control Flow
...

(Example output truncated for brevity.)
```

## How to Run

1. Open the notebook in Kaggle.
2. Add your `GOOGLE_API_KEY` to Kaggle Secrets.
3. Run all notebook cells.
4. The AI agent will analyze quiz performance.
5. Receive personalized adaptive learning feedback.

---

## Future Improvements

- Long-term Memory
- RAG (Retrieval-Augmented Generation)
- Tool Calling
- Multi-Agent Collaboration
- Streamlit Web Interface
---

## License

This project is intended for educational and portfolio purposes.

## Author

Lanternfish168
