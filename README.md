# 🌍 COVID-19 Data Analysis using Pandas, NumPy & Matplotlib

This project is a simple data analysis and visualization of COVID-19 global data. It uses **Python**, **Pandas**, **NumPy**, and **Matplotlib** to process and visualize the pandemic's spread over time.

---

## 📁 Project Structure

```
covid-data-analysis/
│
├── data/
│   └── time-series-19-covid-combined.csv.zip  # Raw dataset
├── covid_analysis.ipynb                       # Jupyter Notebook containing the full analysis
└── README.md                                  # Project documentation
```

---

## 📌 Features

- Cleans and fills missing data using `SimpleImputer`.
- Renames and drops unnecessary columns.
- Aggregates global and country-level COVID-19 statistics.
- Calculates `Active` cases using:  
  `Active = Confirmed - Recovered - Deaths`
- Visualizes:
  - World-level trends over time.
  - Country-wise trends using scatter plots.

---

## 🛠️ Tech Stack

- Python 3.x
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [scikit-learn (for SimpleImputer)](https://scikit-learn.org/)
- Jupyter Notebook

---

### 🗺️ Country-wise Trend Plot

Each country is plotted using the same structure:
- Blue: Confirmed
- Green: Recovered
- Red: Deaths
- Orange: Active

---
Made with ❤️ by Harsh Singh.


