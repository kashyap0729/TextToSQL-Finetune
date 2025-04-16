# Fine-Tuning LLMs for Text-to-SQL Generation 🧠📊

This project explores the fine-tuning of large language models (LLMs) to convert natural language queries into SQL using synthetic data from GretelAI. We experimented with two models: **LLaMA 3 (8B)** and **DeepSeek-R1:8B**, optimized for SQL generation using efficient training techniques and deployed for local inference via Ollama.

---

## 🚀 Objective

- Convert natural language queries into valid SQL statements.
- Improve SQL generation accuracy through supervised fine-tuning.
- Deploy optimized models locally for fast and lightweight inference.

---

## 🗃 Dataset

- Source: [GretelAI Synthetic Text-to-SQL Dataset](https://gretel.ai/)
- Format: 
  ```json
  {
    "SQL Prompt": "Which employees earn more than $5000?",
    "SQL": "SELECT name FROM employees WHERE salary > 5000",
    "Explanation": "Filters employees earning more than 5000"
  }
