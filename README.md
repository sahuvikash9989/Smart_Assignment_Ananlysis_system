# Smart_Assignment_Ananlysis_system


This is a simple web application for teachers.  
It helps teachers upload student assignment answers and automatically get:

- class insights
- common mistakes
- weak concepts
- answer clusters
- scores and teaching suggestions

The goal is to save teachers’ time and give meaningful feedback instead of only marks.

---

## What problem does this project solve?

Teachers spend a lot of time reading every answer to find:

- common mistakes
- weak understanding
- repeated answers
- class level patterns

This project automatically analyses student answers and shows all this information in one dashboard.

---

## Main features

- Teacher login and registration
- Upload assignment file (CSV or JSON)
- Automatic grouping of answers by question
- Similarity analysis between answers
- Answer clustering
- Weak concept detection
- Insight score and confidence score
- Structured teaching summary for every question

---

## Technologies used

- Python
- Flask
- HTML, CSS
- SQLite database
- Basic NLP and clustering techniques

---

## File format for upload

Your CSV file must be in this format:

student_id,student_name,question_id,question,answer
101,Arjun,Q1,What is recursion?,A function calling itself
102,Rahul,Q1,What is recursion?,Recursion repeats a proces


---

## How to run the project

### 1. Install Python packages
### 2. run in cmd "python app.py"

