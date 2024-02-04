This comprehensive data analysis project delves into the historical performance of Bitcoin, a decentralized digital currency that has captivated the financial world. 
The dataset utilized contains a rich array of information, including Open, High, Low, and Close prices, along with Volume and Market Cap metrics, spanning various dates.

The primary objective is to uncover meaningful insights from this dataset, shedding light on trends, patterns, and potential correlations within Bitcoin's price dynamics. 
Through meticulous exploration, cleaning, and analysis, the project aims to equip stakeholders with a deeper understanding of Bitcoin's historical behavior.

Table of Contents:
1. Introduction
2. Project Setup
3. Data Source
4. Data Cleaning
5. Data Exploration
6. Time Series Analysis
7. Moving Averages
8. Correlation Analysis
9. Tableau Visualizations
10. Sharing and Documentation

Introduction:
Bitcoin, a decentralized digital currency, has gained significant attention. 
This project aims to analyze historical Bitcoin price data to understand trends, patterns, and potential correlations.

Project Setup:- Tools and Technologies
Jupyter Notebook
Python
Pandas for data manipulation
Matplotlib and Seaborn for data visualization
Tableau for advanced visualizations

Data Source:
The dataset was obtained from Kaggle.

Data Cleaning:
The dataset underwent cleaning processes to handle missing values, convert data types, and ensure consistency.
#sample code for cleaning
print(df.isnull().sum())

Data Exploration:
Explored the dataset to understand its structure and relationships. Analyzed key statistics and visualized trends.

Sample Questions Explored
What are the highest and lowest Bitcoin prices?
How does the trading volume change over time?

Time Series Analysis
Utilized time series analysis to visualize Bitcoin's price trends over time.

Moving Averages
Applied moving averages to smooth out price trends and identify potential patterns.

Correlation Analysis
Calculated correlation matrices to identify relationships between variables.

Tableau Visualizations:
Leveraged Tableau for more advanced visualizations, including bar charts, line graphs, and heatmaps.

Visualizations Created:
Bar chart highlighting days with high trading volume.
https://public.tableau.com/views/Bitcoin_Volume_Analysis/Sheet2?:language=en-US&:display_count=n&:origin=viz_share_link

Line chart illustrating the percentage change in Bitcoin prices.
https://public.tableau.com/views/PricePercentageChange/Sheet1?:language=en-US&:display_count=n&:origin=viz_share_link

 Bar chart to show Open, High, Low, and Close prices for each day in a candlestick chart.
 also, color coded the bars based on whether the Close price is higher or lower than the Open price.
 https://public.tableau.com/views/Bitcoin_Candlestick_Chart/Sheet1?:language=en-US&:display_count=n&:origin=viz_share_link

Thank you!!!
