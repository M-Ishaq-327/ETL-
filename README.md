# 🚀 End-to-End Data Analytics Project Using (Python + SQL) 📊

## 📌 Project Overview  

This project involves an end-to-end data analytics workflow using Python for data processing and SQL Server for data storage and analysis. The goal is to extract, clean, transform, and analyze sales data to derive meaningful insights.  

## 🔄 Steps Involved  

### 1️⃣ Data Extraction  

- 📥 Download data from Kaggle API.  
- 📂 Extract files from a zip archive.  

### 2️⃣ Data Preprocessing  

- 📑 Read the extracted file using Pandas.  
- 🛠 Handle missing values.  
- ✏️ Rename columns (convert to lowercase, replace spaces with underscores).  
- 📊 Derive new columns:  
  - 🏷 **Discount** = `list_price - sale_price`  
  - 💰 **Profit** = `sale_price - cost_price`  
- 📆 Convert `order_date` from object type to datetime.  
- 🗑 Drop unnecessary columns (`cost_price`, `list_price`, `discount_percent`).  

### 3️⃣ Loading Data into SQL Server  

- 📤 Load the cleaned data into SQL Server using the **append** option.  
- 🔄 Reload the data using the **replace** option after transformation.  

### 4️⃣ Data Analysis & Insights  

- 📈 Identify **top 10 revenue-generating products**.  
- 🏆 Find **top 5 highest-selling products** in each region.  
- 📊 Compare **month-over-month sales growth** for 2022 and 2023.  
- 📅 Determine **which month had the highest sales** for each category.  
- 📉 Identify the **sub-category with the highest profit growth** in 2023 compared to 2022.  

## 🛠 Technologies Used  

- 🐍 Python (Pandas)  
- 🗄 SQL Server  
- 🌐 Kaggle API  

💡 This project covers data extraction, transformation, and analysis to generate valuable business insights! 🚀📊  

