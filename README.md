# COVID-19 Global Data Visualization Project

![Dashboard Preview](images/tableau_dashboard.png)

## 📌 Project Overview

This project analyzes global COVID-19 trends using data visualization and exploratory data analysis techniques. The analysis focuses on confirmed cases, deaths, mortality rates, and vaccination coverage across different WHO regions and countries.

The project combines Python-based analysis with Tableau dashboards to present meaningful insights from real-world healthcare data.

---

## 🎯 Objectives

- Analyze global COVID-19 case and death trends
- Compare mortality rates across WHO regions
- Explore vaccination coverage and distribution
- Build interactive and static visualizations for insight generation
- Present findings through a Tableau dashboard and analytical report

---

## 🛠️ Tools & Technologies

### Programming & Analysis
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn
- Plotly Express
- Tableau

### Development Environment
- Jupyter Notebook

---

## 📂 Project Structure

```text
data-visualization-project/
│── README.md
│── notebook.ipynb
│── requirements.txt
│── covid_analysis_report.pdf
│
├── data/
│   ├── WHO-COVID-19-global-table-data.csv
│   └── vaccination-data.csv
│
├── images/
│   ├── cumulative_total_cases_deaths.png
│   ├── deaths_last_7_days_per_100k.png
│   ├── vaccination_coverage.png
│   └── tableau_dashboard.png
│
└── tableau/
    └── CW-DataVisualization.twb
```

---

## 📊 Key Visualizations

### Cumulative Total Cases and Deaths by WHO Region

![Cases and Deaths](images/Cumulative-Total-Cases-and-Deaths-by-WHO-Region.png)

---

### Deaths in Last 7 Days per 100k Population

![Deaths per 100k](images/Deaths-in-last-7-days-per-100k-population.png)

---

### Vaccination Coverage Analysis

![Vaccination Coverage](images/Vaccination-Coverage.png)

---

## 📈 Key Insights

- Some WHO regions experienced significantly higher mortality rates despite lower overall case counts.
- Vaccination coverage showed a visible relationship with reduced recent death rates in several countries.
- Regional disparities highlighted differences in healthcare infrastructure, reporting quality, and pandemic response strategies.
- Data visualization provided clearer understanding of global pandemic progression and recovery trends.

---

## 📑 Tableau Dashboard

The project also includes an interactive Tableau dashboard for visual exploration of COVID-19 trends and vaccination statistics.

Dashboard file:
```text
tableau/CW-DataVisualization.twb
```

---

## ⚙️ Installation & Setup

Clone the repository:

```bash
git clone https://github.com/AmmarKafeel47/data-visualization-project.git
```

Navigate to the project directory:

```bash
cd data-visualization-project
```

Install required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📄 Report

A detailed analytical report is included in the repository:

```text
covid_analysis_report.pdf
```

---

## 📚 Dataset Source

- WHO COVID-19 Global Data
- Vaccination datasets used for educational and analytical purposes

---

## 👨‍💻 Author

### Ammar Kafeel

- MSc Data Science — University of Roehampton
- Data Visualization & Analytics Enthusiast
- Interested in Data Science, Machine Learning, and AI Engineering

GitHub:
https://github.com/AmmarKafeel47

---

## ⭐ Future Improvements

- Add interactive Plotly dashboards
- Deploy dashboard using Streamlit
- Include time-series forecasting models
- Integrate automated data updates
- Expand regional comparative analysis
