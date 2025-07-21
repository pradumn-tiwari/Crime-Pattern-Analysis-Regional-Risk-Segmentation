# 🛡️ Crime Data Clustering & Risk Zone Analysis (India)

This project aims to analyze crime trends across Indian states and union territories (UTs), identify high-risk regions, and explore correlations between crime types, literacy rates, and geography using SQL and unsupervised machine learning.

---

## 📁 Project Overview

- **Data Source:** Collected from multiple public websites and government crime repositories
- **Scope:** State/UT-level crime records across multiple years
- **Techniques Used:** SQL, Clustering (Unsupervised ML), EDA, Feature Engineering

---

## 🎯 Key Objectives

- Collect and clean state- and district-level crime data from diverse sources
- Analyze literacy rates in relation to total crimes across India
- Perform multi-dimensional comparisons:
  - Literacy Rate vs. Total Crimes
  - Type of Crime by State vs. Literacy Rate
  - Year-over-Year Total Crime Rate
  - Area vs. Overall Crime Incidence
- Use SQL queries to:
  - Identify districts with high recurrence of crimes over ≥3 years
  - Return corresponding state, district, year, and murder count in descending order
- Apply unsupervised learning (clustering) to segment districts into:
  - **Sensitive Areas**
  - **Moderate Areas**
  - **Peaceful Areas**

---

## 📊 Methodology

### 1. **Data Collection & Preparation**
- Gathered data from crime reporting portals, national databases, and open datasets
- Cleaned and structured using Python (Pandas) and Excel

### 2. **SQL-Based Analysis**
- Extracted high-crime patterns with conditional filtering
- Joined and grouped records to rank districts by frequency and severity

### 3. **Unsupervised Machine Learning**
- Applied clustering techniques (e.g., K-Means)
- Segmented districts into zones by analyzing multiple crime and literacy dimensions
- Created separate dataframes for each cluster for focused analysis

---

## 🛠️ Technologies Used

- **Languages:** Python, SQL
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Requests, BeautifulSoup, Selenium
- **Tools:** MS Excel, Jupyter Notebook

---

## 📈 Outputs & Insights

- Visualizations showing literacy vs. crime patterns by region
- SQL-generated tables highlighting chronically affected districts
- Clustered dataframes for better interpretation and targeted analysis
- Year-on-year heatmaps to reveal rising/falling crime trends

---

