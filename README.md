# ✈️ British Airways Customer Feedback & Booking Analysis
Customer Behaviour Prediction

Analyzing **customer reviews and booking data** for British Airways to understand sentiment, key trends, and predict booking completion.

---

## 📌 Project Overview
- **🗂 Data Collection & Cleaning**  
  Scraped reviews from [Skytrax](https://www.airlinequality.com/airline-reviews/british-airways), cleaned text, ratings, and dates.
  
- **📊 Exploratory Data Analysis (EDA)**  
  Analyzed rating distribution, top reviewer countries, trends over time, word frequency, and n-grams.  
  Performed **sentiment analysis** with **TextBlob**.
  Topic modeling using **LDA** & **NMF**.

- **💼 Customer Booking Analysis**  
  Explored bookings by sales channel, trip type, length of stay, flight day, and origin.  
  Filtered outliers and prepared clean dataset for modeling.

- **🤖 Predictive Modeling**  
  Predicted booking completion using **Random Forest**.  
  Preprocessed with **One-Hot Encoding** & **Standard Scaling**.  
  Evaluated using **accuracy, precision, recall, F1-score**, and visualized **feature importance**.

---

## 🌟 Key Insights
- Positive reviews frequently highlight **friendly and efficient cabin crew**.  
- **Monday** is the most preferred flight day; **Saturday** the least.  
- Round trips are most common; **internet bookings dominate**.  
- Balancing dataset improved model performance.

---

## 🛠 Tools & Libraries
![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)  
![Pandas](https://img.shields.io/badge/Pandas-1.5-green?logo=pandas)  
![NumPy](https://img.shields.io/badge/NumPy-1.25-orange?logo=numpy)  
![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.2-purple?logo=scikit-learn)  
![NLTK](https://img.shields.io/badge/NLTK-3.8-red?logo=nltk)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-blue?logo=matplotlib)  
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-purple?logo=seaborn)  
![Plotly](https://img.shields.io/badge/Plotly-5.15-orange?logo=plotly)  
![Yellowbrick](https://img.shields.io/badge/Yellowbrick-1.5-green?logo=python)  
![WordCloud](https://img.shields.io/badge/WordCloud-1.9-blue?logo=python)  

---

## 🔗 References
- Airline review source: [Skytrax](https://www.airlinequality.com/airline-reviews/british-airways)
