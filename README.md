# product-discount-analysis
An Excel-based analysis of product discount, ratings, and category insights.

# 📊 Product Discount & Rating Analysis (Excel Project)

This project is an end-to-end data analysis performed in Microsoft Excel to explore the relationships between **product pricing**, **discounts**, **ratings**, and **categories** in an e-commerce dataset.

---

## 🛠 Tools Used

- Microsoft Excel
  - Pivot Tables
  - Calculated Columns
  - Scatter & Line Charts
- Data Cleaning & Formula Logic

---

## 🎯 Objective

To analyze patterns in discounts, product ratings, and category performance and draw insights that can support business decisions like pricing strategy, product listing prioritization, and promotional planning.

---

## 📁 Files Included

- `product_analysis_project.xlsx`: Main Excel workbook with all pivot tables, charts, and formulas

---

## 📌 Key Questions Answered

| Q# | Analysis Task |
|----|-----------------------------|
| 1  | Average discount percentage by product category |
| 2  | Count of products under each category |
| 3  | Total number of reviews per category |
| 4  | Products with the highest average ratings |
| 5  | Comparison of average actual price vs discounted price by category |
| 6  | Products with the highest number of reviews |
| 7  | Number of products with a discount of 50% or more |
| 8  | Distribution of product ratings |
| 9  | Total potential revenue by category *(Actual Price × Rating Count)* |
| 10 | Number of unique products per price range bucket |
| 11 | Relationship between rating and discount (scatter & line chart) |
| 12 | Count of products with fewer than 1,000 reviews |
| 13 | Categories with the highest product discounts |
| 14 | Top 5 products by rating + number of reviews (combined score) |

---

## 🔍 Sample Insight (Q11: Discount vs Rating)

A scatter chart was created to examine the correlation between **discount percentage** and **rounded product rating**. The chart showed that:
> 🔹 There is no strong correlation between high discounts and higher product ratings.

---

## 🧠 Notable Techniques

- **Custom formulas** like:
  - `=(Actual Price - Discounted Price) / Actual Price`
  - `=IF(Discount % >= 50, "Yes", "No")`
  - `=Rounded Rating + (Rating Count / 1000)`
- **Bucket grouping** using nested `IF` statements for ranges
- **Sorting & filtering** for top insights
- **Dynamic charts** for visual storytelling

---

## 📌 How to View the File

You can view the workbook directly in Excel or Google Sheets. All questions are answered on separate sheets (labeled `Q1`, `Q2`, etc.) for easy navigation.

---

## ✅ Summary

This project showcases practical Excel-based analytics techniques applied to real-world data questions.  
It demonstrates key skills in:
- Structured data exploration
- Business insight generation
- Communicating findings visually

---
