# stock_classification
![image](https://img.shields.io/badge/Lifecycle-Work%20in%20Progress-yellow)

An attempt to better understand stock trading by using various unsupervised learning methods to classify stocks into groups to focus my energy on learning group behaviors.


# Data 
 - I pulled historical stock data from [kaggle](https://www.kaggle.com/dgawlik/nyse?select=prices.csv) for stock prices from 2010 to 2016
 - The data is in the form of CSV
 ![image](https://cdn.discordapp.com/attachments/734534633081012358/734534702068793384/Stock.PNG)
  - There were some stocks whose data did not start in 2010 or end in 2016 (Due to being started, closing, or other reasons) so these were disgarded. Could be something to look at later, but for now... ¯\(ツ)/¯
  
 # Conclusions
 
  - Stocks are unpredictable and grouping them by their daily activity can be problematic when understanding a stock. 
    - Changing the time window might be a better approach due to seasonality and GDP swings.
