# DataScienceCourse3_Assignment1
**Power BI Data Cleaning and Visualization — DS PGC Course 3 Assignment 1**

---

## 📘 Assignment Overview
This assignment demonstrates **data cleaning, modeling, and visualization in Microsoft Power BI Desktop** using three tables: **Customer**, **Product**, and **Sales**.  
Deliverable: a PDF with screenshots of each task and step-by-step instructions.

---

## 🧩 Tasks Summary
1. **Data Cleaning** — round Price; split Customer into FirstName & LastName.  
2. **Standardization** — Category → UPPERCASE; replace `unemployment` → `Unemployed` in Profession.  
3. **Data Types & Consistency** — ensure Date, Price types; standardize Size values.  
4. **Modeling & Deduplication** — create relationships using CustomerID & ProductID; remove duplicates.  
5. **Visualizations** — Total Sales by Category (bar); Sales % by Category (pie).

---

## 🧰 Tools & Features
- Power BI Desktop (latest stable release)  
- Power Query Editor (Transform, Add Column, Replace Values, Column From Examples, Remove Duplicates)  
- Data Model relationships (1-to-many: Customer→Sales, Product→Sales)  
- DAX measures (e.g., `Total Sales := SUMX(Sales, Sales[Price] * Sales[Quantity])`)  
- Visuals: Clustered column chart, Pie/Donut chart, Table, Cards, Conditional Formatting  
- Power BI features: Q&A visual, Bookmarks, Analytics pane (reference line)

---

## 📂 Files Included
- `DataScienceCourse3Assignmen1Question.pdf` — assignment brief.  
- `DataScienceCourse3Assignment1Solution.pdf` — solution with screenshots and steps.

---

## 🧭 How to Review
1. Download `DataScienceCourse3Assignment1Solution.pdf`.  
2. Open Power BI Desktop and replicate steps (Power Query → Transform Data).  
3. Verify each screenshot page in the PDF corresponds to Tasks 1–5.

---

## 👤 Author
**Utkarsh Anand**  
DS PGC Course 3 — Internshala Trainings
