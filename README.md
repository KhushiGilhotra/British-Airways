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
- **Python 3.12**
- **Data Handling**: `pandas`, `numpy`
- **Web Scraping**: `requests`, `BeautifulSoup`
- **Data Cleaning & NLP**: `nltk`, `textblob`, `sklearn`
- **Visualization**: `matplotlib`, `seaborn`, `plotly`, `wordcloud`
- **Machine Learning**: `sklearn` (RandomForest, StandardScaler, OneHotEncoder, train_test_split)
- **Model Evaluation**: `yellowbrick` (ConfusionMatrix), `sklearn.metrics`

---

## 🔗 References
- Airline review source: [Skytrax](https://www.airlinequality.com/airline-reviews/british-airways)
