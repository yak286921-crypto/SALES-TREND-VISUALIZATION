# 📈 CODTECH IT Solutions — Data Analytics Internship
## Task 1: Sales Trend Visualization

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Charts-4C72B0?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

## 📋 Internship Details

| Field | Details |
|-------|--------|
| **Name** |MD SAHIL ANSARI |
| **Intern ID** | CITS3147 |
| **Domain** | Data Analytics |
| **Duration** | 4 Weeks |
| **Mentor** | NEELA SANTHOSH KUMAR |
| **Company** | CODTECH IT Solutions Pvt. Ltd. |
| **Task** | Task 1 — Sales Trend Visualization |

---

## 🎯 Project Overview

> Analyze and visualize **sales trends** across time periods, product categories, regions, and customer segments from a multi-year retail sales dataset. Derive actionable business insights through comprehensive data visualization.

---

## 🗂️ Project Structure

```
Task-1-Sales-Trend-Visualization/
│
├── 📓 sales_trend_visualization.ipynb   ← Main Jupyter Notebook
├── 📊 sales_data.csv                    ← Dataset (500 records)
└── 📝 README.md
```

---

## 📊 Dataset Description

**File:** `sales_data.csv`
**Records:** 500 rows | **Columns:** 17

| Column | Description |
|--------|-------------|
| `order_id` | Unique order identifier |
| `date` | Order date (2021–2023) |
| `month` | Month name (Jan–Dec) |
| `quarter` | Quarter (Q1–Q4) |
| `year` | Year (2021, 2022, 2023) |
| `category` | Product category (Electronics, Clothing, Furniture, Groceries, Sports) |
| `sub_category` | Category + Product name |
| `product` | Product name |
| `region` | Sales region (North, South, East, West) |
| `state` | Indian state |
| `city` | City name |
| `customer_segment` | Consumer / Corporate / Home Office |
| `sales` | Total sales amount (₹) |
| `quantity` | Units sold |
| `discount` | Discount applied (0.0–0.4) |
| `profit` | Profit earned (₹) |
| `shipping_cost` | Shipping cost (₹) |

---

## 🛠️ Tools & Libraries Used

| Library | Purpose |
|---------|---------|
| **Pandas** | Data loading and manipulation |
| **NumPy** | Numerical operations |
| **Matplotlib** | Line charts, bar charts, pie charts |
| **Seaborn** | Heatmaps and statistical charts |

---

## 🔧 How to Run

### Step 1 — Install dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 2 — Open the notebook
```bash
jupyter notebook sales_trend_visualization.ipynb
```

### Step 3 — Run all cells
**Kernel → Restart & Run All**

---

## 📓 Notebook Sections

| Section | Visualization |
|---------|--------------|
| 1 | Library imports & data loading |
| 2 | Dataset overview & statistics |
| 3 | Monthly & yearly sales trend (line + bar charts) |
| 4 | Category-wise sales (bar + pie + line trend) |
| 5 | Regional sales (bar + pie charts) |
| 6 | Profit & discount analysis (scatter + bar) |
| 7 | Customer segment analysis (3 pie charts) |
| 8 | Top 10 products + category vs quarter heatmap |
| 9 | Key insights summary |

---

## 📈 Key Insights

1. **Monthly trend** shows seasonal peaks in Q3 and Q4
2. **Electronics** is the highest revenue-generating category
3. **North region** leads in overall sales contribution
4. **Consumer segment** accounts for the majority of orders
5. Higher discounts show a weak negative correlation with profit
6. **Year-on-year growth** is consistent across all 3 years

---

<div align="center">
<b>CODTECH IT Solutions Pvt. Ltd.</b> — Data Analytics Internship — Task 1
</div>
