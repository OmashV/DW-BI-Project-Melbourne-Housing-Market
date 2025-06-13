# DW & BI Project – Melbourne Housing Market 🏘️

This project is part of my Semester 1, 2025 coursework for **Data Warehousing and Business Intelligence**. It involves building a complete DW & BI solution for analyzing housing market trends in Melbourne using SQL Server, SSIS, SSAS, Excel, and Power BI.

---

## 📊 Project Overview

- **Domain**: Real Estate / Housing Market  
- **Dataset**: Melbourne Housing Market Dataset (extended to cover one year)  
- **Goal**: Enable data-driven analysis of housing sales trends, pricing, property types, and location insights using DW & BI tools.

---

## 🛠️ Tools & Technologies

- **SQL Server** – Data warehouse implementation  
- **SSIS** – ETL development with multiple data sources (CSV, SQL)  
- **SSAS** – Cube design and OLAP implementation  
- **Excel** – OLAP analysis with PivotTables, roll-up, drill-down, slice, and dice  
- **Power BI** – Interactive reports with matrix visuals, slicers, drill-down, and drill-through  
- **DAX** – Used in Power BI for measures and calculations

---

## 📁 Project Components

### 1. **Data Preparation**
- Cleaned and separated raw data into:
  - `properties.csv`
  - `sales.csv`
  - `sellers.csv`
  - `location.csv`
- Ensured proper relationships and coverage for one year.

### 2. **Data Warehouse Design**
- Implemented a **star schema** with:
  - **Fact Table**: Property Sales
  - **Dimensions**: Property, Seller, Location, Date
  - Included a **Slowly Changing Dimension (SCD)**

### 3. **ETL with SSIS**
- Extracted data from CSV and database sources
- Transformed and loaded into SQL Server DW
- Developed an **accumulating snapshot fact table** to capture transaction lifecycle
- Updated processing time using secondary ETL package

### 4. **SSAS Cube**
- Built a cube with:
  - Measures: Total Sales, Average Price, etc.
  - Hierarchies: Region → Suburb
  - Connected to Excel and Power BI for OLAP analysis

### 5. **OLAP Analysis**
- Used Excel PivotTables to demonstrate:
  - Roll-up, Drill-down
  - Slice and Dice
  - Pivoting and dynamic exploration

### 6. **Power BI Reporting**
- Created 4 reports:
  - **Matrix Visual** with groupings
  - **Cascading Filters** with multiple slicers
  - **Drill-down Report**: Year → Month
  - **Drill-through Report**: Navigate to detailed view by suburb or property type


## 📝 Learning Outcomes

- Hands-on experience in designing dimensional models
- Building real-world ETL pipelines using SSIS
- Implementing SSAS Cubes and OLAP operations
- Developing analytical dashboards with Excel and Power BI
- Applying DAX for business logic in reports

---


## 📬 Contact

**Omash Viduranga**  
3rd Year Data Science Undergraduate  
Email: [vidurangaomash@gmail.com]  


