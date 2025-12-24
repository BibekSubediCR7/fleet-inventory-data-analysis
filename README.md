# 📊 Fleet Inventory Data Analysis (Excel)

## 🧑‍💼 Project Overview
This project simulates the responsibilities of a **Junior Data Analyst** in a local government office. The work was divided into two phases. In the first phase, raw fleet inventory data was imported from a CSV file and cleaned for accuracy and consistency. In the second phase, a separate fleet inventory dataset was imported from another CSV file, cleaned, and analyzed using **Pivot Tables** to generate summarized insights for reporting and dashboard preparation.

---

## 📁 Datasets
- **Format:** CSV (raw) → Excel (.xlsx) after cleaning
- **Source:** Internal departmental fleet inventory data (simulated scenario)
- **Content:** Vehicle and equipment inventory details across government departments

---

## 🧹 Part 1: Data Cleaning & Preparation (Raw CSV)

The first dataset was provided in CSV format and required cleaning before any analysis could be performed.

### Tasks Performed
- Converted the raw CSV file to **XLSX format**
- Adjusted **column widths** for clear data visibility
- Removed **empty rows** using Excel filters
- Identified and removed **duplicate records**
- Corrected **spelling errors** in text fields
- Removed extra **double spaces** using Find & Replace
- Reconstructed incorrectly imported **department names** using **Flash Fill**
- Removed unnecessary columns after consolidation


---

## 📈 Part 2: Data Cleaning & Analysis Using Pivot Tables (Separate Dataset)

A second fleet inventory dataset was provided in CSV format. This dataset was cleaned and analyzed to summarize equipment distribution across departments.

### Data Preparation
- Imported raw CSV file into Excel
- Formatted the dataset as an **Excel Table**
- Cleaned inconsistencies and formatting issues
- Ensured numerical fields were correctly structured for analysis

### Summary Statistics
- Used **AutoSum** to calculate:
  - Sum  
  - Average  
  - Minimum  
  - Maximum  
  - Count  

### Pivot Table Analysis

Three pivot tables were created to analyze the cleaned dataset:

#### 1️⃣ Equipment Count by Department
- **Rows:** Department  
- **Values:** Sum of Equipment Count  
- Sorted in **descending order**

#### 2️⃣ Equipment Class Breakdown Within Departments
- **Rows:** Department → Equipment Class  
- **Values:** Sum of Equipment Count  
- Collapsed all fields except **Transportation**

#### 3️⃣ Department Breakdown Within Equipment Classes
- **Rows:** Equipment Class → Department  
- **Values:** Sum of Equipment Count  
- Collapsed all fields except **CUV**

📊 Pivot table screenshots are available in the `visuals/` directory.

---


---

## 🛠 Tools & Skills Used
- Microsoft Excel
- CSV to Excel Data Conversion
- Data Cleaning & Preparation
- Pivot Tables
- AutoSum & Table Formatting
- Data Analysis & Interpretation

---

## 📌 Key Learning Outcomes
- Experience working with multiple raw datasets
- Strong data cleaning and preparation skills
- Practical use of Pivot Tables for inventory analysis
- Realistic simulation of an entry-level data analyst workflow

---

## 📂 Repository Structure

fleet-inventory-data-analysis/
├── data/
│ ├── part1_raw_fleet_inventory.csv
│ ├── part1_cleaned_fleet_inventory.xlsx
│ └── part2_raw_fleet_inventory.csv
├── analysis/
│ └── part2_fleet_inventory_analysis.xlsx
├── visuals/
│ ├── pivot_table_department.png
│ ├── pivot_table_department_equipment.png
│ └── pivot_table_equipment_department.png
└── README.md
---

## 👤 Author
**Bibek Subedi**
