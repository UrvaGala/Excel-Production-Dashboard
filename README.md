# 📊 Excel Production Dashboard

An interactive Production Dashboard built in **Microsoft Excel** to transform raw production data into meaningful business insights using **data cleaning**, **VLOOKUP**, **Pivot Tables**, **Pivot Charts**, and **Slicers**.

---

## 📷 Dashboard Preview

![Production Dashboard](Production%20Dashboard.png)

---

## 📌 Project Overview

This project demonstrates the complete workflow of cleaning, transforming, analyzing, and visualizing production data in Microsoft Excel.

The dashboard enables users to monitor production performance, compare product categories, analyze manager performance, and interactively filter data using slicers.

---

## 🧹 Data Cleaning Process

The following preprocessing steps were performed before building the dashboard:

### 1. Handling Missing Values
- Replaced all blank values in the **Gender** column with **"Unknown"** to maintain data consistency.

### 2. Correcting Inconsistent Manager Ages

The dataset contained multiple age values for the same manager.

To standardize the data:

- Sorted the dataset by **Production Date** (Oldest → Newest).
- Copied the **Manager** column to a new worksheet.
- Removed duplicate manager names.
- Used **VLOOKUP** to retrieve the earliest recorded age for each manager.
- Created a **New Age** column in the original dataset.
- Used **VLOOKUP** again to populate the corrected ages.
- Converted formulas into static values using **Paste Special → Values**.
- Removed the temporary columns.
- Renamed the final column as **True Age**.

This ensured every manager had one consistent age across the dataset.

---

## 📊 Dashboard Features

The interactive dashboard includes:

- 📈 Pivot Charts
- 📋 Pivot Tables
- 🎛 Interactive Slicers
- 📦 Product-wise Analysis
- 👨‍💼 Manager-wise Analysis
- 💰 Production Cost Analysis
- 📅 Time-based Production Trends

---

## 📈 Key Insights

- Compare production costs across different product categories.
- Analyze manager-wise production performance.
- Monitor production trends over time.
- Filter the dashboard dynamically using slicers.
- Generate quick business insights for decision-making.

---

## 🛠 Excel Features Used

- Data Cleaning
- Sorting
- Remove Duplicates
- VLOOKUP
- Paste Special (Values)
- Pivot Tables
- Pivot Charts
- Slicers
- Dashboard Design

---

## 💻 Tools Used

- Microsoft Excel

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Analysis
- Dashboard Development
- Data Visualization
- Business Intelligence
- Microsoft Excel

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `Dashboard.xlsx` | Excel dashboard project |
| `Production Dashboard.png` | Dashboard screenshot |
| `README.md` | Project documentation |

---

## ▶️ How to Use

1. Download the `Dashboard.xlsx` file.
2. Open it using Microsoft Excel.
3. Navigate to the **Dashboard** worksheet.
4. Use the slicers to interactively filter the data and explore different production insights.

---

## 👤 Author

**Urva Gala**

---

⭐ If you found this project useful, consider giving the repository a star!
