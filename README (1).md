# 📊 Netflix Dataset — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

> An exploratory data analysis (EDA) project on Netflix content — uncovering trends in content types, genres, countries, ratings, and top directors using Python.

---

## Overview

With the rapid growth of streaming platforms, understanding content distribution, trends, and viewer preferences has become increasingly important. This project dives into Netflix's catalog to extract meaningful patterns using data cleaning, preprocessing, and visualization techniques.

---

## Dataset

| Property     | Value                          |
|--------------|-------------------------------|
| Source       | [Kaggle](https://www.kaggle.com/) |
| File         | `netflix1.csv`                |
| Rows         | 8,807                         |
| Columns      | 12                            |

**Columns include:** `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## Objectives

- ✅ Perform data cleaning and preprocessing
- ✅ Explore the dataset using descriptive statistics
- ✅ Visualize key trends and patterns
- ✅ Derive actionable insights from the data

---

## Tech Stack

| Tool              | Purpose                        |
|-------------------|-------------------------------|
| Python 🐍         | Core programming language      |
| Pandas            | Data manipulation & analysis   |
| NumPy             | Numerical operations           |
| Matplotlib        | Data visualization             |
| Seaborn           | Statistical visualizations     |
| Jupyter Notebook  | Interactive development        |

---

## Project Structure

```
netflix-eda/
│
├── Netflix_(1).ipynb     # Main analysis notebook
├── netflix1.csv          # Dataset (from Kaggle)
└── README.md             # Project documentation
```

---

## Key Analysis Steps

1. **Data Loading** — Reading the CSV and previewing the first rows
2. **Data Inspection** — Checking shape, data types, duplicates, and null values
3. **Data Cleaning**
   - Converting `date_added` to datetime format
   - Cleaning the `duration` column (removing `min`, `Season`, `Seasons` text)
4. **Exploratory Analysis**
   - Distribution of Movies vs. TV Shows
   - Top 10 countries by content volume
   - Rating distribution
   - Top 10 directors by number of titles

---

## Visualizations

| Chart                         | Description                                      |
|-------------------------------|--------------------------------------------------|
| 🎬 Movies vs. TV Shows        | Bar chart comparing content type distribution    |
| 🌍 Top 10 Countries           | Countries contributing the most content          |
| ⭐ Ratings Distribution        | Frequency of each content rating (TV-MA, PG, etc.) |
| 🎥 Top Directors              | Most frequent directors on the platform          |

---

## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/netflix-eda.git
   cd netflix-eda
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Netflix.ipynb
   ```

4. Make sure `netflix1.csv` is in the same directory as the notebook.

---

## Insights

- The dataset contains **8,807 titles** across Movies and TV Shows.
- The **United States** leads in content production, followed by other major markets.
- Content ratings reveal a strong skew toward mature audiences (e.g., **TV-MA**).
- A small group of directors dominate Netflix's catalog in terms of title count.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

*This project was built as part of a data analysis learning journey. Feel free to fork, star ⭐, and contribute!*
