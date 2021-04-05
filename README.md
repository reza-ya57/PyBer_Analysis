# PyBer_Analysis
# Analyze Stock Data
## Overview of Project
### Create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Result
### To refactor the code we used array variable and put all process in one loop to prevent multiple process and reduce the output time. 
- In this project we used array variable to record stock name and value so we assign a 12 size array regarding the total number of stocks.
```
Dim tickers(12) As String
        
```
- We determine three below arrays to collect the result and pass to the analyze report
``` 
    Dim tickerVolume(12) As Long
    Dim tickerStartingPrice(12) As Single
    Dim tickerEndingPrice(12) As Single
```
### We calculate total daily volume and yearly return for these 12 stocks on 2017 and 2018 based. Total daily volume can reveal how actively the stocks was traded and the yearly return shows the percentage increase or decrease in price from the beginning of the year to the end of the year.

![Comparison_Chart](https://github.com/reza-ya57/Stock-analysis/blob/main/Resources/Performanc_Stock_Comparison.png)

- By comparing 2017 and 2018 data analysis we can make below conclusion:
  - By looking at yearly return percentage we can say 2017 has better performance than 2018. In 2017 only one of the stock has negative return and the others have positive outcome. 
  - Based on 2018 result two stocks have a better performance and could be a candidate for investing, ENPH and RUN
### By refactoring the code we achieved a significant improvement in excecution times. You can see the executiontime of original code and refactored script below:

![Original_Excecution_Time](https://github.com/reza-ya57/Stock-analysis/blob/main/Resources/Excecutive_Time_2017_Original.png)
![Refactor_Excecution_Time](https://github.com/reza-ya57/Stock-analysis/blob/main/Resources/Excecutive_time_2017_Refactor.png)

## Summary
- Advantages of refactoring code
  - Have compact code
  - Reduce memory usage
  - Decrease required storage

- Disadvantages of refactoring code
  - Increase complexity of the code
  - Take more time 

#### To refactor the original code in this project we eliminate nonessential loop and used single loop for the whole process. This change caused more complexity to find the solution to run the script with one loop. In other hand by using this method the script line decreased and also the execution time improved. 
#### In summary refactoring is required for high performance script regarding to run the code in large data so we can have a significant improvement by reduce the memory usage and increase the execution time. 
