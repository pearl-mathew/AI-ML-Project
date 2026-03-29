# AI-ML-Project
# 📊 Simple Sentiment Analyzer (Rule-Based NLP)
### A Python-based decision engine to categorize text sentiment.

## 📖 Project Overview
This project is a computational system designed to automatically determine the emotional tone of a piece of text. In an era of massive digital feedback, this tool demonstrates how **Natural Language Processing (NLP)** can transform unstructured human language into organized, actionable data (Positive, Negative, or Neutral).

Built as a **Rule-Based Lexicon System**, this program avoids complex external libraries to showcase the fundamental logic behind string manipulation, data preprocessing, and conditional decision-making in Python.

---

## 🚀 How it Works (The Logic)
The analyzer follows a specific four-step pipeline to simulate human decision-making:

1.  **Data Preparation:** Uses a pre-defined "knowledge base" (dictionary) of positive and negative keywords.
2.  **Preprocessing:** Standardizes input using `.lower()` to ensure the system is case-insensitive (e.g., treating "GREAT" and "great" identically).
3.  **Scanning Process:** Iterates through the text using membership operators to identify keyword matches.
4.  **Decision Engine:** Implements a scoring system (`pos_count` vs `neg_count`) to determine the final sentiment through conditional logic.

---

## 🛠️ Features & Key Decisions
* **Simplicity over Complexity:** Written in pure Python without external dependencies (like TextBlob) to demonstrate core algorithmic thinking.
* **Handling Ambiguity:** Includes a dedicated **Neutral** category for balanced or keyword-free sentences to prevent "forced" miscategorization.
* **Robust Preprocessing:** Automatically handles user formatting to ensure consistent accuracy.

---

## 💻 Setup and Usage

### Prerequisites
* Python 3.x installed on your machine.

## 💻 Setup and Usage

#### Prerequisites
* **Python 3.x** installed on your system.

#### Installation
1.  **Clone this repository** to your local machine:
    ```bash
    git clone [https://github.com/Pearl-Mathew/sentiment_analyzer.git](https://github.com/Pearl-Mathew/sentiment_analyzer.git)
    ```
2.  **Navigate** into the project folder:
    ```bash
    cd sentiment_analyzer
    ```

### Running the Program
1.  Run the script via your terminal or IDE:
    ```bash
    python sentiment_analyzer.py
    ```
2.  Enter any sentence when prompted (e.g., *"I had a great day today!"*).
3.  The program will immediately return the detected sentiment with a corresponding emoji.

---

## ⚠️ Known Limitations
As a rule-based system, this project highlights the foundational challenges of modern AI:
* **Context Blindness:** It currently cannot detect negation (e.g., "not good" may be seen as positive).
* **Sarcasm Detection:** Literal keyword matching may misinterpret sarcastic intent.
* **Lexicon Limits:** Accuracy is tied to the size of the internal dictionary.

---

## 🎓 Learning Outcomes
This project served as my gateway into **Artificial Intelligence**:
* Realized that **Data Preprocessing** is just as critical as the algorithm itself.
* Gained experience in **Control Flow** (loops and conditionals) for real-world problem-solving.
* Understood the transition from "rigid" rule-based systems to the flexible needs of modern AI.

---
**Author:** Pearl Mathew  
**Specialization:** B.Tech CSE (Health Informatics) '29 | VIT Bhopal University
