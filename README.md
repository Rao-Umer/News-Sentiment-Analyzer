# 📰 News Sentiment Analyzer

A simple yet powerful Python-based tool that fetches online news articles, analyzes their sentiment, and generates concise summaries using Natural Language Processing (NLP).

---

## 🚀 Overview

**News Sentiment Analyzer** is a command-line application that allows users to:

* Extract content from any news article URL
* Analyze the overall sentiment (Positive, Negative, Neutral)
* Generate a short, meaningful summary of the article

This project demonstrates practical use of **web scraping**, **text processing**, and **sentiment analysis** in Python.

---

## ✨ Features

* 🔗 **URL-Based Article Extraction**
  Fetches and processes real-time news articles from the web

* 🧠 **Sentiment Analysis**
  Uses VADER (NLTK) to classify sentiment with detailed scores

* 📝 **Smart Summarization**
  Extracts key sentences based on word frequency

* ⚡ **Fast & Lightweight**
  Minimal dependencies, easy to run

* 🖥️ **Clean CLI Interface**
  Simple and user-friendly terminal interaction

---

## 🛠️ Tech Stack

* Python
* `requests` – HTTP requests
* `BeautifulSoup` – Web scraping
* `nltk` – NLP and sentiment analysis

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/news-sentiment-analyzer.git
cd news-sentiment-analyzer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install requests beautifulsoup4 nltk
```

---

## ▶️ Usage

Run the script:

```bash
python main.py
```

Then:

1. Enter a valid article URL
2. Choose number of sentences for summary
3. View sentiment and summary results

---

## 🧪 Example Output

```
===== 📰 News Sentiment Analyzer =====

🔗 Enter article URL: https://example.com/news

===== 📊 Analysis Result =====

Sentiment: Positive 😊

Detailed Scores:
neg: 0.05
neu: 0.70
pos: 0.25
compound: 0.62

📝 Summary:
[Top key sentences from the article...]
```

## ⚠️ Limitations

* Works best with standard news websites
* May include unwanted text (ads, navigation content)
* Summarization is extractive (not AI-generated)
