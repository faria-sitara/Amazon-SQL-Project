# 📊 Amazon Sales & Customer Insights

This project uses SQL-based data analysis to extract actionable insights from an e-commerce dataset, simulating Amazon sales data. The goal is to support business decisions in inventory management, customer engagement, and revenue optimization.

## 🚀 Project Objectives

- Identify top-selling products and high-performing categories
- Analyze customer purchasing behavior and lifetime value
- Track monthly revenue trends
- Detect products with high return rates
- Evaluate seller performance and order success
- Generate inventory stock alerts
- Automate inventory updates after sales

## 🛠️ Technologies Used

- SQL Server / T-SQL
- SQL Window Functions
- Common Table Expressions (CTEs)
- Stored Procedures

## 📁 Key Features / Queries

1. **Top 10 Products by Sales**
   - Product ranking by total revenue and quantity sold.

2. **Revenue by Product Category**
   - Category-wise revenue and contribution percentages.

3. **Average Order Value (AOV)**
   - AOV for customers with more than 5 orders.

4. **Monthly Sales Trends**
   - Monthly revenue changes over the past year.

5. **Customer Lifetime Value (CLTV)**
   - Total revenue generated per customer with ranking.

6. **Inventory Stock Alerts**
   - Lists products with stock below a set threshold.

7. **Top Performing Sellers**
   - Seller ranking by revenue and order success percentage.

8. **Most Returned Products**
   - Products with the highest return rates.

9. **Declining Revenue Products**
   - Products with highest year-over-year revenue drop.

10. **Stored Procedure for Inventory Update**
   - Procedure to update inventory when a sale occurs.

## 📌 How to Use

1. Load your dataset into a SQL Server environment.
2. Run the provided SQL scripts in the documented order.
3. Customize thresholds or logic as needed (e.g., low stock alert level).
4. Use the stored procedure `add_sales` to simulate new orders and manage inventory updates.

## 📈 Business Value

This analysis enables better business decision-making by:
- Pinpointing high-value customers and products
- Reducing inventory risks
- Improving seller collaboration
- Identifying problem areas like high returns or sales declines

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

---

📬 Questions or suggestions? Feel free to reach out!

