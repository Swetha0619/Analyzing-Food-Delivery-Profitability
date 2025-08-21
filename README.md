# Analyzing-Food-Delivery-Profitability
Analyzed 1,000 food delivery orders in New Delhi to evaluate profitability. Processed raw data, cleaned discount values, and calculated per-order profit. Visualized trends to reveal how delivery fees, commissions, discounts, and refunds impact margins, efficiency, and customer behavior.

Food Orders Profitability Analysis – New Delhi
📌 Objective
Analyze food delivery orders to understand profitability drivers, focusing on discounts, delivery fees, commissions, and payment methods.
📊 Dataset
Food delivery transactions (New Delhi)
Includes: order/delivery date, order value, fees, discounts, payment method
🛠 Tools Used
Python · Pandas · Regex · Matplotlib · Seaborn
🔑 Steps
Data Exploration – Loaded & inspected key fields
Data Cleaning – Converted dates, standardized discounts (% / flat / none)
Profit Formula –
Profit = Order Value + Delivery Fee – (Commission + Processing + Refunds + Discount)
Summary Stats – Orders, revenue, profit, avg. profit/order, outliers
Visuals – Profit distribution (histogram) & profit by payment method (boxplot)
Insights – Discounts impact margins, some payment methods less profitable, negative-profit orders need review
🚀 Recommendations
Optimize discount strategy
Reassess costly payment methods
Investigate loss-making orders
Extend analysis to seasonal & customer-level trends
