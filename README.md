# 📊 Analyzing the Impact of NPAs on Bank Growth & Efficiency: A Comparative Study of Public vs Private Sector Banks

This project explores how **Non-Performing Assets (NPAs)** impact the profitability, efficiency, and financial health of Indian public and private sector banks. It is developed using **Python (Jupyter Notebook)** for analysis and **Power BI** for interactive visualization.

## 📁 Project Structure

- `PSU_Banks_Data.xlsx` - Financial dataset for 10 public sector banks
- `Private_Banks_Data.xlsx` - Financial dataset for 10 private sector banks
- `NPA_Impact_Analysis.ipynb` - Jupyter notebook with all data analysis and visualizations
- `PowerBI_Dashboard.pbix` - Dashboard (optional) showing graphical insights
- `README.md` - Project documentation

---

## 🎯 Objective

To understand how **Gross NPA %**, **Operating Efficiency Ratio (OER)**, and other financial indicators like **ROA**, **ROE**, **NIM**, etc., affect the **Net Profit Margin (NPM)** and growth of Indian banks.

---

## 📌 Key Features

- Comparative analysis between **Public and Private Sector Banks**
- Correlation and regression plots (using Seaborn & Matplotlib)
- Visualizations of:
  - Gross NPA % vs Net Profit Margin (NPM)
  - OER vs NPM
  - Category-wise bar charts for comparison
- Bank categorization using `Bank Type` feature
- Cleaned, structured dataset used for reproducible insights

---

## 🧪 Dataset Overview

The datasets contain the following financial indicators for 10 PSU banks and 10 Private banks:

- Gross NPA
- Gross NPA %
- Return on Assets (ROA)
- Return on Equity (ROE)
- Net Interest Margin (NIM)
- Capital Adequacy Ratio (CAR)
- Bank Size (Total Assets)
- Loan to Deposit Ratio (LDR)
- Operating Efficiency Ratio (OER)
- Net Profit Margin (NPM)

---

## 📊 Detailed Analysis Performed

### 🔹 1. Data Preprocessing
- Imported two datasets and added a **Bank Type** column to distinguish Public and Private banks.
- Cleaned and merged the datasets for unified analysis.

### 🔹 2. Visual Exploratory Data Analysis (EDA)
- **Scatter Plots with Regression Lines**:
  - *Gross NPA % vs NPM*: To assess how bad loans affect profitability.
  - *OER vs NPM*: To examine whether operational efficiency translates into better margins.

- **Bar Charts**:
  - Compared **mean ROA, ROE, NIM, CAR, and NPM** between PSU and Private Banks.
  - Displayed individual performance metrics for all 20 banks.

- **Heatmap (Optional)**:
  - Correlation heatmap to identify multivariate relationships.

---

## 🧠 Key Insights Derived

### 🏦 Public vs Private Bank Observations:
1. **Private Sector Banks**:
   - Tend to have **lower Gross NPA %**, which contributes to healthier **Net Profit Margins**.
   - Demonstrate better **Operating Efficiency**, resulting in higher profitability.
   - Have consistently better **ROA** and **ROE**, indicating effective asset and equity utilization.
   - Maintain higher **Capital Adequacy Ratios**, implying financial stability.

2. **Public Sector Banks**:
   - Show **higher levels of Gross NPAs**, which directly drag down **NPM**.
   - Struggle with **high Operating Costs**, reflected by poor OER values.
   - Despite larger **bank size**, fail to deliver better margins due to inefficiencies.
   - Their **CAR** is relatively weaker, raising questions about long-term solvency under stress.

### 📉 Relationship-Based Insights:
- **Gross NPA %** has a **strong inverse relationship** with **Net Profit Margin** for both bank types.
- **OER** is a **critical determinant of profitability** — higher OER generally implies lower NPM.
- **NIM** positively correlates with ROA and ROE, especially in Private Banks.
- Operational discipline plays a more important role than size in determining profitability.

---

## 📌 Project Highlights

- 📁 Real-world structured financial data
- 📈 Clean visualizations using `Seaborn` and `Matplotlib`
- 🔎 Insightful, interpretable regression and comparison analysis
- 📌 Clear distinction in performance across bank types---

## 📊 Technologies Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Excel (for data formatting)
- Power BI (for dashboard visualization)

---

## 📈 Sample Visualizations

- **Linear Regression Plot:** Gross NPA % vs NPM  
- **OER Impact:** How OER affects profitability  
- **Bar Charts:** Category-wise comparison of financial indicators  
- **Bank Type Segmentation:** Separate views for PSU and Private Banks  

---

## ✅ How to Use

1. Clone the repository
2. Open the Jupyter Notebook (`.ipynb`) in Anaconda or VSCode
3. Make sure required libraries (`pandas`, `seaborn`, `matplotlib`) are installed
4. Run the notebook cells step by step
5. Optionally, open the Power BI dashboard for visual storytelling

---

## 🔍 Future Scope

- Add more years of data for time-series trend analysis
- Perform machine learning classification on bank risk levels
- Integrate RBI or open banking API for real-time data updates

---

## 📚 Author

**[Rohit Thakare]**  
MBA in FinTech | Financial Research & Analytics Enthusiast  
🔗 LinkedIn: [www.linkedin.com/in/rohit-thakare-4aa279324](www.linkedin.com/in/rohit-thakare-4aa279324)
