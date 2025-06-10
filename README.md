# 📘 BSU Machine Learning Lectures

This repository contains two applied machine learning notebooks developed for students at Belarusian State University (BSU). The focus is on solving **real-world problems** with as little theory as possible — using real data and production-ready tools.

---

## 📂 Contents

### 🔹 Recommendation System
Notebook: `Recommendation_BSU.ipynb`  
- Item-based recommender system using Last.fm listening data  
- Simple, interpretable metrics for quality: Hit Rate, MAP, NDCG  
- Data in `archive/`:
  - `lastfm_user_scrobbles.csv`
  - `lastfm_artist_list.csv`

### 🔹 Stock Forecasting
Notebook: `BSE_TimeSeries_stock_forecasting.ipynb`  
- Time series forecasting based on real stock data  
- Concepts: rate-based differencing, stationarity checks, trend modeling  
- Dataset: `data_example.xlsx`

---

## Usage

1. Open notebooks in JupyterLab, VSCode, or any Python 3.x environment
2. Required packages (install with `pip`):
   - `pandas`
   - `numpy`
   - `scikit-learn`
   - `statsmodels`
   - `matplotlib`, `seaborn` (for plotting)
3. All datasets are included — no need for database connections

---

## Evaluation Metrics in Recommenders

Offline metrics like:
- **Mean Average Precision (MAP)** — how many top items are relevant
- **Normalized Discounted Cumulative Gain (NDCG)** — takes item position into account
- **Hit Rate** — measures if the relevant item was recommended

>  However, real validation of recommender systems should be done via **A/B testing** — offline metrics alone can be misleading in production.

---

## About the Author

**Kanstantsin Bichun**  
Senior Data Scientist with 5+ years experience in financial modeling, treasury optimization, and machine learning in banking (Alfa-bank Belarus).
Founder and CEO of Scroogeer investment AI bot with best deals notifications.
Founder and CEO of Zarada.by banking products development.
Lecturer in applied ML at BSU (Faculty of Applied Mathematics and Computer Science), focused on real use cases instead of abstract theory.  

📺 [Lecture recording (YouTube, in Russian)](https://www.youtube.com/watch?v=SY7Kh658Bvk)  
🔗 LinkedIn: https://www.linkedin.com/in/constantine-bichun/ 
