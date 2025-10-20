## 🏥 Healthcare Hospital Quality Analytics Dashboard

A real-world healthcare analytics project using CMS hospital data. Includes data cleaning in Python and an interactive Tableau dashboard showing hospital performance, sepsis care quality, and state-wise health insights.

---
## 📸 Dashboard Preview

Interactive Tableau dashboard visualizing hospital quality metrics across the U.S.

---
## 🎯 Project Overview

This project analyzes U.S. hospital performance using official CMS (Centers for Medicare & Medicaid Services) datasets.
It focuses on key healthcare quality indicators such as:

Sepsis Care Compliance

Staff Vaccination Rates

Emergency Department Performance

State & Ownership Comparison

The goal is to identify top-performing hospitals, observe state disparities, and highlight areas for care improvement, using Python for cleaning and Tableau for visualization.

---
## 🗂 Project Structure
Healthcare-Hospital-Quality-Analytics/

├─ Tableau/

│  ├─ healthcare-hospital-quality-dashboard.twb   # Tableau Workbook

│  ├─ cms_timely_wide_facility_kpis.csv          # Final Tableau dataset

│  └─ Dashboard SS.png                           # Dashboard screenshot

├─ Data_Cleaning_and_Merge.ipynb                 # Jupyter notebook (Python)

└─ README.md

---
## 🧾 Data Sources (Public | CMS Healthcare Data)
Dataset	Source Link
Hospital General Information	https://data.cms.gov/provider-data/dataset/xubh-q36u

Timely & Effective Care – Hospital	https://data.cms.gov/provider-data/dataset/yv7e-xc69

📌 Note: Raw datasets are not uploaded due to GitHub size limits. Download from the links above if reproducing the project.

🧼 Data Preparation (Jupyter Notebook)

Data cleaning and merging conducted in Data_Cleaning_and_Merge.ipynb using Python (Pandas):

Removed "Not Available" and null values

Selected key metrics (Sepsis, Vaccination, ED Wait Time)

Merged hospital details using Facility ID

Exported final dataset for Tableau dashboard

---
### 📊 Dashboard Features (Built in Tableau)
Feature	Description:

🏥 Top Hospitals Ranking	Displays best-performing hospitals by KPI

🗺 U.S. State Map	Visualizes statewide hospital quality performance

🎚 Interactive Filters	Filter by State & Hospital Ownership

💬 Smart Tooltips	Shows hospital rating & ownership on hover

---

### 💡 Key Insights

Some states consistently outperform others in Sepsis Care (%)

Non-profit hospitals tend to have higher vaccination rates

High ED volume states show greater variation in care quality

## 🚀 How to Run the Dashboard Locally
Step 1 – Download Data

Download CMS datasets from links and place them in a data/ folder (if reproducing analysis).

Step 2 – Run Python Notebook
Data_Cleaning_and_Merge.ipynb

Step 3 – Open Tableau Dashboard

Open: Tableau/healthcare-hospital-quality-dashboard.twb

---

## 📬 Connect with Me

Swapnil Yadav
🔗 LinkedIn: https://www.linkedin.com/in/swapnil-yadav-dataanalyst/
