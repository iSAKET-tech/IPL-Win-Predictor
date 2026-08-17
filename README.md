# 🏏 IPL Win Predictor

An interactive Machine Learning web application built with Python and Streamlit that predicts the win probability of an IPL team during a second-innings run-chase based on match metrics.

---

## 📌 Project Overview

The **IPL Win Predictor** uses machine learning algorithms trained on historical Indian Premier League (IPL) match data to calculate the real-time winning percentage for both the batting and bowling teams.

### Key Features
* **Interactive UI:** Built using Streamlit with custom layout.
* **Real-time Probability:** Dynamic winning probability calculations based on current match conditions.
* **Comprehensive Metrics:** Factors in teams, venue, target score, current runs, overs completed, and wickets lost.

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python
* **Machine Learning:** Scikit-learn, Pandas, NumPy
* **Serialization:** Pickle 
* **Web Framework:** Streamlit
* **Styling:** Custom CSS (Glassmorphism & Blurred Background)

---

## 📂 Project Structure

```text
├── Analysis.ipynb         # Model training & EDA Jupyter Notebooks
├── delivery.csv
├── matches.csv            
├── app.py                 # Streamlit web application
├── pipe.pkl               # Trained ML pipeline / serialized model
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
