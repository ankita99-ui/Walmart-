<div align="center" style="border:2px solid #333; padding:20px; width:500px; margin:auto;">

<img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/Walmart_logo.svg" 
alt="Walmart Logo" width="300"/>

<font size='+3' color='#FFA500'><b>Sales Forecasting</b></font></div>







<font color="#FF8C00"><h2>Problem Statement:</h2></font>

A **<font color="#004080">Retail</font> <font color="#D4A669">Store</font>** that has multiple outlets across the country.

They are facing issues in managing the inventory - to match the demand with respect to supply.


<font color="#A04F0E"><h2>Dataset Information:</h2></font>

You are provided with the <font color="#8C593A">Weekly_Sales</font> data for their various outlets.

The **<font color="#004080">Walmart</font><font color="#FF8C00">.csv</font>** contains <font color="#264C4D">6435 rows</font> and <font color="#264C4D">8 columns.</font>

| Feature Name   | Description                                      |
|----------------|--------------------------------------------------|
| <font color="#264C4D">Stores</font>          | Store number                                     |
| <font color="#1B4E75">Date</font>           | Week of Sales                                    |
| <font color="#8C593A">Weekly_Sales</font>   | Sales for the given store in that week            |
| <font color="#992600">Holiday_Flag</font>   | Indicates if it is a holiday week                 |
| <font color="#D4A669">Temperature</font>    | Temperature on the day of the sale                |
| <font color="#004080">Fuel_Price</font>     | Cost of fuel in the region                        |
| <font color="#6A287E">CPI</font>           | Consumer Price Index                              |
| <font color="#FF5733">Unemployment</font>   | Unemployment Rate                                 |



<font color="orange"><h2>Objectives:</h2></font>

**Analysis**

  > Handle <font color="orange-red">missing values</font> in the dataset.
  
  > Conduct <font color="dark brown">Exploratory Data Analysis (EDA)</font>to reveal data patterns.
  
  > Identify and analyze <font color="dark brown">Outliers</font> to ensure data quality.
  
  > Perform <font color="dark brown">Statistical Analysis</font> for key insights.

**Various  INSIGHTS** 

   > * a.If the  <font color="blue"> Weekly_Sales </font> are affected by the <font color="reddish-orange"> Unemployment</font> Rate,
    * If YES - which Stores are <font color="bright orange "> suffering the most</font>?
   
   > * b.If the <font color="blue"> Weekly_Sales</font> show a <font color=" bluish-green "> Seasonal Trend</font>
     * When and what could be the <font color="bright orange"> timing and reasons</font>?
   
   > * c.Does<font color="orange"> temperature</font> affect the <font color="blue"> Weekly_Sales </font> 
   
   > * d. How is the <font color="rich purple"> Consumer Price Index (CPI) </font> affecting the <font color="blue"> Weekly_Sales</font> of various stores.
   
   > * e. <font color="Green"> TOP Performing</font> Stores based on historical data.
   
   > * f. The <font color="Green"> WORST Performing</font> Stores and how significant is the difference between the highest and lowest performing stores.

     
     
**Predictions**

> * Apply <font color="bluish-green">Predictive Modeling Techniques</font> to forecast Weekly_Sales.
    * Develop models to predict <font color="blue"> Weekly_Sales </font> for each store for the next 12 weeks.



 # Conclusion 

 - The main purpose of this study was to predictWalmart’s sales based on the available historic data and identify whether factors like temperature, unemployment, fuel prices, etcaffect the weekly sales of particular stores under study. This study also aims to understand whether sales are relatively higher during holidays like Christmas and Thanksgiving than normal days so that stores can work on creating promotional offers that increase sales and generate higher revenue.


- Based on the insights derived from the exploratory data analysis, it is evident that Walmart sales exhibit a direct correlation with both store size and holiday seasons. Furthermore, an intriguing observation was made regarding store types, with Type A stores standing out as the top performers in terms of generating sales for Walmart. 


- In examining the specified variables in this analysis, namely temperature, unemployment, CPI, and fuel prices, it was noticed that sales exhibit a marginal increase during favorable weather conditions and when fuel prices are reasonable. However, it's essential to note the cautious stance due to the study's reliance on a relatively limited training dataset. Upon closer inspection during exploratory data analysis, it became apparent that sales tend to experience a relative uptick in periods of lower unemployment levels. Conversely, based on the dataset provided for this study, no discernible correlation was found between sales and the CPI index. Once again, it's imperative to approach these observations with prudence, considering the need for a more expansive training dataset containing additional information for making robust claims.


# 1 . **Bakshi, C. (2020). Random forest regression.**
      https://levelup.gitconnected.com/random-forest-regression-209c0f354c84
     



2. **Bari, A., Chaouchi, M., & Jung, T. (n.d.). How to utilize linear regressions in predictive analytics.**
      https://www.dummies.com/programming/big-data/data-science/how-to-utilize-linear-regressions-in-predictive-analytics/



3. **Baum, D. (2011). How higher gas prices affect consumer behavior.**
     https://www.sciencedaily.com/releases/2011/05/110512132426.htm



4. **Brownlee, J. (2016). Feature importance and feature selection with xgboost in python.**
     https://machinelearningmastery.com/feature-importance-and-feature-selection-with-xgboost-in-python/
