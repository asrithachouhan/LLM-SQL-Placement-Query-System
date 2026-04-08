# LLM-SQL-Placement-Query-System
Natural Language to SQL Query Generator for Placement Database using LLM
# 🚀 LLM-SQL: Natural Language to SQL Query System

This project demonstrates how Large Language Models (LLMs) can be used to convert natural language queries into SQL queries and execute them on a placement database.

---

## 📌 Features

- 🔹 Convert plain English questions into SQL queries
- 🔹 Real-time query execution on PostgreSQL/MySQL
- 🔹 Simple and interactive UI using Streamlit
- 🔹 Displays results in tabular format

---

## 🧠 Example Queries

- How many companies offered more than 20 LPA?
- Which companies hired CSE students?
- What is the highest salary offered in 2025?

---

## ⚙️ Tech Stack

- **Backend:** Python
- **Frontend:** Streamlit
- **Database:** PostgreSQL / MySQL
- **LLM:** OpenAI / Gemini / LLaMA
- **Query Language:** SQL

---

## 🗄️ Database Schema

### Students Table
- student_id
- name
- department
- CGPA

### Companies Table
- company_id
- company_name
- domain
- package

### Placements Table
- placement_id
- student_id
- company_id
- year
- job_role

---

## 🔄 System Architecture

User Input → LLM → SQL Query → Database → Output

---

## ▶️ How to Run

```bash
# 1. Create virtual environment
python3 -m venv venv

# 2. Activate environment
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run application
streamlit run app.py
