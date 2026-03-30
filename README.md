# ✈️ Airlines Strategic Revenue & Fleet Efficiency Modeling (SQL + Python)


## 📌 Business Problem
The airline industry is facing a profit squeeze due to strict regulations, rising fuel prices, and a tight labor market. The goal of this project is to identify how the airline can **maximize profitability** by optimizing **Occupancy Rates** rather than just increasing ticket prices.

## 🎯 Project Objectives
* **Increase Occupancy Rate:** Identify underperforming flights and fill empty seats.
* **Pricing Optimization:** Evaluate how different fare classes (Business vs. Economy) impact total revenue.
* **Strategic Growth:** Quantify the financial impact of a **10% increase in occupancy** across the entire fleet.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Database:** SQLite (`travel.sqlite`)
* **Tools:** Jupyter Lab / Google Colab, PowerPoint (Automated reporting)

## 📊 Key Insights & Findings

### 1. Fleet Capacity
We identified 6 major aircraft models with over 100 seats, with the **Boeing 773** leading the fleet at **402 seats**.

### 2. The "Workhorse" vs. The "Laggard"
* **SU9 (Sukhoi Superjet):** Generated the highest total revenue (**5.1B**) despite low average ticket prices. It is the fleet's primary revenue driver.
* **CN1:** Identified as a "laggard" with low revenue and only Economy offerings. Recommended for a facility or pricing overhaul.

### 3. The 10% Revenue "Lift"
If the airline increases occupancy by just 10%, the projected annual growth is:
* **SU9:** +511,710,437
* **763:** +436,957,356
* **773:** +343,120,549



## 📂 Repository Structure
```text
├── Airline_Analysis.ipynb        # Full Colab Analysis
├── Airlines_Widescreen.pptx      # Executive Presentation
├── README.md                     # Project Documentation
└── images/                       # Visualizations and Charts
```
## 📊 Dataset Source
The data used in this analysis is the **Airline Data Analysis** dataset from Kaggle.
* **Source:** [Kaggle - Airline Data Analysis](https://www.kaggle.com/datasets/fiazbhk/airline-data-analysis)
* **Format:** SQLite Database (`travel.sqlite`)

## 🚀 How to Run

1. **Clone this repository:**
```
git clone https://github.com/anisahmed01/airline-revenue-and-occupancy-analysis
```

2. **Ensure you have sqlite3 and pandas installed.**

3. **Open Airline_Analysis.ipynb in Jupyter Lab or Google Colab.**

4. **If using Colab, upload the travel.sqlite file to the sidebar to establish a connection.**



### Author: Anis Ahmed
```
Website: anisahmed.in
```

## 📊 Dashboard Preview

<p align="center">
  <img src="https://raw.githubusercontent.com/anisahmed01/airline-revenue-and-occupancy-analysis/main/images/Screenshot%202026-03-28%20185330.png" alt="Dashboard Preview" width="100%"/>
</p>
