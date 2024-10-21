# Insights-for-Global-Electronics
Problem Statement
As part of Global Electronics' data analytics team, the goal is to conduct a comprehensive Exploratory Data Analysis (EDA) to uncover valuable insights from the company’s data. The goal is to provide actionable recommendations that can enhance customer satisfaction, optimize operations, and drive overall business growth. Global Electronics, a leading retailer of consumer electronics, has provided you with several datasets containing information about their customers, products, sales, stores, and currency exchange rates. The company seeks to leverage this data to better understand their business and identify areas for improvement.

Business Use Cases
By analyzing Global Electronics' customer, product, sales, and store data, one can aim to identify key insights that will enhance marketing strategies, optimize inventory management, and improve sales forecasting. This will help tailor marketing campaigns, develop better products, plan effective promotions, and decide on store expansions and optimizations. Additionally, understanding the impact of currency exchange rates on sales will allow for better international pricing strategies. Overall, these insights will help Global Electronics increase customer satisfaction and drive business growth.

#Tools Used

• Jupyter Notebook

• IDE- Visual Studio Code

• Python, Pandas, Matplotlib, Seaborn - for Data cleaning and EDA(Exploratory Data Analysis)

• My SQL - Database to store and retrieve cleaned data

• Power BI - Visualization

#Data Sources

• Customer data (customers.csv): Contains information about customers such gender, D.O.B, and demographics, used for analyzing customer behavior and segmentation.

• Sales data (sales.csv): Includes records of transactions, such as number of sales, product ID, it's quantities, order date, delivery date, store ID, and currency essential for understanding sales patterns and performance.

• Products data (products.csv): Lists product details including IDs, names, categories, subcategory, unit prices, unit costs helping to analyze product performance and trends.

• Stores data (stores.csv): Provides information on store locations, IDs, and attributes, useful for examining geographic sales performance and store-related analysis.

• Currency exchange rates data (exchangerates.csv): Contains historical exchange rates between different currencies, crucial for analyzing sales and financial data in a global context.

#Approach
• Data Cleaning and Preparation:

Checking for missing values and handle them appropriately. Converting data types where necessary (e.g., dates, numerical values). Merging datasets where necessary for analysis (e.g., linking sales data with product and customer data).

• Load Data:

Inserting the preprocessed data into an SQL database by creating relevant tables for each data source.

• Power BI Visualization

Connecting SQL to Power BI/Tableau, import the data, and create interactive dashboards.

• Develop SQL and Calculations

Formulating and executing SQL and calculations in Power BI to extract key insights from the data.

#Analysis Steps:

#Customer Analysis

• Demographic Distribution: Analyze the distribution of customers based on gender, age (calculated from birthday), location (city, state, country, continent).

• Purchase Patterns: Identify purchasing patterns such as frequency of purchases, and preferred products.

• Segmentation: Segment customers based on demographics and purchasing behavior to identify key customer groups.

#Sales Analysis

• Sales by Product: Evaluate which products and categories are the top performers in terms of revenue generated.

• Sales by Store: Assess the performance of different stores based on sales data.

• Order Volume over Years: Examine the sales history over month and years.

#Product Analysis

• Product Popularity: Identify the most popular products based on sales data.

• Profitability Analysis: Calculate profit margins for products by comparing unit cost and unit price.

• Category Analysis: Analyze sales performance across different product categories and subcategories.

#Store Analysis

• Store Performance: Evaluate store performance based on sales, size (square meters), and operational data (open date). • Geographical Analysis: Analyze sales by store location to identify high-performing regions.

#Findings and Recommendations

The analysis results are summarized as follows:

Customer Demographics:
• The gender distribution appears to be evenly balanced with male and female customers represented more or less equally. This suggests that the retailer's products and marketing strategies may be appealing to both genders.

• The customer base is predominantly composed of individuals aged 60 and above, and the youngest individuals aged between 20 and 29, represents a significantly smaller portion. The remaining age groups, spanning from 30 to 59 years old, exhibit a relatively uniform distribution. This distribution suggests a diverse customer base with a substantial portion of older individuals, potentially indicating a mature market segment.

• The majority of customers are from North America followed by Europe and Australia. Toronto is leading amongst other cities along with other cities in the US, followed by the ones in Canada including Montreal, Calgary and Atlanta. All of these cities located in Nourth America, confirms the previous observation.

Correlation of various features with Revenue:
• Both males and females within the same age group show similar purchasing patterns across different product categories. This indicates a gender-neutral trend in purchasing behavior, suggesting that gender may not be a significant factor influencing product preferences among customers.

• Regardless of age and gender, customers demonstrate consistent preferences for various product categories. The 'normalized purchase frequency heatmap' shows same correlation. This consistency suggests that product preferences are not strongly correlated with demographic factors such as age or gender but indicating universal appeal of certain products across diverse customer segments.

• Analysis of the 'normalized purchase frequency heatmap' shows highest purchase of purchase computers, followed by cell phones, music, movies, and audio books. These product categories appear as the most favored among customers of all age groups and genders, indicating their widespread appeal and demand among the customer base.

• However, the purchase frequency heatmap highlights a trend among customers aged 60 and above, who demonstrate higher purchasing frequency compared to other age groups. This observation can be attributed to the larger size of this age group, suggesting that while their purchasing frequency may be higher, it may not indicate a stronger preference for specific products over other groups.

• Revenue shows almost negligible/no correlation with 'Store Age' and 'Store Size'. This suggests that revenue or profit does not vary with these 2 parameters.

Top Leading Brands, Products and Categories:
• Leading Brands: Contos dominates followed by Wide World Importers, Southridge Video and Adventure Works. Contoso's lead indicates strong brand recognition and customer preference. Marketing and product quality likely contribute to this brand's success.

• Top Category and Subcategory: Computers are the most popular category followed by Cell Phones. Bluetooth Headphones is a subctegory in demand. This indicates strong preference for technology and electronics among Customers. Next in the list is Music, Movies and Audio Books which suggests a substantial market for entertainment content.

• Top Products: The highest-selling products are desktop computers from "Adventure Works Desktop" and "WWI Desktop" series.The focus on desktop computers suggests a high demand for these products among customers, potentially due to specific features or competitive pricing.

Sales and Delivery Trend:
• The sales trend shows a decline in April every year. However, it gradually increased, peaking in Dec continuing onto Jan and Feb in the subsequent year.

• Overall, there is an upward trend since 2017 until it reached its peak in 2020. Post April 2020, it is visible that sales has not seen its expected upward trend.
