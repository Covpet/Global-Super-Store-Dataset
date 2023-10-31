
# Gloabal Superstore

## Table of Content
- [Project Overview](Project.Overview)
- [Data Source](Data.Source)
- [Tools](Tools)
- [Project Structure](Project.Structure)
- [Data Cleaning](Data.Cleaning)
- [Exploratory Data Analysis(EDA)](Exploratory.Data.Analysis (EDA))
- [Data Insight](Data.Insight)
- [Results/Findings](Reslts/Findings)
- [Recommendation](Recommendation)
- [Refrence](Reference)


## Project Overview
---
Global Superstore, headquartered in New York, stands as a prominent e-commerce retailer with an extensive array of products, committed to becoming the ultimate one-stop shopping destination for its global customer base. Catering to customers from 147 different countries, the superstore grants access to a diverse selection of more than 10,000 products. This all-encompassing range encompasses three primary categories: office supplies (such as staples), furniture (inclusive of items like chairs), and technology products (showcasing smartphones).
The purpose of this project is to aid Global Superstore in the analysis and extraction of valuable insights from the Superstore dataset. These insights are aimed at equipping the management with the knowledge necessary for making well-informed decisions that enhance overall performance and profitability.

## Data Soure
---
This dataset was provided at the conclusion of the training program conducted by Digitaley Drive as the final project. Below is the link to the data set


[Download here](https://docs.google.com/spreadsheets/d/1nxESpFzWjlGDMGDVLH69xmDzIl9l6OEq/edit#gid=633280281)


## Tools
- Power query - Cleaning and Modeling
- Power Bi - Visualization
- Github - Documentation


## Project Structure
 This project was executed following the subsequent process.

- Data Collection

In the first stage of the project, we focus on obtaining the Global Superstore dataset. The academy supplied us with this dataset as a result of our successful training completion.

- Data Cleaning

The Data Cleaning phase stands as a crucial component of any data analysis project. In this segment, I methodically describe the steps and methods utilized to guarantee the dataset's accuracy, dependability, and its readiness for analysis within Power BI. This procedure involves validating the data, eliminating duplicates, managing missing values, and rectifying any irregularities or discrepancies found in the original data. The objective is to generate a tidy and well-organized dataset that serves as the foundation for our insights and visualizations, accomplished through the use of Power Query.

- Data Visualization

Data Visualization plays a pivotal role in the realm of data analysis. This stage encompasses the creation of an interactive and informative dashboard using Power BI. Through this dashboard and the associated reports, I provide a comprehensive perspective on the Global Superstore sales report. My visualizations provide a more profound insight into the essential performance metrics, profitable countries, lucrative regions, subcategories, and various other metrics. By using charts, graphs, and tables, I breathe life into the data, making it easy for stakeholders to swiftly grasp the insights extracted from the dataset.
 
- Data Documentation

Following the conclusion of the analysis, I recognize the significance of effectively conveying the discoveries and suggestions. For this purpose, I've established an extensive documentation repository on GitHub. This documentation serves as a valuable reference that elucidates the insights I've uncovered from the dataset, providing comprehensive explanations of these insights and delivering a thorough overview of the recommendations. It equips the leadership of Global Superstore with the insights necessary to make informed decisions with the goal of enhancing overall performance and profitability.

## Data Cleaning 
I brought the dataset into Power Query for the purpose of cleaning and transforming the data. This dataset consisted of three tables: Orders, People, and Returns. During this procedure, I noticed that the 'Postal code' field in the Order table contained approximately 80% Null values. I replaced these Null values with '0.' Furthermore, I combined the Returns table with the Order table using the VLOOKUP function in Microsoft Excel. In addition, I conducted a comprehensive validation and quality check on all rows and columns within the dataset to ensure its accuracy and integrity. Once I confirmed that the dataset adhered to the necessary quality standards, I concluded the data transformation process and loaded it into Power BI for further analysis.



## Exploratory Data Analysis(EDA)
Exploratory Data Analysis (EDA) is a crucial step in our approach to the Global Superstore dataset. It involves diving deep into the data to answer essential questions that underpin our analysis and decision-making. These questions are 
  
Question 1.

a) What are the three countries that generated the highest total profit for Global Superstore in 2014?

b) For each of these three countries, find the three products with the highest total profit. Specifically, what are the products’ names and the total profit for each product?

Question 2.

a) Identify the 3 subcategories with the highest average shipping cost in the United States.

Question 3.

a) Assess Nigeria’s profitability (i.e., total profit) for 2014. How does it compare to other African countries?

b) What factors might be responsible for Nigeria’s poor performance? You might want to investigate shipping costs and the average discount as potential root causes.

Question 4.

a) Identify the product subcategory that is the least profitable in Southeast Asia.

b) Is there a specific country in Southeast Asia where Global Superstore should stop offering the subcategory identified in 4a?

Question 5.

a) Which city is the least profitable (in terms of average profit) in the United States? For this analysis, discard the cities with less than 10 Orders. b) Why is this city’s average profit so low?

Question 6.

a) Which product subcategory has the highest average profit in Australia?

Question 7.

a)Who are the most valuable customers and what do they purchase?



## Data Analysis 

Within the financial landscape of Global Store for the year 2014, three countries emerged as significant drivers of profit: the United States, China, and India.

The United States stood out with an impressive profit of $39,936.85, underscoring its crucial role as a major revenue generator for the company.

China secured the second position, making a substantial contribution of $8,421.33 to the overall profits. The rapid growth of the Chinese market played a pivotal role in achieving this.

India, in the third position, also made a notable contribution with a profit of $7,330.95. This emphasizes the increasing influence of the Indian market on Global Store's financial performance.

Collectively, these three countries played a central role in shaping the profitability of Global Store in the year 2014.

- Here is a breakdown of the countries and products that have contributed the most to our profitability


*Most Profitable product in United States and their profits*

|Product Name |Profit|
|----------------|-------------------|
|canon imageCLASS 2200 Advanced copier|25,199.993|
|fellowes PB500 electric plastic Comb Binding Machine with Manual Bind|7,753.04 |
|Hewlett Packard Laserjet 3310 Copier| 6,983.88 |
|Total| 39,936.85|

*Most Profitable Product In China and their Profits*

|Product Name |Profit|
|------------------|--------------------|
|Sharp wireless Fax, Digital|2,894.10|
|Hp Copy Machine, Color|2,855.13|
|Samsung Smart Phone, VolP|2,672.10|
|Total|8,421.33|



|*Most Profitable Product In India and their Profits*

|Product Name |Profit|
|--------|--------|
|Sauder Classic Bookcase,Traditional        |2,903.58|
|Apple Smart Phone, with Caller ID          |2,817.99|
|Cisco Smart Phone with Caller ID   |1,609.38|
|Total|7,330.95|


*The 3 subcategories with the highest average shipping cost in the United States*

To gain valuable insights into the shipping dynamics within the United States and understand how these specific product groups impact the business's financial performance, I needed to delve deeper.

When examining shipping costs in the United States, it's intriguing to discover that three particular subcategories stood out due to their high average shipping expenses. These subcategories include Chairs, Phones, and Storage, and they played a central role in shaping the dynamics of shipping costs.

Among these, Chairs took the lead as the subcategory with the highest average shipping cost, registering an impressive 58.43%. Phones secured the second position with an average shipping cost of 41.02%. The popularity and demand for phones, in combination with their shipping costs, introduce an intriguing aspect to the overall profitability analysis.

Finally, the subcategory of Storage emerged as the third highest, with an average shipping cost of 27.31%. The cost of shipping these items stands as a significant factor to consider when assessing profit margins and making logistical decisions.


*Nigeria’s profitability  for 2014. How does it compare to other African countries?*


To gain valuable insights into the shipping dynamics within the United States and understand how these specific product groups impact the business's financial performance, I needed to delve deeper.

When examining shipping costs in the United States, it's intriguing to discover that three particular subcategories stood out due to their high average shipping expenses. These subcategories include Chairs, Phones, and Storage, and they played a central role in shaping the dynamics of shipping costs.

Among these, Chairs took the lead as the subcategory with the highest average shipping cost, registering an impressive 58.43%. Phones secured the second position with an average shipping cost of 41.02%. The popularity and demand for phones, in combination with their shipping costs, introduce an intriguing aspect to the overall profitability analysis.

Finally, the subcategory of Storage emerged as the third highest, with an average shipping cost of 27.31%. The cost of shipping these items stands as a significant factor to consider when assessing profit margins and making logistical decisions.


*The least product subcategory profitable in Southeast Asia and the specific country in Southeast Asia where Global Superstore should stop offering the subcategory with the least profit*

The analysis covers a set of Southeast Asian countries, including Malaysia, Indonesia, Philippines, Thailand, Vietnam, Cambodia, Singapore, and Myanmar. In these countries, a diverse array of subcategories were available, encompassing Phones, Copiers, Appliances, Bookcases, Machines, Chairs, Storage, Binders, Furnishing, Labels, Art, Fasteners, Paper, Supplies, Accessories, and Tables.

Interestingly, among all these subcategories, 'Tables' emerged as the least profitable in the Southeast Asian region, resulting in a negative profit of -19k. On the contrary, 'Phones' proved to be the most profitable subcategory, yielding a profit of 13k.

Considering the significant loss associated with 'Tables' in Indonesia, it might be advisable to reconsider the supply of this subcategory by Global Superstore to prevent further financial setbacks.


*Which city is the least profitable (in terms of average profit) in the United States? For this analysis, discard the cities with less than 10 Orders. b) Why is this city’s average profit so low?*

Among the cities in the United States, Concord stands out due to its lowest profit, resulting in a significant loss of •23.18. A closer examination of the chart uncovers that Concord grapples with elevated shipping costs combined with limited discounts. The high shipping expenses can dissuade customers from making purchases because of the higher selling prices, prompting them to seek local alternatives. Conversely, offering minimal discounts may discourage repeat buying, leading to financial deficits.

To enhance profitability in Concord, it is advisable for the company to reassess its pricing strategy. This might involve exploring ways to reduce shipping costs or providing more enticing discounts to incentivize customers to make more frequent purchases. A deep understanding of the local market dynamics and customer preferences in Concord is essential in formulating a strategy that can reverse the current situation and reinstate profitability.



*Which product subcategory has the highest average profit in Australia?*
Australia provides a wide range of subcategories, including Phones, Copiers, Appliances, Bookcases, Machines, Chairs, Storage, Binders, Furnishing, Labels, Art, Fasteners, Paper, Supplies, Accessories, and Tables. Remarkably, 'Appliances' emerges as the foremost subcategory in Australia, having accrued a significant total of 139.

*Who are the most valuable customers and what do they purchase?*

Below is a list of our most profitable customers and what they purchase from us


|Name of Customer|Products they purchased|Country|
|----------------|-----------------------|-------|
|Tamara Chand|Canon imageCLASS 2200 Advanced Copier|United State|
|Raymond Buuch|Canon imageCLASS 2200 Advanced Copier|United State|
|Hunter Lopez|Canon imageCLASS 2200 Advanced Copier|United State|
|Adrian Barton|GBC Ibimaster 500 Manual ProClick Binding System|United State|
|Sanjit Chand|Ibico EPK-21 Electric Binding System|United State|
|Patrick Jones|Hoover Stove, Red|Italy|



## Findings

Throughout the analysis, I have unveiled several noteworthy insights and observations:

- Profit-Driving Countries: The primary contributors to the company's profitability have been the United States, China, and India.

- Shipping Costs and Discount Dynamics: The presence of high shipping costs and substantial discounts in specific countries, like Nigeria, has led to considerable financial setbacks. On the other hand, South Africa has managed to maintain substantial profits despite elevated shipping expenses.

- Subcategory Performance in Southeast Asia: Within the array of subcategories offered in Southeast Asia, 'Tables' proved to be the least profitable, while 'Phones' emerged as the most lucrative. The negative profit associated with 'Tables' in Indonesia suggests the need to reconsider its supply in that particular market.

- Subcategory Performance in Australia: Australia boasts a diverse range of subcategories, with 'Appliances' shining as the top-performing subcategory, yielding a total profit of 139.

These findings provide valuable insights into the financial performance of the company, the influence of shipping costs and discounts, and the performance of different products and regions. Subsequent analyses and strategic actions can be grounded in these findings to enhance profitability and decision-making.

## Recommendations

Here are some comprehensive suggestions aimed at enhancing the performance, customer service, and profitability of Global Superstore:

- Shipping Costs and Discounts: Examine the ramifications of high shipping costs and substantial discounts in specific regions, such as Nigeria. Consider fine-tuning pricing and discount strategies to strike a balance that ensures profitability.

- Subcategory Strategy: Assess the profitability of subcategories across different markets. If specific subcategories consistently result in losses, contemplate discontinuing or optimizing their availability in those regions.

- Market Emphasis: Given the profitability of countries like the United States, China, and India, contemplate expanding marketing and sales efforts in these markets to further enhance profitability.

- Customer Insights: Delve into the characteristics and behaviors of the most profitable customers to unearth patterns that can be leveraged to attract and retain similar customers.

- Product Mix: Evaluate the product assortment in Australia, with 'Appliances' performing strongly. Consider promoting or expanding offerings in this category if it aligns with your overarching business strategy.

- Data-Driven Decision-Making: Persist in utilizing data analysis and insights to inform business decisions and strategies. Regularly monitor and adapt to changing market dynamics to uphold and improve profitability.

- Pricing Strategy: Rigorously evaluate the impact of discounts and shipping costs across diverse regions. Adjust pricing strategies to maximize profitability while maintaining competitiveness.

By incorporating these recommendations into the operational and strategic framework of Global Superstore, the objective is to enhance performance, elevate customer satisfaction, and ultimately increase profitability. These actions should be underpinned by a dedication to data-driven decision-making and a steadfast focus on meeting customer needs.



## Reference 
[Link to Dataset](https://docs.google.com/spreadsheets/d/1nxESpFzWjlGDMGDVLH69xmDzIl9l6OEq/edit#gid=633280281)
