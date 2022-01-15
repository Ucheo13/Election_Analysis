# Election_Analysis
## Overview of the Analysis
The purpose of this assignment is to refactor the code so that the code can loop through the entire spreadsheet and store values needed to construct a table that describes the 
return and total volume for each ticker.
## Results
Clearly, 2017 stocks outperformed 2018 stocks by a considerable amount. The return represents how much the stock value grew by the end compared to the start. The higher 
the return the better the stock performed. In most cases the difference in the percentages for each ticker is large. The only case that is similar in returns is ticker TERP. Where 
it has 2017’s -7.2% vs 2018’s -5.0%. The only case where 2018 outperforms 2017. In the starting price ticker, the values in 2017 were [19.47, 12.67, 19.85, 1.05, 33.54, 19.12, 
15.63, 5.59, 13.2, 6.85, 12.89, 2.7]. The ending price had [21.21, 16.86, 59.44, 2.41, 67.52, 24.06, 24.05, 5.9, 37.55, 8.43, 11.96, 4.05] in 2017. For 2018 starting prices were 
[21.14, 17.14, 62.57, 2.6, 70.43, 24.01, 25.06, 5.92, 38.05, 8.97, 11.81, 3.95]. For 2018 ending prices were [19.6, 14.34, 23.4, 4.73, 42.46, 19.05, 9.89, 10.89, 35.1, 4.97, 
11.22, 3.81]. I was able to obtain these prices by using the codes tickerStartingPrices(tickerIndex) = Cells(i, 3).Value and tickerEndingPrices(tickerIndex) = Cells(i,6).Value. 
This adds the relative prices for each corresponding ticker.

The code corresponding to 2018 ran very fast, executing in 0.0859375 seconds. The code in 2017 ran in 0.0859375 seconds as well.
![2017_Screenshot](https://user-images.githubusercontent.com/96452277/149602539-63d267e9-49f0-4b5d-96dd-003cd08dfe80.png)
![2018_Screenshot](https://user-images.githubusercontent.com/96452277/149602540-5cdd9020-46d8-4dc5-ac74-b13148b3624b.png)

## Summary
An advantage of refactoring code is that there are no new puzzles that need to be solved. You know the result you are looking for making the debugging a lot easier as you go 
along. A disadvantage is that you need to fully understand code that you haven’t visited in a while in order to refactor it. Requires good comments and spacing. In this project 
the most difficult thing was following along with the already made code so I could fill in the missing lines needed. 
An advantage of the new refactor code is that it is much more efficient and is able to run faster by looping through the entire spreadsheet one time and storing information in 
separate arrays. An advantage to the original is that it may be simpler to code avoiding the concept of multiple arrays but going through thousands of lines is terrible. Overall, 
the refactored code is what I would recommend.
