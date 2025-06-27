# News-Summarizer

A Python-based GUI application that automatically summarizes news articles from URLs, extracts key details like title, author, publication date, and performs sentiment analysis.

---

## 📈 Features

* ✍️ Extracts **Title**, **Authors**, **Published Date** from any news article.
* ✅ Generates an **automatic summary** of the article using NLP.
* 📊 Performs **Sentiment Analysis** (Positive / Negative / Neutral).
* 📃 Simple and lightweight **Tkinter-based GUI**.
* 🌟 Built using Python with minimal dependencies.

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/shakeel-33-code/news-summarizer.git

```

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
venv\Scripts\activate  # On Windows
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python "main.py"
```

---

## 📚 Dependencies

Listed in `requirements.txt`, includes:

* `nltk`
* `textblob`
* `newspaper3k`
* `lxml_html_clean`

### 🔄 NLTK Setup

The app auto-downloads required resources on first run:

```python
import nltk
nltk.download('punkt')
nltk.download('punkt_tab')
```







---

## 🏆 Built With

* [Python](https://www.python.org/)
* [Tkinter](https://docs.python.org/3/library/tkinter.html)
* [Newspaper3k](https://newspaper.readthedocs.io/)
* [TextBlob](https://textblob.readthedocs.io/)
* [NLTK](https://www.nltk.org/)

---

## 📄 License

This project is for educational use. Feel free to fork and experiment for learning or demo purposes.



 


---

## 🛋️ .gitignore

Ensure your `.gitignore` excludes:

```
venv/
__pycache__/
*.pyc
nltk_data/
.vscode/
```

---

For any help or issues, feel free to open an issue or PR on the repo!
