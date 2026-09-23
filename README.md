# Power Pivot Sales Dashboard & Data Modeling

An advanced Excel data modeling and analytics project developed using **Power Pivot**, **Data Model (Power Pivot)**, and **DAX (Data Analysis Expressions)**. This project demonstrates how to relationalize multiple flat data sheets, build an efficient data model, and design a clean, professional dashboard for sales insights.

---

## 📌 Project Overview
The objective of this project was to transform separate transactional and dimensional datasets into a cohesive business intelligence solution. Instead of relying on traditional, slow `VLOOKUP` or `XLOOKUP` functions, the data was loaded directly into Excel's **Data Model** to build an optimized star-schema relationship, drastically reducing file size and improving calculation speeds.

## 🛠️ Features & Technical Implementation

### 1. Data Sheets & Structure
The workbook consists of the following structured tables:
*   **`Dashboard`**: The final user interface containing high-level dynamic summaries and visual charts.
*   **`Customers`**: Customer dimension table featuring `Customer ID`, `Customer Name`, and `City`.
*   **`Products`**: Product dimension table featuring `Product ID`, `Product Name`, `Category`, and `Price`.
*   **`Sales`**: Transactional fact table containing 22 records with `Sales ID`, `Customer ID`, `Product ID`, `Quantity`, and `Date`.
*   **`External Data`**: Documented storage for external tracking data.

### 2. Relational Data Modeling (Power Pivot)
*   Established a **Star Schema** by connecting the fact table (`Sales`) with dimension tables (`Customers` and `Products`).
*   Created robust relationships using **Primary Keys** (`Customer ID`, `Product ID`) and **Foreign Keys** ensuring strict data integrity with zero duplicates in dimension tables.

### 3. Measures & DAX Expressions
Calculations were implemented using core DAX expressions within the Data Model:
*   **Total Sales ($)**: Calculated dynamically to reflect total revenue across categories and regions.
*   **Total Quantity Sold**: Aggregated to track product performance volume.

### 4. Interactive Dashboard & Visualizations
The main **Dashboard** view provides critical retail insights at a glance:
*   **Total Sales by Product Category**: A Clustered Column Chart visualizing performance across categories like Electronics, Accessories, and Furniture.
*   **Total Sales by City**: A clean visual summary showing market penetration across major cities (Sylhet, Dhaka, Chittagong, Khulna, Rajshahi).

---

## 🚀 Key Learning Outcomes
*   Mastered the workflow of **Excel Power Pivot** and handling data inside the Excel Data Model environment.
*   Understood relational database concepts (One-to-Many relationships) within a spreadsheet context.
*   Designed a scannable, executive-ready dashboard adhering to professional design principles (clean alignment, precise data formatting, and clear visual hierarchy).

## 📁 How to View the Project
1. Clone or download this repository.
2. Open `module-4-power-pivot-model.xlsx` using Microsoft Excel (Excel 2016 or newer with Power Pivot enabled is recommended).
3. Navigate to the **Dashboard** sheet to interact with the visualizations.


## 👨‍💻 Author

**Bayzid Mostak**<br>
*Data Analyst & Visualization Expert*

*   [LinkedIn] https://www.linkedin.com/in/bayzid-mostak-data-analyst/
*   [GitHub] https://github.com/TusharAlBayzid
