# Ecommerce

### E-commerce Data Analysis with MySQL & Python

This project showcases a complete data analysis workflow for an e-commerce dataset, starting with data ingestion — where raw CSV files are automatically read, cleaned, and loaded into a MySQL database — and continuing through data exploration and transformation using SQL queries and Python’s data analysis libraries. It culminates in insightful visualizations that reveal patterns in customer behavior, sales trends, product performance, and payment preferences. The process mirrors a real-world data analytics pipeline, combining database management with analytical programming to turn raw transactional data into actionable business insights.

### Libruaries Used

pandas
matplotlib.pyplot
seaborn
mysql.connector

---

## 📌 Project Workflow

1. **Data Collection**

   * Multiple CSV files (`customers.csv`, `orders.csv`, `products.csv`, etc.) containing e-commerce transaction data are prepared.

2. **Data Ingestion into MySQL**

   * Python script automatically reads each CSV file.
   * Cleans column names (replaces spaces, dashes, and dots with underscores).
   * Infers correct MySQL data types (INT, FLOAT, DATETIME, etc.).
   * Creates tables dynamically if they don’t exist.
   * Inserts cleaned data into MySQL tables.

3. **Data Exploration (SQL Queries)**

   * Retrieve and analyze:

     * Unique customer cities.
     * Yearly and monthly order counts.
     * Total sales per category.
     * Payment installment percentages.
     * Customer distribution by state.

4. **Data Analysis with Python**

   * Use **Pandas** for data manipulation and aggregation.
   * Use **Matplotlib** and **Seaborn** for statistical plotting.

5. **Visualization & Insights**

   * Generate bar charts, pie charts, and line plots to visualize:

     * Sales trends over time.
     * Best-selling categories.
     * Geographic distribution of customers.
     * Payment method preferences.

6. **Conclusion & Business Insights**

   * Summarize findings to highlight key business opportunities and operational improvements.

---

