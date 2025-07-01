
# 📦 Amazon Sales Data Analysis

## 📄 Overview
This project performs **Exploratory Data Analysis (EDA)** and **data cleaning** on a real-world **Amazon Sales Report dataset**. It aims to extract meaningful insights about sales, customer behavior, fulfillment status, and time-based trends.

---

## 🎯 Objective
To analyze and visualize Amazon sales data in order to:
- Understand sales trends over time
- Identify top-performing categories
- Clean and preprocess messy data
- Calculate essential statistics like total revenue, average order value, etc.
- Detect patterns using visualizations and correlation analysis

---

## 🛠️ Technologies Used

| Tool / Library   | Purpose                           |
|------------------|-----------------------------------|
| Python           | Programming language              |
| Pandas           | Data manipulation & analysis      |
| NumPy            | Numerical computing               |
| Matplotlib       | Data visualization                |
| Seaborn          | Statistical plotting              |
| Jupyter Notebook | Development environment           |

---

## 📊 Dataset Summary

- **Filename**: `Amazon Sale Report.csv`
- **Features Analyzed**:
  - `Order_ID`, `Status`, `Fulfilment`, `Amount`, `Category`, `ship-postal-code`, `Date`, `fulfilled-by`, and more
- **Key Transformations**:
  - Renaming columns
  - Handling missing values (`Amount`, `ship-postal-code`, etc.)
  - Parsing and aggregating date fields
  - Filling fulfillment values logically based on conditions

---

## 🔍 Key Analyses

1. **Basic Statistics**
   - Count, Mean, Median, Mode, Standard Deviation
2. **Data Cleaning**
   - Removed duplicates
   - Filled missing values
   - Converted date columns
3. **Visual Explorations**
   - Histograms for numeric features
   - Line plot for `Status` distribution
   - Heatmap for correlation among numeric fields
4. **Trend Analysis**
   - Monthly sales trend
   - Category-wise total sales
   - Category-wise monthly sales pattern

---

## 📈 Sample Insights

- **Max Sales Amount**: ₹[value from notebook]
- **Top Performing Categories**: `Electronics`, `Clothing`, etc.
- **Highest Sales Month**: [Month-Year]
- **Fulfilment Type Most Used**: `Amazon` / `Easy Ship`

---

## 📁 Folder Structure

```bash
📦 Amazon-Sales-EDA/
├── 📜 project_notebook.ipynb      # Main analysis notebook
├── 📄 README.md                   # Project documentation (this file)
├── 📂 data/
│   └── Amazon Sale Report.csv     # Source dataset
```

---

## ✅ Next Steps / Suggestions

- Add model training (regression/classification for prediction)
- Perform time-series forecasting
- Deploy dashboard with Streamlit or Tableau

---

## 🧑‍💻 Author

**Earuva Teja**  
B.Tech CSE | Data Analyst Intern | Simplilearn IBM Certified
