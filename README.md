# VBA_Challenge
## Overview of the project
The project was an interesting analysis of stock prices using Visual Basic. I was provided with 2 years' worth of data to help Steve analyse green stocks for the year of 2018 and 2019. Through the course of the analysis I was able to learn different aspects of visual basics, conditional statements and loop statements which are widely used to automate repetitive tasks. The project also gave a fundemantal udnerstanding of macros and to coding using VBA.  

As part of the project and the module, the key was to be able to identify tickers and perform analysis on various tickers to ensure Steve was able to invest in the best possible stock for his parents.  

Key things learned
1. Different datatypes within VBA
2. Creating a variable and assigning dataypes to the variable
3. Conditional statements and for loops
4. Making VBA user-firendly by providing buttons and other visual ways for people to interact with the code without having to read them

## Analysis
### 2017 vs 2018 price analysis
2018 was a bad year overall for these stock tickers. **10 of the 12 stocks analysed had lost value and 3 of them had even lost over 40%**

Key points to note from 2018
1. ENPH and RUN were the only stocks which gained value and almost doubled in price
2. Both these stocks had high total daily volumes as well **_(over 500,000)_**
- However we must be careful as there is no general trend between total volume and return  

![2018 analysis](VBA_Challenge_2018.png)

2017 on the other hand was a good year for these stocks. **11 out of the 12 stocks analysed had a positive return and 4 of these stocks more than doubled in price**

Key points to note from 2017
1. TERP was the only stock which lost value
2. DQ almost tripled in price and might not be the best investment at this point as it is overpriced  

![2017 analysis](VBA_Challenge_2017.png)


**Takeaway from both years: These stocks are volatile and we should wait for stability before investing in any of these stocks. At a layman level this leads us to believe that 2018 was more a correction for these stocks and the future year prices might be a bit more stable compared to 2017 and 2018**


###Original Vs Refactored Code performance:

The original code worked well and helped us understand the workings of VBA, however the code had us loop through indivdual values of starting and ending price every time which hindered code performance.
With the refactored code, we declared different arrays and removed the nested nature of the for loops which considerably increased code performance. The execution time with the re-factored code dropped was 1.3 seconds below the actual code. _The refactored code runtimes are in the screenshots within the analysis section_

**2017 and 2018 run-times before refactoring**  
![2017 code time](VBA_Old_Code_time_2017.PNG)
![2018 code time](VBA_Old_Code_time_2018.png)

##Summary
###Advantages and disadvatanges of refactoring code
**Advantages**
1. Improving speed of code execution
2. Improving resource requirements, thereby helping manage server costs etc.
3. Ability to think outside the box and reduce complexities  

**Disadvantages**
While there are no disadvantages per-se, one important thing is to ensure the logic of a code works properly before thinking about reducing complexities and making the code easier to run.

###How do these apply to refactoring the original script

With the refactored code I
1. Cleaned-up the for loops to improve processing speed
2. Used arrays and declared variables in the array which helped in better more efficient data storage as opposed to resetting the values every time

That said, the intial code is still helpful in understanding the logic and was more easily readable.

The inital code helped in
1. Understanding the logic of conditionals how the loops worked
2. Incremented the values within nested for loops which helped in getting an understanding of the logic here as well

**These helped in reducing the run-time of code by almost 1.3 s as you can see in the above screenshots**





