# ✈️ Airline Revenue & Occupancy Analysis (SQL + Python)

![Project Header](https://via.placeholder.com/1000x300?text=Airline+Data+Analysis+Project) 
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
├── Airline_Analysis.ipynb        # Full Jupyter/Colab Analysis
├── Airlines_Widescreen.pptx      # Executive Presentation
├── travel.sqlite                 # Database file (Raw Data)
├── README.md                     # Project Documentation
└── images/                       # Visualizations and Charts
