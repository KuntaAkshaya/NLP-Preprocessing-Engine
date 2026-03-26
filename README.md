# 🧠 NLP Preprocessing Engine

## 📌 Project Overview
This project is part of the Data Science Internship (February 2026).  
The goal is to build a robust NLP preprocessing engine that converts raw, noisy text into clean and structured data suitable for machine learning models.

---

## 🚀 Features Implemented

- 🔹 Lowercase conversion
- 🔹 Removal of numbers
- 🔹 Removal of URLs and email patterns
- 🔹 Handling repeated characters (e.g., "soooo" → "so")
- 🔹 Removal of special characters and emojis
- 🔹 Removal of extra spaces
- 🔹 Tokenization
- 🔹 Removal of short words (≤ 2 characters, except "no", "not")

---

## 🛠️ Technologies Used

- Python 🐍
- Google Colab
- Regular Expressions (re)
- Collections (Counter)

---

## 📊 Tasks Covered

### ✅ Task 1: Conceptual Understanding
Answered theoretical NLP questions.

### ✅ Task 2: Preprocessing Function
Implemented `preprocess_text()` function.

### ✅ Task 3: Stress Testing
Tested on real-world noisy sentences.

### ✅ Task 4: Token Analytics
Calculated:
- Total tokens
- Unique tokens
- Average token length

### ✅ Task 5: Frequency Analysis
Used `Counter` to find:
- Top 10 frequent words
- Least frequent words

### ✅ Task 6: Full Pipeline
Built reusable pipeline:
```python
def full_pipeline(text_list):
