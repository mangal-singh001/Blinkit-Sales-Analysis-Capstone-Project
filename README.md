# Blinkit Sales Analysis Capstone Project

## 📊 Project Overview

This project performs a comprehensive sales analysis of Blinkit (a quick-commerce grocery platform) using data science and BI techniques. The goal is to derive business insights from Blinkit’s grocery sales data — analyzing sales trends, customer behavior, and outlet performance — and present them via a Power BI dashboard.

---

## 🔍 Business Objectives

1. Understand Blinkit’s overall sales performance: total sales volume, average sale per transaction, and number of items.
2. Analyze customer satisfaction using average item ratings.
3. Explore how different item attributes (like fat content or product category) affect sales.
4. Compare outlet performance by:

   * Outlet type (supermarket, grocery store, etc.)
   * Outlet size
   * Outlet location tier
   * Outlet establishment year
5. Generate actionable insights for Blinkit stakeholders (e.g., which outlet types to focus on, popular product segments, and customer preferences).

---

## 📂 Project Structure

Here’s how the repository is organized:

```
.
├── BlinkIT Grocery Data.csv         # Raw dataset  
├── SQL/                             # SQL queries & scripts  
├── Python/                          # Data cleaning, EDA & analysis notebooks  
├── Power BI/                        # Power BI report files (.pbix)  
├── Images/                          # Screenshots, charts, dashboards  
└── Blinkit Analysis.pptx            # Presentation of findings & recommendations  
```

---

## 🛠️ Tools & Technologies

* **Python**: for data cleaning, exploratory data analysis (EDA), and preprocessing.
* **SQL**: to query and manipulate structured data.
* **Power BI**: to build an interactive dashboard using data modeling (relationships, DAX measures), visualizations, and slicers.
* **Data Visualization / Modeling**: Custom measures (KPIs), applied business logic, and visual storytelling.

---

## 📈 Key Metrics & KPIs

* **Total Sales**: Cumulative revenue generated from all transactions.
* **Average Sales**: Mean revenue per sale event.
* **Number of Items**: Total unique items sold.
* **Average Rating**: Mean customer rating for items.

---

## 📊 Insights & Findings

Some of the high-level insights (hypothetical, but grounded in what such an analysis can uncover):

* Low-fat items may contribute significantly to total sales, suggesting an opportunity to promote health-conscious products.
* Certain categories (e.g., Fruits & Vegetables, Snack Foods) could be high-revenue drivers.
* Medium-sized outlets might be outperforming others in terms of sales, indicating a strong business model at that scale.
* Tier-3 locations (or whichever location tier) might be surprisingly high in sales, meaning Blinkit could prioritize expansion or marketing there.
* Outlet establishment trends over time can inform Blinkit’s strategy about where to open new outlets or invest in existing ones.

---

## 💡 Business Recommendations

Based on the analysis, some suggested strategic actions Blinkit could consider:

1. **Inventory Optimization**: Focus more SKUs on high-demand categories (e.g., fruits, snacks) that drive most of the revenue.
2. **Outlet Strategy**: Expand in outlet types and sizes that are performing best (e.g., medium outlets) or replicate the business model of top-performing stores.
3. **Customer Engagement**: Promote low-fat products if they are both high in sales and satisfaction.
4. **Location Expansion**: Leverage insights on high-performing geographic tiers (tier-wise analysis) for future growth.
5. **Performance Monitoring**: Use the Power BI dashboard to track KPIs periodically and make data-driven decisions.

---

## 🚀 How to Run / Use This Project

1. **Clone the Repository**

   ```bash
   git clone https://github.com/mangal-singh001/Blinkit-Sales-Analysis-Capstone-Project.git  
   ```
2. **Data Exploration & Cleaning**

   * Use the Jupyter notebooks in the `Python/` folder to clean and preprocess the CSV data.
   * Optionally run SQL scripts from the `SQL/` folder to validate or transform data.
3. **Open the Power BI Dashboard**

   * Open the `.pbix` file in the `Power BI/` folder using Power BI Desktop.
   * Interact with slicers and visuals (e.g., outlet type, product category) to explore the insights.
4. **View the Presentation**

   * The `Blinkit Analysis.pptx` contains a summary of findings and business strategy recommendations.

---

## 📁 Data Details

* **Dataset**: `BlinkIT Grocery Data.csv` — contains Blinkit transaction-level data including item details, outlet information, sales, and ratings.
* **Columns**: (for example) `Item Fat Content`, `Item Type`, `Outlet Establishment Year`, `Outlet Size`, `Outlet Location Tier`, `Sales`, `Rating`, etc.

---

## ⚠️ Limitations & Considerations

* Data Quality: There may be missing/incorrect values in rating or sales data, which could bias insights.
* Representativeness: The dataset may not cover all Blinkit outlets or may be a sample, so conclusions should be considered in that context.
* Temporal Scope: If the data is from a specific time period, trends may not generalize outside that window.
* Causality: The analysis is primarily observational; correlation does not necessarily imply causation.

---

## 👥 Contributors

* **Mangal Singh** — Project lead: cleaning, EDA, Power BI design, analysis, and insights.
* (You can add more names if you collaborated with others.)

---

## 📚 References / Inspiration

This type of Blinkit sales-analysis dashboard has been done by other data analysts / learners as portfolio projects. ([GitHub][1])
Also, structure and content for this README are inspired by best practices for data-science project documentation. ([Gist][2])

---

## 📄 License

Specify if your project is open-source, e.g.:

```
MIT License  
© 2025 Mangal Singh  
```

---

If you like, I can write a **detailed README** (with images, badges, and all sections) tailored for this exact repo — do you want me to do that?

[1]: https://github.com/Tejassrivastava8/Blinkit-Data-Analysis?utm_source=chatgpt.com "GitHub - Tejassrivastava8/Blinkit-Data-Analysis: This Power BI dashboard project offers a comprehensive analysis of Blinkit, India's Last Minute App, focusing on sales performance, customer satisfaction, and inventory distribution. The interactive dashboard transforms raw data into actionable insights, enabling data-driven decision-making for business optimization."
[2]: https://gist.github.com/danielecook/94272f387d3366070d2546e2eadefe57?utm_source=chatgpt.com "A template to make good README.md for a scientific or data analysis project · GitHub"
