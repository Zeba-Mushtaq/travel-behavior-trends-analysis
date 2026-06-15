# 🌍 Travel Behavior & Trends Analysis (2019–2024)

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Viz-3F4F75)](https://plotly.com/)
[![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-FF4B4B)](https://streamlit.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> A data analytics project exploring **global tourism patterns from 2019 to 2024** — covering the pre-pandemic baseline, the pandemic-era collapse, and the post-pandemic recovery in travel behavior. Built end-to-end with **Python, Pandas, Plotly, and Streamlit**.

---

## 📌 Project Overview

This project analyzes a synthetic global tourism dataset (10,000+ trip records) to uncover patterns in:

- 🧭 **Travel volume trends** across years (2019–2024)
- 🌦️ **Seasonal travel behavior** (which seasons see the most trips, and why)
- 🎯 **Purpose of travel** (Business vs Leisure/Tourism vs other categories)
- 👥 **Traveler type segmentation** (Solo, Couple, Family, Group Tours)
- 🛬 **Top origin and destination countries**
- 🌙 **Trip duration patterns** by traveler type and travel purpose
- 📉 **COVID-19 impact** — visualizing the dip in travel during 2020–2021 and the recovery curve afterward

The goal is to turn raw trip-level data into **clear, visual, and actionable insights** about how global travel behavior shifted across one of the most disruptive periods in modern tourism history.

---

## 🗂️ Dataset

**File:** `global_tourism_travel_trends-selected-columns.csv`
**Size:** 10,000 trip records
**Time Range:** 2019 – 2024

| Column | Description |
|---|---|
| `trip_id` | Unique identifier for each trip |
| `year` | Year the trip took place (2019–2024) |
| `month` | Month of travel (1–12) |
| `season` | Season label (Spring, Summer, Autumn, Winter) |
| `origin_country` | Traveler's country of origin |
| `destination_country` | Country traveled to |
| `travel_purpose` | Purpose of trip (Business, Leisure/Tourism, etc.) |
| `traveler_type` | Type of traveler (Solo, Couple, Family, Group Tour) |
| `num_travelers` | Number of travelers in the trip |
| `duration_nights` | Length of stay in nights |

> ⚠️ This is a **synthetic dataset** created for educational and portfolio purposes — it does not represent real tourism statistics.

---

## 🔍 Key Questions This Project Answers

1. How did global travel volume change year-over-year from 2019 to 2024?
2. Which seasons are the most popular for travel, and does this vary by traveler type?
3. What are the most common travel purposes, and how have they shifted post-pandemic?
4. Which countries are the top sources and destinations for travelers?
5. How does trip duration differ between Solo travelers, Couples, Families, and Group Tours?
6. Is there a visible "recovery curve" in the data after the 2020 pandemic dip?

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Pandas** — data cleaning & aggregation
- **Matplotlib / Seaborn** — static visualizations
- **Plotly** — interactive charts & choropleth maps
- **Streamlit** — interactive dashboard deployment
- **Jupyter Notebook** — exploratory data analysis (EDA)

---

## 📁 Repository Structure

```
travel-behavior-trends-analysis/
│
├── data/
│   └── global_tourism_travel_trends-selected-columns.csv
│
├── notebooks/
│   └── travel_trends_eda.ipynb        # Full exploratory analysis
│
├── app/
│   └── streamlit_app.py               # Interactive dashboard
│
├── images/
│   └── (charts, dashboard screenshots, GIFs)
│
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 🚀 How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/Zeba-Mushtaq/travel-behavior-trends-analysis.git
cd travel-behavior-trends-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter notebook
```bash
jupyter notebook notebooks/travel_trends_eda.ipynb
```

### 4. Launch the interactive dashboard
```bash
streamlit run app/streamlit_app.py
```

---

## 📊 Sample Visualizations

*(Add screenshots/GIFs of your charts and dashboard here once generated)*

- Yearly travel volume trend (2019–2024)
- Seasonal distribution heatmap
- Travel purpose breakdown by year
- Top 10 destination countries
- Trip duration by traveler type
- COVID-19 impact timeline

---

## 📈 Key Insights

*(To be updated after analysis is complete)*

- ...
- ...
- ...

---

## 🔮 Future Work

- Time-series forecasting of travel demand using Prophet/ARIMA
- Clustering travelers into behavioral segments using K-Means
- Geographic flow mapping of origin → destination routes
- Sentiment analysis if review/feedback data is added

---

## 👩‍💻 Author

**Zeba Mushtaq**
Data Analyst | AI/ML Enthusiast | Building in Public

- 🌐 [Portfolio](https://zeba-portfolio.vercel.app)
- 💻 [GitHub](https://github.com/Zeba-Mushtaq)
- ✍️ [Medium](https://medium.com/@zebamushtaq) | [Hashnode](https://zebabuilds.hashnode.dev) | [DEV.to](https://dev.to/zebamushtaq)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
