# 🚗 Car Sales Analysis Dashboard (Power BI)

This project presents a Power BI dashboard designed to analyze car sales behavior across different regions, socio-economic groups, and customer demographics. The dataset was sourced from [Kaggle](https://www.kaggle.com/) and processed to extract business insights that can help guide pricing, inventory, and marketing strategies.

---

## 📊 Project Overview

- **Goal:** Understand how car sales vary by brand, region, vehicle style, color, and customer demographic.
- **Scope:** The dashboard serves both tactical and strategic decision-making, offering insights by region, time period, and customer segments.
- **Tool:** Power BI for visual analytics, with preprocessing done in Excel.

---

## 🧰 Tools Used

- **Power BI Desktop**
- **Microsoft Excel**
- **Miro** – for ERD modeling
- **PowerPoint** – for dashboard background styling
- **Kaggle** – for dataset source

---

## 🎯 Project Objectives

- Visualize sales performance by region, gender, and time period.
- Identify top-selling brands, vehicle colors, and styles.
- Enable decision-makers to compare current vs. previous period sales.
- Reject or validate the hypothesis: *"Do all car brands sell equally across regions and income groups?"*

---

## 🧮 Calculated Measures

The following KPIs were created using DAX in Power BI:
- **Previous Period Sales**
- **Average Accumulated Sales**
- **Total Sales Sum**
- **Accumulated Sales**
- **Sales Percentage Variation**

---

## 📘 Data Model

The model consists of:
- **Fact Table:** `Sales`
- **Dimension Tables:** `Customers`, `Dealers`, `Vehicles`, `Calendar`
- **Relationship Type:** One-to-Many (1:N) from each dimension to the fact table

ERD Diagram![Entidad relacion Coder (3)](https://github.com/user-attachments/assets/8e3e9b72-d923-446c-b050-10e18ad3456c)


---

## 📸 Screenshots

### Main KPIs Page
KPI Dashboard(![image](https://github.com/user-attachments/assets/0580351e-8b0b-4dbd-89d6-6e053efa6ed7)


### Vehicle Insights
Vehicle Tab(![image](https://github.com/user-attachments/assets/d5e2c223-a803-448f-a394-6a2fe8cca6eb)


### Customer Demographics
Customer Tab(![image](https://github.com/user-attachments/assets/8d3e1ce5-07af-4c5e-b7cc-9e1c8448d2b9)


---

## 🔍 Key Insights

- **Sales behavior varies** significantly by region and socio-economic group.
- **Pale white vehicles** are the top-selling color across multiple regions.
- **Female customers** show different purchase patterns, suggesting the need for gender-targeted vehicle offerings.
- **Sales drop** consistently in the first two months of the year, suggesting seasonal discount opportunities.

---

## 🚀 Future Enhancements

- Analyze customer preferences by transmission type (manual vs. automatic)
- Explore electric vehicle demand via surveys
- Integrate marketing datasets for richer customer segmentation

---

## 📁 Dataset

Sourced from: [Kaggle - Car Sales Dataset](https://www.kaggle.com/)

---

## 👤 Author

**José De León**  
[LinkedIn]([https://www.linkedin.com/in/your-profile](https://www.linkedin.com/in/jose-de-leon-analytics/) | [Portfolio](https://github.com/josedeleon-analytics)

---

