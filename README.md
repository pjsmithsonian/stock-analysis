# Stock Analysis

## Project Overview
We are undertaking this analysis to assist Steve in his efforts to find envrionmentally conscious stocks with solid returns to advice his parents to invest in.

## Results

### Stock Performance And Execution Times - 2017
All but one stock, TERP, had a good 2017. The best performers, however, were DQ (199%), ENPH (129%), and SEDG (184%). From this year alone, any of these would be a good investment. 

As for the script run time, the refactoring of the VBA code helped to reduce the time from .56 to .488. This improvement helps, especially as this script may be used on larger datasets.

![2017](/Resources/VBA_Challenge_2017.PNG)

### Stock Performance And Execution Times - 2018
Stocks in 2018 was not as good of a year. The only stocks with positive returns were ENPH (81.9%), and RUN (84%). From this year alone, any of these would be a good investment, but considering ENPH's performance over the past 2 years, this is likely the best investment for Steve's parents.

As for the script run time, the refactoring of the VBA code helped to reduce the time from .74 to .5.


![2018](/Resources/VBA_Challenge_2018.PNG)

## Summary

### Refactoring Code
Refactoring code has many positives. One of these positives is that it often will take code that is more rough around the edges and make it appear cleaner. This more readable code will allow someone that may come along later to be able to read the code, thus making the code more sustainable. Refactored code also will run more efficiently. This means not only running faster, but also utilizing fewer system resources. 

The one disadvantage to refactoring code is just keeping track of what you are doing. If you are replacing a hard-coded value with a variable, there is the risk that you could miss the value and end up getting results that you do not anticipate. This is not necessarily due to refactoring itself, but more a pitfall to avoid while refactoring.

### Applications to Our Analysis
In our analysis this refactoring of code improved the run time of the VBA script. While with such a small population this doesn't matter as much, this refactoring makes it to where if we were to increase our dataset dramatically, it would make sure that our code was more efficient than the original script. Also, the refactoring makes our script less reliant on hard-coded values and makes it more dynamic. This allows us to be more flexible when and if future updates are necessary. We will not have to touch as many portions of the script to make updates. 
