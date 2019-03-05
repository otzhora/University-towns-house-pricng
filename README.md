# Pandas and statistic practice project 

### Purpose 
In this projcet i will test hypothesis that university towns have their mean housing prices less eiffected by recessions

### Definitions 

1) A quarter is a specific three month period, Q1 is January through March, Q2 is April through June, Q3 is July through September, Q4 is October through December.

2) A recession is defined as starting with two consecutive quarters of GDP decline, and ending with two consecutive quarters of GDP growth.

3) A recession bottom is the quarter within a recession which had the lowest GDP.

4) A university town is a city which has a high percentage of university students compared to the total population of the city.
 
### Data 

 I get GDP data from Bureau of Economic Analysis, US Department of Commerce ([GDP over time](http://www.bea.gov/data/gdp/gross-domestic-product#gdp)). My hypothesis was tested on last recession period (see notebook for more). Information about university towns in USA i got from Wikipedia page. House pricing is from [Zillow research data site](https://www.zillow.com/research/data/).

### About testing 

I used [Student's t-test](https://en.wikipedia.org/wiki/Student%27s_t-test) for testing my hypothesis

Null-hypothesis: Uni-towns mean housing prices affected by economic recession in same way as other towns 

Hypothesis: Uni-towns mean housing prices less affected by economic recession

Choosen threshold for p-value is 0.01

### Results of t-test

`p-value = 0.004325214853511201` therefore we reject our Null-hypothesis

`t-statistic = -2.8540746960114096` negative t-stat means that uni-towns mean housing prices is greater then mean prices of other cities, so that means that they less affected by recession 

