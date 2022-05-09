# Module 2 Challenge - Stock Analysis

## Overview of Project

### Purpose

The purpose of this analysis is to evaluate the performance of several stocks for Steve's parents. Our customer, Steve, would like a program that can evaluate Stock Volume, Opening Price, and Closing Price of a large dataset of stocks for any year.

## Results

### Results of Stock Performance between 2017 and 2018

The resulting analysis shows most 2017 stocks evaluated had positive

Our analysis shows most of the stocks evaluated for 2017 resulted in a positive return. However, most of the stocks evaluated for 2018 resulted in a negative return. Only stock tickers "ENPH" and "RUN" had consecutive positive returns, while only "TERP" had consecutive negative returns.

### Results of Execution Times for Original vs Refactored Script

Our analysis resulted in a large run time difference between the original and refractored scripts. The original program ran in 0.7734 seconds for an analysis of 2017 data and 0.7812 seconds for an analysis of 2018 data. Meanwhile, our refractored program ran in 0.1093 seconds for an analysis of the same 2017 data and 0.1093 seconds for an analysis of the same 2018 data. 
![VBA_Challenge_2017](https://user-images.githubusercontent.com/103288980/167322966-c0db7bcc-836b-4034-996d-f6e23bbed72f.PNG)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/103288980/167322969-2b9f1835-717a-4a1e-87df-39063379f589.PNG)

## Summary

### Advantages vs Disadvantages of Refactoring code in general

In summary, the principal advantage to refactoring code lies in greatly increasing the efficiency your program executes all of its calculations. While this difference seems small in our example, this could add up on much larger datasets. The main disadvantage to refractoring code is the additional time required to rewrite your subroutines.

### Advantages vs Disadvantages of Original vs Refactored Script

With respect to our program, our refractored script is much simpler than the original. We were able to remove the double loop and replace it with a series of loops instead. This resulted in a 7x faster runtime for our program.
![VBA_Challenge_Code](https://user-images.githubusercontent.com/103288980/167324422-9077478f-3d75-4b43-bfbe-762f7694eecf.PNG)
