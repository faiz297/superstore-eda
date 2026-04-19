# 🛒 Superstore Management System — Exploratory Data Analysis

An end-to-end EDA project analysing a superstore's operations across sales, profit, customers, regions, and delivery using Python.

---

## 📁 Project Structure

```
📦 superstore-eda
 ┣ 📓 EDA.ipynb                        # Main analysis notebook
 ┣ 📄 Superstore_Management_System.csv # Dataset
 ┣ 📄 requirements.txt                 # Python dependencies
 ┗ 📄 README.md                        # Project documentation
```

---

## 📊 Dataset Overview

| Feature | Detail |
|---|---|
| Records | 1,000 orders |
| Columns | 25 |
| Missing Values | None |
| Duplicates | None |

**Key columns:** Order ID, Order/Ship Date, Customer Segment, Product Category, Region, Sales Amount, Cost Price, Profit, Delivery Status, Stock Left

---

## 🔍 Analysis Performed

- **Data Quality Check** — null values, duplicates, data type conversion
- **Univariate Analysis** — distribution of all categorical and numerical variables
- **Bivariate Analysis** — sales & profit breakdown by category and region
- **Time Series Analysis** — monthly trends in sales, profit, and order volume
- **Correlation Analysis** — heatmap of numerical variable relationships
- **Customer Segment Analysis** — revenue and profit comparison across segments
- **Key Insights Summary** — overall KPIs and top performers

---

## 💡 Key Findings

- 📈 **Total Sales:** ₹12.74M | **Total Profit:** ₹3.19M | **Margin:** ~25%
- 🏆 **Top Category:** Grocery (highest profit)
- 🌍 **Best Region:** North
- 👤 **Most Profitable Segment:** Home Office
- ⚠️ **Delivery Concern:** Over 52% of orders were either Cancelled or Returned

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** — data manipulation
- **NumPy** — numerical operations
- **Matplotlib** — visualisations
- **Seaborn** — statistical plots

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/superstore-eda.git
   cd superstore-eda
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the notebook**
   ```bash
   jupyter notebook EDA.ipynb
   ```

> Make sure `Superstore_Management_System.csv` is in the same folder as the notebook.

---

## 👤 Author

**Faiz Idris**  
BCA Student | Data Analytics Enthusiast  
[LinkedIn](#) • [GitHub](#)
