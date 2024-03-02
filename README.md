🎯 Objective:
📌 Vrinda Store wants to create an annual sales report for 2022 so that Vrinda can understand their customers and grow more sales in 2023.

🎯 Questions to solve:
1️⃣ Compare the sales and orders using single chart.
2️⃣ Which month got the highest sales & order?
3️⃣ Who purchased more men or women in 2022?
4️⃣ What are different order status in 2022?
5️⃣ List top 10 states contributing to the sales?
6️⃣ Relation between age & gender based on number of orders.
7️⃣ Which channel is contributing to maximum sales?
8️⃣ Highest selling category.

🔎 Data cleaning:
Checking each column by applying filter in order to check the data type whether it is text, Number or Date type. Checking for null values in each column and identifying the duplicates.

⚙ Data processing:
✅ Creating new column called Age group by using "IF CONDITION", IF(E2>=50,"Senior", IF(E2>=30,"Adult","Teenager"). This Age group column categorized into Senior, Adult, & Teenager.
✅ Again creating new column "month" from extracting date column by using TEXT function (=TEXT(G2,"mmm").

📈 Data analysis:
💡 Creating pivot table from cleaned and processed data.
💡 Creating various types of charts like bar chart, pie chart, etc. to gain the insights.

⭐ Insights:
1️⃣ Women are largest buyer as compare to men about (~64%).
2️⃣ Maharashtra, Karnataka and Uttar Pradesh are the top 3 states (~35%).
3️⃣ Adults age group (30-49 yrs.) is contributing around (~50%).
4️⃣ Amazon, Flipkart & Myntra are among the highest selling category (~80%).

📋 Conclusion:
✳ Target women customers of age group (30-49 yrs.) living in Maharashtra, Karnataka & Uttar Pradesh by showing ads/offer/coupons available on Amazon, Flipkart & Myntra.
