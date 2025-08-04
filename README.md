# Math Quiz Game in Java 🎯

This is a simple Java console application that generates random arithmetic questions for the user to solve. The user answers 5 questions and receives a final score at the end of the quiz.

---

## 📂 Files in the Project

| File Name         | Purpose                                      |
|-------------------|----------------------------------------------|
| `Question.java`   | Generates a random arithmetic question and checks the user's answer. |
| `MathQuiz.java`   | Handles the quiz logic and score calculation. |
| `main.java` (or `CarEngine.java`) | The main entry point that starts the quiz game. |

---

## ✅ Features

- Random arithmetic questions using `+`, `-`, `*`, or `/`
- Division handled with floating point precision
- Score is tracked and displayed at the end
- Object-oriented structure using 3 separate classes

---

## 🚀 How to Compile and Run

1. **Save the files**:
   - `Question.java`
   - `MathQuiz.java`
   - `main.java` 

2. **Compile** all files:
   ```bash
   javac Question.java MathQuiz.java main.java
   Run the main class: java main

📌 Sample Output:
What is 42 + 17?
Your answer: 59
Correct!
What is 36 / 9?
Your answer: 4
Incorrect.
...
Your final score is: 3/5

