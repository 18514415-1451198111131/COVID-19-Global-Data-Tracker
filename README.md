# 📊 COVID-19 Data Analysis Projects

## Overview

This repository contains two related projects focused on analyzing global COVID-19 data:

1. **COVID-19 Data Analysis Project**
2. **COVID-19 Data Analysis Project (Interactive)**

Both projects aim to provide insights into the spread, trends, and impact of COVID-19 using real-world data. The interactive version enhances user experience with dynamic visualizations and input controls.

---

## 1. 📈 COVID-19 Data Analysis Project

### Description

This is a static, script-based data analysis project using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**. It processes historical COVID-19 data to uncover patterns and trends.

### Features

* Data cleaning and preprocessing
* Time series analysis of cases, deaths, and recoveries
* Country-wise comparisons
* Peak case detection
* Correlation between variables (e.g., testing vs. confirmed cases)
* Visualizations (line plots, bar charts, heatmaps)

### Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

### How to Run

1. Clone the repository.
2. Open `covid_data_analysis.ipynb` in Jupyter Notebook.
3. Run each cell sequentially.

---

## 2. 💡 COVID-19 Data Analysis Project (Interactive)

### Description

An enhanced interactive dashboard built using **Streamlit** (or **Dash**, depending on your implementation). This version allows users to filter data by country, date range, and view real-time visualizations interactively.

### Features

* Country and date range selectors using dropdown and slider widgets
* Real-time data filtering and updating of charts
* Interactive charts (line, bar, pie, and maps if applicable)
* Summary statistics (totals, averages, growth rates)
* Optional data export

### Technologies

* Python
* Pandas
* Streamlit or Dash
* Plotly / Altair / Matplotlib (for interactive visualizations)

### How to Run

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
2. Run the app:

   ```bash
   streamlit run covid_dashboard.py
   ```

   or (for Dash)

   ```bash
   python app.py
   ```

### Optional Stretch Features

* User-uploaded data for localized analysis
* Map-based visualization of outbreaks
* Forecasting using basic machine learning models

---

## 📁 Project Structure

```
📆 covid19-analysis/
├── data/                   # Raw and cleaned datasets
├── notebooks/              # Jupyter analysis notebooks
│   └── covid_data_analysis.ipynb
├── interactive/            # Interactive dashboard app
│   └── covid_dashboard.py or app.py
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

---

## 📌 Sources

* [Johns Hopkins University CSSE COVID-19 Dataset](https://github.com/CSSEGISandData/COVID-19)
* [Our World in Data](https://ourworldindata.org/coronavirus)

---

## 📬 Contact

**Author:** Thendo Netshandama
📧 Email: [tnetshandama90@gmail.com](mailto:tnetshandama90@gmail.com)
🌍 South Africa
