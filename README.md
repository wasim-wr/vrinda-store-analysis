# vrinda-store-analysis

🛍️ Vrinda Store
Annual Sales Analysis Report — 2022
Excel Dashboard · Data Analytics · Business Intelligence

1. Project Overview
Vrinda Store is an Indian fashion e-commerce brand selling women's and men's ethnic wear (kurtas, sets, sarees, tops, western dresses). This project analyses 31,047 orders placed across 7 sales channels during 2022, using Excel to clean, model, and visualise the data into an interactive dashboard for business decision-making.
Key Dataset Facts
• Records: 31,047 orders  |  Columns: 21 attributes per order
• Period: January – December 2022
• Channels: Amazon, Flipkart, Myntra, Ajio, Meesho, Nalli, Others
• Geography: 20+ Indian states
• Total Revenue: ₹21,176,377
• Tools Used: Microsoft Excel (Pivot Tables, Charts, Slicers, Dashboard)

2. Business Questions & KPIs Solved
The analysis was structured around six core business questions to drive actionable insights:

KPI Question	Finding	Business Impact
Which month had peak sales & orders?	March — ₹19.28L / 2,819 orders	Align inventory & campaigns to Q1
Who buys more — Men or Women?	Women: 64%  |  Men: 36%	Focus marketing on women shoppers
Top 5 contributing states?	MH, KA, UP, TS, TN (top 5)	Prioritise logistics in these states
Which age group orders most?	Adult women (35%) dominate	Target 30–49 age segment
Which channel drives most revenue?	Amazon 35% → Myntra 23% → Flipkart 22%	Double down on Amazon; grow Myntra
What is the order fulfilment rate?	92.2% delivered; 7.8% cancelled/returned	Reduce cancellations in low-tier cities

3. Process
3.1  Data Collection
Raw transactional data exported from the store's backend — one row per order containing order ID, customer ID, gender, age, date, channel, category, size, amount, and ship location.
3.2  Data Cleaning
• Standardised Gender column (M → Men, W → Women)
• Corrected Qty column (One/Two → 1/2)
• Removed blank and duplicate rows
• Derived Month column from Date for time-series analysis
• Created Age Group buckets: Teenager (<30), Adult (30–49), Senior (50+)
3.3  Data Processing & Analysis
• Built Pivot Tables for each KPI dimension
• Computed revenue aggregates and % distributions by gender, state, channel, age
• Created derived metrics: fulfilment rate, channel share, gender-age cross-tab
3.4  Dashboard
• Single-sheet interactive dashboard with 6 chart panels
• Slicers: Month, Channel, Category — all charts update simultaneously
• Chart types: Bar (Orders vs Sales), Pie (Gender, Status, Channels), Line (trend), Horizontal Bar (States, Age-Gender)

4. Dashboard Insights

Dimension	Insight	Recommendation
Orders vs Sales	March is the peak month; steady decline Jun–Dec	Run Q1 promotions; re-engage in Oct–Dec
Gender Split	Women = ₹13.56L (64%); Men = ₹7.61L (36%)	Women-first product strategy & ads
Order Status	92.2% delivered; cancelled 2.7%; returned 3.4%	Investigate return hotspots by state
Top States	Maharashtra ₹29.9L, Karnataka ₹26.5L, UP ₹21.0L	Warehouse & express delivery focus
Age × Gender	Adult women 34.6%; Teen women 21.1%	Create loyalty programme for adult women
Channels	Amazon 35.5%; Myntra 23.4%; Flipkart 21.6%	Negotiate better placement on Amazon

5. Key Project Insights
Women Drive Revenue
Women account for 64% of total sales. Adult women (30–49) alone contribute ~35% of all orders — the single most valuable segment.
Seasonal Peak is Q1
Sales peak in March (₹19.28L) and taper through the second half of the year. November–December show the lowest volumes despite being festive months — suggesting missed campaign opportunities.
Amazon is the Dominant Channel
Amazon drives 35.5% of all orders. Flipkart and Myntra together add another 45%, making these three platforms responsible for ~80% of revenue. Nalli and Meesho are niche but relevant for premium segments.
Geographic Concentration
Top 5 states (Maharashtra, Karnataka, Uttar Pradesh, Telangana, Tamil Nadu) account for the majority of revenue. This concentration enables targeted fulfilment investment while highlighting growth potential in Tier 2 markets.
Fulfilment is Strong
A 92.2% delivery rate is healthy. Cancellations (2.7%) and returns (3.4%) are the primary leakage points and are worth investigating by channel and geography.

6. Final Conclusion
The Vrinda Store 2022 dashboard reveals a clear strategic picture: target adult women aged 30–49 on Amazon and Myntra, front-load campaigns in Q1 (Jan–Mar), and concentrate logistics investment in Maharashtra, Karnataka, and Uttar Pradesh.

Three priority actions:
• 1.  Launch a women-focused loyalty/retention programme targeting the 30–49 age band on Amazon.
• 2.  Run dedicated Q4 festive campaigns (Oct–Dec) to recover the second-half revenue dip.
• 3.  Investigate return and cancellation root causes — even a 1% improvement in fulfilment rate yields ~₹2L additional revenue annually.

This project demonstrates end-to-end data analytics in Excel — from raw data cleaning through pivot-based modelling to an interactive, slicer-driven dashboard ready for business stakeholders.
