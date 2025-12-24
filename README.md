# 📊 Fleet Inventory Data Analysis (Excel)

## 🧑‍💼 Project Overview
This project simulates the role of a **Junior Data Analyst** working in a local government office. The task involved importing, cleaning, and analyzing fleet inventory data received from another department. The objective was to prepare clean, structured data and generate meaningful insights using **Microsoft Excel**, primarily through **Pivot Tables**.

---

## 📁 Dataset
- **Format:** Excel (.xlsx)
- **Source:** Internal departmental fleet inventory data (simulated scenario)
- **Content:** Vehicle and equipment inventory information across multiple government departments

---

## 🧹 Part 1: Data Cleaning & Preparation

Before analysis, the raw dataset required extensive cleaning. The following steps were performed:

- Converted the original CSV file to **XLSX format**
- Adjusted **column widths** for full data visibility
- Removed **empty rows** using Excel filters
- Identified and removed **duplicate records**
- Corrected **spelling errors** in text fields
- Removed extra **double spaces** using Find & Replace
- Reconstructed incorrectly imported **department names** using **Flash Fill**
- Removed unnecessary columns after consolidation

📄 Cleaned dataset:

---

## 📈 Part 2: Data Analysis Using Pivot Tables

After cleaning, the dataset was analyzed to summarize fleet inventory distribution.

### 🔹 Table Formatting & Summary Statistics
- Converted the dataset into an **Excel Table**
- Used **AutoSum** to calculate:
  - Sum  
  - Average  
  - Minimum  
  - Maximum  
  - Count  

### 🔹 Pivot Table Analysis

Three pivot tables were created to analyze the data from different perspectives:

#### 1️⃣ Equipment Count by Department
- **Rows:** Department  
- **Values:** Sum of Equipment Count  
- Sorted in **descending order**

#### 2️⃣ Equipment Breakdown Within Departments
- **Rows:** Department → Equipment Class  
- **Values:** Sum of Equipment Count  
- Collapsed all fields except **Transportation**

#### 3️⃣ Department Breakdown Within Equipment Types
- **Rows:** Equipment Class → Department  
- **Values:** Sum of Equipment Count  
- Collapsed all fields except **CUV**

📊 Pivot table screenshots are stored in the `visuals/` folder.

---

## 🛠 Tools & Skills Used
- Microsoft Excel
- Data Cleaning & Preprocessing
- Pivot Tables
- AutoSum & Table Formatting
- Data Analysis & Interpretation

---

## 📌 Key Learning Outcomes
- Hands-on experience cleaning real-world messy data
- Strong understanding of Pivot Tables for summarizing datasets
- Ability to analyze and present inventory data clearly
- Practical simulation of an entry-level data analyst role

---

## 📂 Repository Structure
fleet-inventory-data-analysis/
├── data/
│ ├── raw_fleet_inventory.xlsx
│ └── cleaned_fleet_inventory.xlsx
├── analysis/
│ └── fleet_inventory_analysis.xlsx
├── visuals/
│ ├── pivot_table_department.png
│ ├── pivot_table_department_equipment.png
│ └── pivot_table_equipment_department.png
└── README.md

## 👤 Author
**Bibek Subedi**
