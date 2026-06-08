# 🍽️ Restaurant Review Sentiment Monitor

A production-style NLP application built with **Streamlit** for real-time restaurant review sentiment analysis, live prediction monitoring, confidence tracking, data drift detection, and batch CSV/TSV scoring.

---

# Features

- Real-time restaurant review sentiment prediction
- Positive and negative sentiment classification
- Confidence score monitoring
- Batch CSV/TSV review scoring
- Interactive monitoring dashboard
- Prediction mix visualization
- Confidence trend tracking
- Input drift detection alerts
- Recent prediction logging
- Deployment-style Streamlit interface

---

# Tech Stack

## Frontend & UI
- Streamlit (Interactive Production-style UI)

## Machine Learning & NLP
- Scikit-learn (Pipeline implementation)
- TF-IDF Vectorization (Text feature extraction)
- Logistic Regression (Classification model)

## Data Processing & Visualization
- Pandas & NumPy
- Plotly & Matplotlib

---

# Project Structure

```bash
Restaurant-Review-Sentiment-Analysis/
│
├── streamlit_restaurant_monitoring_app.py   # Main Streamlit Application
├── restaurant_sentiment_pipeline.joblib     # Pre-trained NLP Pipeline
├── Reviews.csv                              # Sample Dataset
├── Restaurant_Reviews.tsv                   # Sample TSV Dataset
├── BOW & TFIDF.docx                         # Conceptual Documentation
└── README.md                                # Project Documentation
```

# ⚙️ Installation & Setup
Follow these steps to run the project locally:
- Clone Repository
```bash
     git clone [https://github.com/Sahil-Borkar-13/Restaurant-Review-Sentiment-Analysis.git](https://github.com/Sahil-Borkar-13/Restaurant-Review-Sentiment-Analysis.git)
```
- Navigate to Project Folder
```bash
     cd Restaurant-Review-Sentiment-Analysis
```
- Install Dependencies
```bash
     pip install -r requirements.txt
```
