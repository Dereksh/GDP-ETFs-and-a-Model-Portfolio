# Model Portfolio![stock market](https://g.foolcdn.com/editorial/images/518050/stock-market-buy.jpg)

# Proposal
Predict future portfolio returns by 
(1) performing a Monte Carlo Simulation of GDP based on the historical data dating back to 1941 and 
(2) analyzing its correlation to the following indices: S&P500  * Gold  * DJIA  * NASDAQ  * 10Y UST
                      
# Analysis: 

   ## "Flight to Safety"  
   
   * Calculate correlation & Plot heat map of each of the equity markets.
  
      
![image](https://user-images.githubusercontent.com/70820754/99757381-7aec9a80-2aac-11eb-8d97-7d51d69e39bd.png)
![image](https://user-images.githubusercontent.com/70820754/99757602-fbab9680-2aac-11eb-9a94-899f02ca6eb4.png)

   * Plot Correlation of Gold to S&P500
   
 ![image](https://user-images.githubusercontent.com/70820754/99760960-2fd58600-2ab2-11eb-99ab-bfdfe14fd247.png)

   ## Monte Carlo simulation
   * Load and Read csv file & API's
   * Plot Historical Closing Prices
   * Calculate Log Returns
   * Plot Log Returns
   * plot histogram
   * plot monte carlo simulation
   
![image](https://user-images.githubusercontent.com/70820754/99760573-3dd6d700-2ab1-11eb-8671-afcbfe64aeca.png)
![image](https://user-images.githubusercontent.com/70820754/99760599-4b8c5c80-2ab1-11eb-9f96-cf6c7297f86b.png)

   ## Linear Regression 
   
   * Regress each asset class against GDP to see how each reacts to changes in GDP
   * Plot linear regressions
   
![image](https://user-images.githubusercontent.com/70820754/99759835-411d9300-2ab0-11eb-9b8f-c765ec446357.png)
![image](https://user-images.githubusercontent.com/70820754/99760195-627e7f00-2ab0-11eb-89df-554e442d931e.png)

![image](https://user-images.githubusercontent.com/70820754/99760221-71653180-2ab0-11eb-9a2f-f5aea3d93f05.png)
![image](https://user-images.githubusercontent.com/70820754/99760361-c86b0680-2ab0-11eb-8da6-d94d5ecd837b.png)

   ## Portfolios
   
   * Simulate different model portfolios to find expected return based on a GDP Monte Carlo simulation.
  
# Technical Requirments
  
   * Create a Jupyter Notebook describing the data exploration and cleanup process. 
   * Illustrate the final data analysis on Jupyter Notebook. 
   * Save PNG images of visualizations in .readme file.
   * Use one new Python library that hasn't been covered in class. 

# Files
  * [GDP Data.csv](Data/gdp_data.csv)
  * [Market Data.csv](Data/market_data_modified.csv)
  * [Market Data Indexed.csv](Data/Market_Data_Indexed.csv)
  
 


    ## Resources
    
