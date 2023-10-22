# Pizza_Sales_PowerBI

DAX Functions used : 

Avg Order Value = [Total Revenue] / DISTINCTCOUNT(Pizza_Sales[order_id])
Avg Pizza's Per Order = sum(Pizza_Sales[quantity]) / DISTINCTCOUNT(Pizza_Sales[order_id])
Total Orders = DISTINCTCOUNT(Pizza_Sales[order_id])
Total Pizzas Sold = sum(Pizza_Sales[quantity])
Total Revenue = sum(Pizza_Sales[total_price])
