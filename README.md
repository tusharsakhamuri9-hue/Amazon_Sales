# Amazon_Sales
Exploratory Data Analysis on Amazon sales data using Python. The project analyzes pricing, quantity, discounts, net sales, and category-wise performance through data cleaning, bivariate and multivariate analysis, and clear Seaborn visualizations to extract business insights.

# 📦 Amazon Sales Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on an Amazon sales dataset to understand sales behavior, pricing patterns, discounts, customer purchase trends, and category-wise performance.

This project is ideal for:
- Data Analyst / Data Science portfolios
- EDA practice
- Academic and interview submissions

---

## 🎯 Objectives
- Analyze overall sales and revenue trends  
- Study relationships between price, quantity, discounts, and sales  
- Perform bivariate and multivariate analysis  
- Compare category-wise performance  
- Extract meaningful business insights  

---

## 📂 Dataset Description
The dataset contains Amazon sales transaction data with the following columns:

- **OrderID** – Unique order identifier  
- **CustomerID** – Unique customer identifier  
- **ProductID** – Product identifier  
- **Category** – Product category  
- **Price** – Product price  
- **Quantity** – Number of units purchased  
- **Discount** – Discount applied  
- **Discount_Percentage** – Discount percentage  
- **Shipping_Cost** – Shipping cost  
- **Delivery_Rating** – Customer delivery rating  
- **Total_Amount** – Total amount before discount  
- **Net_Sales** – Final sales after discount  

---

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔍 EDA Workflow

### 1️⃣ Data Understanding
- Loaded dataset  
- Checked shape, columns, and data types  
- Reviewed sample records  

### 2️⃣ Data Cleaning
- Checked missing values  
- Handled incorrect data types  
- Removed duplicates  
- Ensured numerical consistency  

### 3️⃣ Univariate Analysis
- Distribution of Price, Quantity, Net Sales  
- Category frequency analysis  

### 4️⃣ Bivariate Analysis (Numerical vs Numerical)
- Price vs Quantity  
- Total Amount vs Net Sales  

### 5️⃣ Multivariate Analysis
- Price vs Category  
- Net Sales vs Category  

---

## 📊 Visualizations Used
- Scatter Plot  
- Joint Plot  
- Strip Plot  
- Violin Plot  
- Bar Plot  
- Point Plot  

All visualizations were created using **Seaborn** for clarity and readability.

---

## 📈 Key Insights
- Higher-priced products contribute more to total sales  
- Quantity purchased is mostly concentrated in lower values  
- Certain categories show higher average net sales  
- Discounts significantly affect net sales  
- Price variation differs across categories  

---

## 📁 Project Structure
Amazon-Sales-EDA/
│
├── amazon_dataset.csv
├── EDAproject.ipynb
├── README.md


---

## 🚀 How to Run
1. Clone the repository  
2. Install required libraries  
3. Open `EDAproject.ipynb` in Jupyter Notebook  
4. Run cells step by step  

---

## ✅ Conclusion
This project demonstrates a complete EDA process, from raw data understanding to insight generation, highlighting how data analysis supports business decision-making.
