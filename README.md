# 📈 SignalToSentiment

**AI-powered emotional trend tracker for Reddit**  
A lightweight Python tool that scans Reddit comments, classifies emotional sentiment, and visualizes mood trends over time. Built for creators, strategists, and researchers who want to understand the emotional energy behind online conversations.

---

## 🧠 Why This Exists

Viral content isn't driven by keywords alone—**emotion** fuels engagement.  
But most tools only track volume or mentions, not emotional shifts.  
**SignalToSentiment** fills that gap by showing how online communities *feel* over time.

---

## 🔩 Features

- ✅ Scrape Reddit comments from any thread or subreddit
- ✅ Classify emotional tone with a sentiment model
- ✅ Output structured data to CSV
- ✅ Visualize sentiment trends in line charts
- ⏳ Future: GPT-powered summaries of emotional shifts

---

## 📁 Project Structure

```
signal-to-sentiment/
├── data/
│   └── reddit_sentiment.csv       ← Sample data (comment + sentiment)
├── scripts/
│   ├── sentiment_classifier.py    ← Classifies tone
│   ├── scrape_reddit.py           ← Reddit scraper (add your keys)
│   └── trend_grapher.py           ← Visual trend chart
├── notebooks/
│   └── SignalToSentiment_Demo.ipynb ← Jupyter walkthrough
├── requirements.txt               ← Python dependencies
└── README.md
```

---

## 🚀 How To Run

1. **Install dependencies**

```bash
pip install -r requirements.txt
```

2. **Scrape Reddit (or use sample CSV)**  
Add your own logic to `scrape_reddit.py` or manually populate `reddit_sentiment.csv`.

3. **Run sentiment classifier**

```bash
python scripts/sentiment_classifier.py
```

4. **Graph the results**

```bash
python scripts/trend_grapher.py
```

Or use the notebook for an interactive walkthrough.

---

## 📊 Sample Output

_Example:_

```
comment,sentiment
"I love this!",positive
"This is awful",negative
...
```

---

## 🧰 Future Ideas

- Twitter/X scraping  
- GPT-generated trend reports  
- Alert system for emotional spikes  
- Integration with TikTok or YouTube planning

---

## 👤 Created By

**Daniel** — AI systems builder, prompt engineer, and emotional signal tracker.  
This project is part of a public portfolio demonstrating practical AI integration.

---

> No license applied. Personal use and learning only unless otherwise stated.
