📊 Fleet Inventory Data Analysis (Excel)
🧑‍💼 Project Scenario

This project simulates the role of a Junior Data Analyst working in a local government office. The task involved importing, cleaning, and analyzing fleet inventory data received from another department. The goal was to prepare accurate, structured data and extract meaningful insights using Excel tools, primarily Pivot Tables.

📁 Dataset

Format: Excel (XLSX)

Source: Internal departmental fleet inventory data (simulated)

Content: Vehicle and equipment inventory details across government departments

🧹 Part 1: Data Cleaning & Preparation

The raw dataset required multiple cleaning steps before analysis could be performed. The following actions were completed:

Converted the original CSV file to XLSX format

Adjusted column widths for clear data visibility

Removed empty rows using filter functionality

Identified and removed duplicate records

Corrected spelling errors in text fields

Removed unnecessary extra whitespace using Find & Replace

Reconstructed department names using Flash Fill after incorrect data import

Removed redundant columns after consolidation

📄 Cleaned data is available in:

data/cleaned_fleet_inventory.xlsx

📈 Part 2: Data Analysis Using Pivot Tables

After cleaning the data, analysis was conducted to summarize and explore the fleet inventory.

✔ Table Formatting & Summary Statistics

Converted dataset into an Excel Table

Used AutoSum to calculate:

Sum

Average

Minimum

Maximum

Count

✔ Pivot Table Analysis

Three pivot tables were created to analyze the inventory from different perspectives:

1️⃣ Equipment Count by Department

Rows: Department

Values: Sum of Equipment Count

Sorted in descending order

2️⃣ Equipment Type Breakdown Within Departments

Rows: Department → Equipment Class

Values: Sum of Equipment Count

Collapsed all fields except Transportation

3️⃣ Department Breakdown Within Equipment Types

Rows: Equipment Class → Department

Values: Sum of Equipment Count

Collapsed all fields except CUV

📊 Pivot table visuals are available in the visuals/ folder.

🛠 Tools & Skills Used

Microsoft Excel

Data Cleaning & Preprocessing

Pivot Tables

AutoSum & Table Formatting

Data Analysis & Interpretation

📌 Key Learning Outcomes

Practical experience cleaning real-world messy data

Strong understanding of Pivot Tables for summarizing datasets

Ability to present structured data insights clearly

Simulated experience of an entry-level data analyst role

🔗 Project Files

Raw data: data/raw_fleet_inventory.xlsx

Cleaned data: data/cleaned_fleet_inventory.xlsx

Analysis file: analysis/fleet_inventory_analysis.xlsx

Visuals: visuals/

👤 Author

Bibek Subedi
