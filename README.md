# Research project
### Authors: [Denys Herasymuk](https://github.com/denysgerasymuk799) and [Yaroslav Morozevych](https://github.com/yarmor20)


## Aim

At this experiment we want to determine what political and economic features can correlate with Life Expectancy in different 
countries and to determine how deeply can they correlate to make some assumptions. We will do this experiment with several 
features and several countries, and after that we will make some assumptions.

## Choosing proper features

Dataset was taken from https://databank.worldbank.org/source/world-development-indicators#

Among 1440 features we have chosen only 42 that could correlate with life expectancy, but after analyzing gained data,
 we had to get rid of approximately 30 features because of the lack of data. However, we still have some features left 
 that could correlate with chosen parameter:

GDP (per capita), Expense (% of GDP), Tech Industry Progress, Employment Ratio, Waged Workers Ratio, Health Expenditure
and Binding Coverage.

## Choosing countries

For this experiment we have decided to choose the countries with high-income (USA, Japan), middle-income (Ukraine, Tajikistan)
 and low-income (Mali, Haiti) to understand on what parameters depends life expectancy in countries with different money
  capital.


## Approach

We will use the linear regression to see if there is a linear relation between the parameters we have chosen and 
use this knowledge to be able to decide what parameters really affect the life expectancy. Using linear regression
 we will determine the significance level of every parameter (its p-value), which will tells us either we will reject 
 null hypothesis or no. Also, the R-squared will show us how good our model is. In other words, how good this linear 
 relation is.
 
 
For more details look at [this html page](https://github.com/denysgerasymuk799/Statistics_course_research_project/blob/master/research_project.nb.html) 
