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
- Run Streamlit App
```bash
     streamlit run streamlit_restaurant_monitoring_app.py
```
- Machine Learning Workflow
```bash
     [Text Input/CSV] ➔ [Text Preprocessing] ➔ [TF-IDF Vectorization] ➔ [Logistic Regression] ➔ [Confidence & Drift Metrics] ➔ [Dashboard UI]
```


- Text Preprocessing & Clean-up: Standardizes raw text by removing noise and irrelevant characters.

- TF-IDF Vectorization: Converts textual data into numerical features based on term frequency.

- Sentiment Classification: Uses a calibrated Logistic Regression model to classify sentiment.

- Confidence Estimation: Extracts prediction probabilities for the predicted label.

- Monitoring Signal Generation: Signals metrics to the live dashboard for performance tracking.

# 🔮 Future Roadmap
- SHAP/LIME Integration: Add model explainability to see which words triggered the sentiment.

- FastAPI Backend: Decouple the ML pipeline into a high-performance REST API.

- Database Logging: Store live predictions in a PostgreSQL or MongoDB database for historical analysis.

- Dockerization: Containerize the application for seamless cloud deployment.

- Advanced Drift Detection: Implement Kolmogorov-Smirnov tests for statistical drift tracking. 

# 👤 Author
- **Sahil Borkar**
  - GitHub Profile: Sahil-Borkar-13

# Areas of Interest
- Natural Language Processing (NLP)

- Machine Learning Operations (MLOps) & Deployment

- Interactive Data Dashboards

- Data Visualization
