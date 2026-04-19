# 🧠 Smart Quiz & Performance Analyzer System (Console-Based)

## 📌 Overview

This project is a **console-based quiz system** developed using Python. It is designed to not only conduct quizzes but also **analyze user performance intelligently** using conditions and loops.

The system provides **detailed feedback, difficulty selection, negative marking, and leaderboard tracking**, making it more advanced than a basic quiz program.

---

## 🎯 Objective

To build a smart quiz system that:

* Conducts MCQ-based quizzes
* Tracks user performance
* Identifies strengths and weaknesses
* Provides meaningful feedback

---

## ⚙️ Features

### 🎮 Quiz System

* Multiple-choice questions (MCQs)
* Immediate feedback for each answer
* Input validation (A/B/C/D only)

---

### 📋 Menu-Driven Interface

Users can select:

1. Start Quiz
2. View Leaderboard
3. View Last Score
4. Exit

---

### 🧩 Difficulty Levels

* Easy
* Medium
* Difficult

Each level has a different set of questions.

---

### 🧮 Scoring System

* ✅ +1 for correct answer
* ❌ -1 for wrong answer (**Negative Marking**)

---

### 📊 Performance Analysis

The system evaluates performance based on percentage:

| Percentage | Level        | Feedback              |
| ---------- | ------------ | --------------------- |
| < 50%      | Beginner     | Needs more practice   |
| 50–74%     | Intermediate | Good job              |
| ≥ 75%      | Advanced     | Excellent performance |

---

### 🧠 Intelligent Feedback

Users receive personalized feedback based on their performance level.

---

### 🏆 Leaderboard System (Bonus Feature)

* Stores multiple attempts
* Displays:

  * Name
  * Score
  * Percentage
  * Level

---

### 🔁 Last Attempt Tracking

* Shows the most recent quiz result

---

### ⚠️ Input Validation

* Prevents invalid menu selections
* Ensures answers are only A/B/C/D

---

## 🛠️ Technologies Used

* Python (Core Concepts Only)

  * Variables
  * Loops (`for`, `while`)
  * Conditions (`if-elif-else`)
  * Lists & Dictionaries

> ❌ No external libraries used
> ❌ No GUI used

---

## ▶️ How to Run

### Run in Jupyter Notebook

1. Open `Hackathon.ipynb`
2. Run all cells

### OR Convert to Python Script

```bash
jupyter nbconvert --to script Hackathon.ipynb
python Hackathon.py
```

---

## 📸 Sample Output

```
WELCOME TO SMART QUIZ & PERFORMANCE ANALYZER SYSTEM

1. Start Quiz
2. Leaderboard
3. Last Score
4. Exit
```

### Example Result:

```
===== RESULT =====
Name: mk
Correct Answers: 4
Wrong Answers: 1
Score: 3
Percentage: 60.0%
Level: Intermediate
Feedback: Good job!
```

---

## 💡 Custom Features Implemented

✔ Difficulty Levels
✔ Negative Marking
✔ Leaderboard Tracking (Bonus)
✔ Performance-Based Feedback

---

## 📈 Future Improvements

* Add timer for each question
* Randomize questions
* Save leaderboard to file
* Add categories (Science, Math, etc.)

---

## 📊 Evaluation Criteria Coverage

| Criteria             | Status |
| -------------------- | ------ |
| Logic Implementation | ✅      |
| Performance Analysis | ✅      |
| Creativity           | ✅      |
| Functionality        | ✅      |
| Input Handling       | ✅      |

---

## 👨‍💻 Author

**Munawar Khan**

---

## 📜 License

This project is for educational purposes and free to use.

---
