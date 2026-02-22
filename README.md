#  AI Text Summarizer (NLTK Based)

A simple extractive text summarization project built using **Python** and **NLTK**.
This program analyzes word frequency in a given paragraph and selects the most important sentences based on scoring.

---

## 📌 Overview

This project performs **frequency-based extractive summarization**:

* Tokenizes text into sentences and words
* Removes stopwords
* Calculates word frequencies
* Scores each sentence based on word importance
* Selects the top N highest scoring sentences as the summary

This approach is simple yet effective for short academic or informational texts.

---

## 🚀 Features

* Sentence tokenization
* Word tokenization
* Stopword removal
* Frequency-based sentence scoring
* Customizable number of summary sentences
* Clean and beginner-friendly implementation

---

## 🛠️ Technologies Used

* Python 3.x
* NLTK (Natural Language Toolkit)

---

## 📦 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/AbdullahAli2005/summarizer_using_nltk.git
cd summarizer_using_nltk
```

### 2️⃣ Install dependencies

```bash
pip install nltk
```

### 3️⃣ Download required NLTK datasets (only once)

The script automatically downloads:

* stopwords
* punkt

Or manually run:

```python
import nltk
nltk.download("stopwords")
nltk.download("punkt")
```

---

## ▶️ How to Run

```bash
python main.py
```

You can modify the `text` variable inside the script to summarize any custom paragraph.

To change summary length:

```python
summary = summarize_text(text, num_sentences=3)
```

---

## 🧩 How It Works (Algorithm Explanation)

1. Convert text to lowercase
2. Tokenize into words
3. Remove stopwords and non-alphabetic tokens
4. Count frequency of remaining words
5. Score each sentence based on cumulative word frequencies
6. Sort sentences in descending order of score
7. Select top N sentences

---



## 📜 License

This project is open-source and available under the MIT License.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

⭐ If you found this helpful, consider giving the repo a star!
