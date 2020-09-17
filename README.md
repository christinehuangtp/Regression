# Regression
### LA census population

#### 1. Introduction
##### 1.1 Background
Every March and April of the year, US goverment ask residents completed census. What is inside of the census could we know? Are there any linear relation between each factor? The goal of this assignment is to draw a scatter plot with a least square regression line of variables perimeter and area, and calculate the correlation coefficient and the coefficient of determination.

##### 1.2 Data
The dataset hosted by the city of Los Angeles in 2010. The data collected by zip code, which showed the different regions people census. In this assignment, we took population and househole as variable to see if there is any relation between its.

data: https://www.kaggle.com/cityofLA/los-angeles-census-data

variables: x - Total Population (number) y - Total Households (number)

We are courios about if total household change by the total population? So we took total population as a indepentdent variable (X), and total household as a dependent varoable (Y).

#### 2.1 Explore data
First, checked the data type. Because we are going to calculate the data, the type should be int or float. Also, checked if there is any null column in the dataset. As below showed, all the numbers in each columns are numberic and there is no null row.

#### 2.2 Clean the data
Because zip code is a code which not present any meaningful numbers, we dropped the column and rename other columns.

#### 3. Analysis
Before analyze, we called useful library. Using numpy transpose fuction can transfer each cloumn to each list, then we assigned column name by index. Functions contained the calculation in slope and intercept of the least square regression line, the drowing of the scatter plot and regression line, the calculation of correlation coefficient and coefficient of determination.

##### Generate scatter plot and regression line

##### Calculate the correlation coefficient and coefficient of determination

#### 4. result
According to the correlation coefficient, the correlation coifficinet is 0.91, we can conclude that there's a significantly strong relation between total population(X) and total households(Y) in LA. However, we can't not conclue that total household is caused by the total population. Strong correlation does not imply causation becuase it is possilbe that total poluation and total households are each strongly related to another vairable.
