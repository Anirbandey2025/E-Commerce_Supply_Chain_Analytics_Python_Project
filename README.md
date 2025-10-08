# E-Commerce_Supply_Chain_Analytics_Python_Project Anirban

E-Commerce Supply Chain Analytics Project | Python Project

Objective: To build a Python-based analytics system that evaluates an e-commerce company’s supply-chain efficiency, measuring order-to-delivery performance, warehouse operations, and cost optimization.

I Developed an interactive EDA and performance analytics notebook using Pandas, NumPy, Matplotlib, and Seaborn to analyze shipment timelines, freight costs, and warehouse throughput. Created KPI summaries and visual insights tracking order status, delivery rate, and total spend across multiple cities and channels.

Key Insights:
• Total Orders Analyzed: 5,090 | Total Freight Cost: ₹37.3 M | Avg. Delivery Time: 6.8 days
• Courier B and Courier D handled > 60 % of total shipments, with Courier B showing the lowest delay ratio (4.2 %).
• Top 3 delay-prone states: Delhi (8.6 %), Bihar (8.1 %), Tamil Nadu (7.9 %) — indicating regional last-mile issues.
• Electronics and Home Appliances categories show highest freight-to-revenue ratio (> 12 %), reducing margin efficiency.
• Orders with weight > 8 kg account for 35 % of total freight cost though only 12 % of order count → urgent need for load balancing.
• Seasonal spike detected between Nov–Dec, increasing average delivery time by ~18 %.
• Scatter & heatmap analyses reveal a strong correlation (0.74) between distance and freight cost, confirming cost scalability per km.

Tools & Techniques Used:
• Python Libraries: Pandas, NumPy, Matplotlib, Seaborn
• Data Wrangling: Datetime conversion, missing-value imputation, feature engineering (Delivery_Delay, Freight_Efficiency)
• Analytics Methods: Groupby KPI aggregation, correlation matrix, trend plots, category distribution visuals
• Business Framing: Cost optimization, logistics benchmarking, courier performance scorecards
