# 🛒 Grocery Sales Data Analysis

An end-to-end data analysis project using Python to explore, analyze, and visualize grocery store sales data, uncovering key business insights regarding revenue, product performance, and regional sales distribution.

---

## 📊 Project Overview
This project processes a grocery sales dataset containing transactional records to understand customer purchasing behavior, top-performing product categories, store-wise performance, and revenue distribution. The complete pipeline includes data inspection, data cleaning verification, advanced aggregations, and visual storytelling using charts.

---

## 🛠️ Tech Stack & Libraries
* **Python** (Programming Language)
* **Pandas** (Data Manipulation & Aggregation)
* **NumPy** (Numerical Computations)
* **Matplotlib** (Data Visualization)
* **Jupyter Notebook** (Development Environment)

---

## 📁 Dataset Features
The dataset (`Grocery Sales.csv`) contains **600 rows and 8 columns**:
1. **Bill_ID**: Unique identifier for each transaction bill.
2. **Date**: Timestamp of the transaction.
3. **Product_Name**: Name of the grocery item purchased.
4. **Category**: Product category (e.g., Staples & Grains, Dairy & Bakery, Snacks, etc.).
5. **Quantity**: Number of units purchased per transaction.
6. **Price_Per_Unit**: Price of a single unit of the product.
7. **Store_Location**: City/Location of the store branch.
8. **Total_Bill_Amount**: Total calculated amount for the transaction.

---

## 🔍 Key Analysis & Insights Performed
* **Data Inspection & Cleaning:** Checked for dataset dimensions, null values, and duplicate entries to ensure data integrity.
* **Category-Wise Analysis:** Evaluated total revenue and quantity sold per product category (identifying *Staples & Grains* as top revenue generator).
* **Store/City-Wise Sales:** Analyzed regional performance across multiple locations (such as Nagpur, Mumbai, Pune, Thane, and Nashik) using bar and pie charts.
* **Top Products Performance:** Identified top-selling products by total revenue and total units sold.
* **Advanced Filtering & Metrics:** Filtered high-value bills (transactions > ₹500), calculated average/mean bill amounts, and computed percentage-wise revenue distribution for each category.

---

## 📈 Visualizations Included
* **Category-Wise Sales Bar Chart** (Custom colored visualizations)
* **City-Wise Sales Pie Chart** (Percentage-based breakdown)
* **Top Products Revenue Bar Chart**
* **Category-Wise Quantity Sold Distribution**

---

## 🚀 How to Run the Project
1. Clone this repository or download the files.
2. Ensure you have Jupyter Notebook and the required libraries installed (`pandas`, `numpy`, `matplotlib`).
3. Place `Grocery Sales.csv` in the same directory as the Jupyter Notebook file (`Grocery Sales Analysis.ipynb`).
4. Run the notebook cells sequentially to execute the complete analysis.

---

## 👩‍💻 Author
**Dhanashree Manohar Chavhan**