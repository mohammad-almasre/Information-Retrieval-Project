# 🔍 LSI-Based Semantic Search GUI

A user-friendly desktop application built with Python and CustomTkinter, allowing semantic search across PDF documents using **Latent Semantic Indexing (LSI)**.

---

## 🚀 Features

- Accepts **1 to 3 PDF files** for processing.
- Automatically preprocesses text (lowercase, remove stopwords/punctuation, lemmatization).
- Smart query search powered by **LSI (Latent Semantic Indexing)**.
- Clean and intuitive GUI built with `tkinter`.
- Ranked results based on semantic similarity.

---

## 🧠 About LSI

Latent Semantic Indexing (LSI) uses **Singular Value Decomposition (SVD)** to capture deep semantic relationships in text. It enables smarter, context-aware document search beyond exact keyword matching.

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### 2. Install Requirements

Make sure you're using **Python 3.8 or higher**.

```bash
pip install -r requirements.txt
```

### 3. Run the App

Open the Jupyter notebook and run all cells, or convert it to a `.py` script to launch directly.

```bash
jupyter notebook LSI_Project.ipynb
```

---

## 📚 NLTK Resources

The app uses `stopwords` and `wordnet`. If it's your first time running the code, make sure to download them:

```python
import nltk
nltk.download('stopwords')
nltk.download('wordnet')
```

---

## 👨‍💻 Authors

- Mohammad R. Al-Masre  
- Omar A. Al-Haymoni

---

## 📄 License

This project is licensed under the **MIT License**.
