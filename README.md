🎓 Fake Review Detection in the Education Sector using Machine Learning and NLP
📌 Overview

This project presents a Machine Learning and Natural Language Processing (NLP) based system for detecting deceptive (fake) reviews in educational institutions. The project combines data collection, text preprocessing, machine learning classification, sentiment analysis, and Power BI visualization to generate meaningful insights from online educational reviews.

The objective is to help students, educational institutions, and researchers identify potentially misleading reviews and improve the reliability of online review platforms.

🚀 Project Objectives
Detect fake educational reviews using Machine Learning.
Perform sentiment analysis on student reviews.
Build an interactive Power BI dashboard for visualization.
Demonstrate a complete end-to-end data science workflow.
📂 Project Workflow
Data Collection
        │
        ▼
Web Scraping
(Collegedunia, Career360, Google Reviews)
        │
        ▼
Data Cleaning & NLP Preprocessing
        │
        ▼
TF-IDF Feature Extraction
        │
        ▼
Logistic Regression Model
        │
        ▼
Fake Review Prediction
        │
        ▼
Sentiment Analysis (VADER)
        │
        ▼
Power BI Dashboard
📊 Dataset

The project uses two types of datasets.

Training Dataset
Fake Reviews Dataset (Kaggle)
Yelp Fake Reviews
HuggingFace Fake Review Dataset

These datasets were filtered using education-related keywords to create an education-focused training dataset.

Real Educational Reviews

Educational reviews were collected through web scraping from publicly available sources including:

Collegedunia
Career360
Google Reviews
🛠 Technologies Used
Programming
Python
Machine Learning
Scikit-learn
Logistic Regression
TF-IDF Vectorizer
Natural Language Processing
NLTK
VADER Sentiment Analyzer
Data Processing
Pandas
NumPy
Visualization
Microsoft Power BI
📈 Model Performance
Metric	Value
Accuracy	90.84%
Precision	91%
Recall	91%
F1 Score	91%
📊 Dashboard Insights

The Power BI dashboard provides interactive visualizations including:

Total Reviews
Fake vs Genuine Reviews
Sentiment Distribution

epository Structure
├── Fake reviews.pbix
├── Fake-Review-Model.ipynb
├── Final Project Report.pdf
├── fake_review_detection_education_project.pptx
├── education_reviews_analysis_clean.csv
├── institutes.csv
├── fake reviews dataset.csv
├── README.md
📌 Results
Total Reviews Analysed: 356
Fake Reviews Detected: 19
Genuine Reviews: 337
Average Rating: 3.31
Model Accuracy: 90.84%
📖 Project Report

The repository includes:

Complete MSc (Data Science) Project Report
PowerPoint Presentation
Jupyter Notebook
Power BI Dashboard
Processed Dataset
⚠️ Disclaimer

This project was developed solely for academic and research purposes as part of the Master of Science (Data Science) program.

Some datasets were obtained from publicly available sources, while educational reviews were collected from publicly accessible websites for research purposes only. The generated predictions should be treated as analytical insights rather than definitive judgments regarding review authenticity.

👨‍💻 Author

Tushar Goswami

Master of Science (Data Science)

Chandigarh University
Average Ratings
Fake Reviews by Institution
Rating vs Sentiment Analysis
