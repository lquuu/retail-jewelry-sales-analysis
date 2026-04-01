# Jewelry Business Inventory & Sales Analysis
Exploratory data analysis of inventory, purchasing, and sales data for Halie & Co., a local jewelry business in Detroit, MI. Completed as part of the University of Michigan's Alternative Fall Break Data Science Program (October 2025).

## 🎯 Project Objectives
The client's core goals were to:
1. Reduce raw material costs — particularly for metals and gemstone cabochons
2. Optimize bulk purchasing frequency — identify workable time windows to buy materials at price lows
3. Identify top-performing products — by sales volume and profitability across product categories


## 📂 Repository Structure
```
├── Notebook_0__Summary_Statistics.ipynb       # Overview, price trend analysis, cost/profit by metal type
├── Notebook_1__Materials_Cleaning.ipynb       # Data cleaning for charms, pendants, clasps & cabochon inventory
├── Notebook_1a__Cabochon_Data_Analysis.ipynb  # Cabochon EDA: shape, color, stone value, inventory depletion
├── Notebook_1b__Charms__Pendants__Clasps.ipynb # Charms/pendants/clasps: profit margin and cost structure by type
├── Notebook_2__Sales.ipynb                    # Sales EDA: category breakdown, top products, units sold
```

## 📊 Analysis Overview
### Materials & Purchasing (Notebooks 0, 1, 1a, 1b)

Cleaned and standardized multi-source inventory data with inconsistent formatting, missing values, and data entry errors
Analyzed raw material price-per-package trends over time (2018–2024) to surface seasonal buying patterns
Compared cost and retail profit by metal type (gold-filled, sterling silver, etc.)
Identified top 20 cabochon stones by total inventory value and tracked quantity depletion to flag restocking needs
Visualized profit margin and cost structure by product type (charms, pendants, clasps) using grouped bar charts

### Sales (Notebook 2)

Categorized sales records into product types (bracelets, necklaces, earrings, rings, charms, etc.) using regex-based classification
Analyzed total units sold and product count per category to identify top-selling lines
Profiled high-revenue vs. high-volume products to support inventory and pricing decisions


## 🛠️ Tools & Libraries

Python 3 — pandas, NumPy, Matplotlib, Seaborn, Plotly Express
Deepnote (collaborative notebook environment)


## ⚠️ Data Privacy
Raw data files are not included in this repository. All analysis was conducted on proprietary business data provided by the client for the duration of the program.

## 👥 Context
This project was completed as part of the University of Michigan Alternative Fall Break Data Science Program, in partnership with Halie & Co. (Detroit, MI).
