# TAMU2021
TAMU 2021 
In this challenge, we are provided with 2 data sources: Knoema’s Data Atlas and Zepl’s US Stock Market for Data Science. Our mission is to find the connection between these two data sources, seeing if there’s a visible impact among environmental factors and stock prices
Knoema’s Data Atlas: https://www.snowflake.com/datasets/knoema-environment-data-atlas/
Zepl’s US Stock Market: https://www.snowflake.com/datasets/zepl-us-stock-market-data-for-data-science/

We first explored the data with basic and find the unique attributes of the columns from all the datasets. We found out that there’s no linking attribute between stock and environmental factors. Therefore, we decided to check the correlation between gas emissions (primarily N2O, CH4 and CO2) and stocks in the US. To do that, we normalized environmental data and stock data with “Z-score normalization” technique, based on mean and standard deviation values of the data.
 
After that, we created a function to merge environmental and stock datasets together and plot them in a graph to check their correlation. We formed our hypothesis for the datasets: “There’s a correlation between Energy sector and the gas emissions level in the United States.”
To prove our hypothesis, we explored some factors:
1.Energy sector and number of stocks for each category
2. N2O, CO2, and CH4 level from 2001 - 2021 in the United States
3.Stocks by industry
4.Correlation between energy sector stocks’ values vs gas emissions
5.Visualize to find the industry and gas emission that has the highest correlation

Final result:

![image](https://user-images.githubusercontent.com/59891364/137635572-9ce42ef8-613a-4cbe-90d5-e78691284346.png)

![image](https://user-images.githubusercontent.com/59891364/137635575-289509b0-c0ef-4241-b804-6b2cd1de6534.png)
