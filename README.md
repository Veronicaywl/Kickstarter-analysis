# Kickstarter-analysis

## Overview of Project
*Detail analysis of the campaigns performance trend, make the result into visulization.*

### Purpose

The purpose of Analysis the Kickstart funding data which included over 4000 campaigns. Analyze the relationship between funding and outcomes based on the different variables such as the parent category and subcategory. We would like to analysis how does the project launch date can affect the outcomes. We also want to know if the goal of funding impacts the project outcomes.   

## Analysis and Challenges

Use the following skills to analyze the data set. 
1. extract the necessary data from the raw data sample
   * use arithmetic functions and statistical functions apply to data set
   * use filler to sort the necessary data for analysis
   * convert the UNIX tiimestamp to readable format
2. insert graphs and tables to analyze the data.
   * use pivot table to filler the useful information based on goal and category
   * use pivot chart to visualized the anaylsis

### Analysis of Outcomes Based on Launch Date

I created a line graph for the outcomes based on launch date analysis. Use the fillter get to the 12 month in a year of the project lanunch. And gets to the result that the successful outcomes are significantly high in May, June, and July. The launch month may effect the outcomes of the projects.  

> Theater_Outcomes_vs_Launch.png
![Theater_Outcomes_vs_Launch](/Users/veronica/Desktop/Data Analysis /Module 1 challenge/resources)

### Analysis of Outcomes Based on Goals

For the outcomes based on Goals anaylze line graph. I only use the subcategory "plays" to analyze. Referred to the picture "Outcomes_vs_Goals", the "play" projects have higher amount of funding goal tend to have a higher percentage of failed. However, there are a few exceptions on a higher amount funding may lead to a relativly higher percentage of success. 

> Outcomes_vs_Goals.png
![Outcomes_vs_Goals](/Users/veronica/Desktop/Data Analysis /Module 1 challenge/resources)


### Challenges and Difficulties Encountered

I am new to data analysis field. There are lots of functions on excel I've never use before. There is a challenge for me to use the COUNTIFS function while I was working on the kickstarter spreadsheet. The most challenge part is I need to find out how to put a number range in a criteria. Luckily, I joined a study group with some classmates and we join the TA section on Saturday. I learned that if there are certain amount of the number range I need to analysis by using countifs function. I need to have multiple range and criteria which I need to analysis for countifs function. 

## Results

The conclusion about Outcomes based on Launch Date:
- Starting from Quarter 2 to quarter 3, the successful rate starts increase. The peak of the highest successful rate is in May. Starting from Q3 to Q4, the successful rate is constantly decrease. 
- Compared the successful rate and fail rate. There are about 23% difference from successful rate to fail rate. Even the line is not exactly has 23% difference in each quarter, but the trend of the failed lines tend to be flatter. Which I concluded the failed rate is relativly stable in a 12 month calendar year.

The conclusion about Outcomes based on Goals:
- The higher amount on projected funding goals can lead to a higher chance of failure. Based on the data set. The goal amount between 1000 to 4999 has the most projects; it also the highest successful cases in this data set within the plays category. In general, I concluded that in the plays category, the goal within the 1000 to 4999 range has the highest chance to successful. 

## Limitations

There are some limitations in this data set. For instance, for the analysis on Outcomes based on Launch Date. This analysis based on all year when the campaign launch. However, if we change the variable on the pivot chart by adding a filter "goal". The graph will gives me a higher successful rate if I chose the goal range between 1000 to 4999. Furthermore, to analyze KPIs should have more variables into the data set. In this case, the goal and pledged may have some correlations if we added to the current outcomes based on goals graph. We can also change the variables such as film & video category, anaylze the KPI on average donation or percentage funded for the category. We can also compares different subcategory such as "television" in film & video category. 
