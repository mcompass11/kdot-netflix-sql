# 🎬 Netflix SQL Analysis

SQL-first exploration of the Netflix catalog: cleaning, normalization, and insight queries
using **SQLite + Pandas**. 
This project demonstrates practical SQL skills -- GROUP BY, filtering, CTEs, window
functions -- plus lightweight visuals in **Matplotlib/Seaborn**

<a href="exports/kdot_netflix_sql.pdf" target="_blank">View Full Analysis (PDF)</a>

## 📌 Overview
This project analyzes Netflix’s public catalog dataset, uncovering insights about titles,
genres, ratings, release trends, and country contributions.
The analysis workflow:
1. **Load & clean** raw Netflix CSV data
2. **Store * query** with SQLite
3. **Extract insights** via SQL and Python (Pandas)
4. **Visualize** results
---

## ✨ Features So Far
- Cleaned & normalized messy CSV data for SQL analysis
- SQL queries for trends over time, genre popularity, and content ratings
- Common Table Expressions (CTEs) for modular query building
- Ranking content by country output
- Bar chart & time series visualizations
---
## 🔑 Key Insights
- 📅 Content Growth: Massive spike in titles between 2016–2020
- 🎭 Genre Leaders: Documentaries & Stand-Up Comedy dominate
- 🌍 Top Producers: USA, India, and the UK lead in title volume
- 🔞 Ratings: TV-MA is the most common rating
---

## 🛠️ Tech Stack
- Python 3
- Pandas - Data handling & preprocessing
- SQLite - Query execution &data storage
- Matplotlib/Seaborn - Visualization
- Jupyter Notebook - Interactive analysis

## 🚀 Run It

1. Clone this repo:
    ```bash
    git clone https://github.com/mcompass11/kdot-netflix-sql.git
    cd kdot-netflix-sql

2. Install requirements:
    ```bash
    pip install -r requirements.txt

3. Launch the notebook:
    ```bash
    jupyter notebook