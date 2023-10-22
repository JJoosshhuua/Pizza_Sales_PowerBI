# Pizza_Sales_PowerBI

- Used DAX Functions, Card, Funnel chart, Slicer chart, Bar chart, Donut chart, Area chart, and Column chart to analyze the Pizza Sales.

DAX Functions used : 

Avg Order Value = [Total Revenue] / DISTINCTCOUNT(Pizza_Sales[order_id])
Avg Pizza's Per Order = sum(Pizza_Sales[quantity]) / DISTINCTCOUNT(Pizza_Sales[order_id])
Total Orders = DISTINCTCOUNT(Pizza_Sales[order_id])
Total Pizzas Sold = sum(Pizza_Sales[quantity])
Total Revenue = sum(Pizza_Sales[total_price])
