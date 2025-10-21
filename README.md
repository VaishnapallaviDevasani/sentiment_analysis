# Employee Sentiment Analysis – AI Internship Project

## 📄 Overview
This project analyzes employee email data to identify sentiment trends, rank employees, and detect possible flight risk using NLP and machine learning.

## 📂 Contents
- `data/test.xlsx`: Dataset provided
- `notebooks/sentiment_analysis.ipynb`: Main analysis
- `outputs/sentiment_results.xlsx`: Final sentiment scores
- `README.md`: Instructions & setup

## 🧰 Requirements
Install dependencies using:
```bash
pip install pandas numpy matplotlib seaborn textblob openpyxl scikit-learn
▶️ How to Run
Open the Jupyter notebook.

Run all cells step by step.

Sentiment results will be saved in outputs/.

📊 Methodology
Text Cleaning: Removed symbols, HTML, and extra spaces.

Sentiment Analysis: Used TextBlob for polarity.

EDA: Visualized sentiment counts and monthly trends.

Ranking: Averaged sentiment per sender.

Flight Risk: Negative trend over time.

Regression: Linear regression on monthly average sentiment.

👩‍💻 Author
Vaishnapallavi Devasani
Email: vaishnapallavidevasani@gmail.com
