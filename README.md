📊 Amazon Sales Data Analysis
This project is a comprehensive data analysis of Amazon sales using Python. The aim is to clean, process, and visualize the sales data to derive meaningful business insights and identify trends related to quantity sold, product categories, shipping locations, and customer behavior.

🧰 Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Jupyter Notebook

📁 Dataset
The dataset includes:
Sales data from Amazon
Fields such as Date, Qty, Category, Size, Courier Status, ship-state, ship-postal-code, etc.

🧼 Data Cleaning Steps
Dropped irrelevant columns (New, PendingS)
Removed null values
Converted data types (e.g., ship-postal-code to int, Date to datetime)
Renamed columns for clarity

📈 Exploratory Data Analysis (EDA)
Several visualizations were generated to understand the data better:
Bar plots of quantity sold by product size
Count plots for courier status and order status
Histograms for product sizes and categories
Pie chart for B2B vs. B2C distribution
Scatter plot of category vs. size
State-wise distribution of shipping locations

📌 Key Insights
Certain sizes dominate in terms of quantity sold, indicating popular product dimensions.
Courier status is strongly linked with delivery success and can help pinpoint logistics issues.
A wide variety of product categories exist, but a few drive most of the volume.
B2C orders dominate, but B2B still forms a significant part of the business.
Orders are concentrated in a few key states, which may be important for regional logistics optimization.

✅ Conclusion
The Amazon Sales Data Analysis revealed several critical insights:
Product Size Trends: A few sizes significantly outperform others in terms of sales volume, which can guide inventory and procurement decisions.
Delivery Optimization: Courier status analysis showed how order delivery success correlates with order status, suggesting room for operational improvements.
Category Distribution: Certain categories see more frequent orders, which can inform marketing and product focus.
Geographical Focus: A handful of states make up the bulk of shipments, indicating priority regions for logistics and customer service investments.
Customer Type Split: The balance between B2B and B2C orders reflects a hybrid sales model, each needing tailored strategies.

