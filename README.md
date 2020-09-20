# An Analysis of Kickstarter Campaigns
performing analysis on kickstarter data to uncover trends

# Kickstarting with Excel

## Overview of Project
This project is about analyzing data for different campaigns and the results of the campaign efforts. 
### Purpose
The purpose of the analysis is to find trends in the data so that it can be used in future efforts. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The data provided did not have a column for the year ended. I created on using the YEARS formula. This column helped me break the data down in a pivot table. The pivot table I created filtered only to the theater category. The columns created show the different outcomes: successful, failed and canceled. The rows created show the date created by month. The values are the count of the outcomes. From this pivot table I was able to create a pivot chart (pictured below). The month created is the X axis and the number of outcomes is the Y axis. The successful launches are in blue, the failed launches are in orange and canceled launches are in grey. 
https://github.com/Stephaniepaul44/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png
### Analysis of Outcomes Based on Goals
From the data provided I analyzed only the plays for this sheet. I used a countif formula to find the number of successful, failed and canceled plays for each dollar amount bracket. They are listed in columns B-D. In column E I did a sum formula to add the number of successful, failed and canceled plays together. In columns F-H I calculated the percentage for each outcome by dividing the number in columns B-D by the number in column E. For example the number of successful campaigns is in column B I divided this by D to get a percentage successful. From the data I calculated with formulas in columns B-H I was able to create a pivot chart (pictured below). The goal amount is the X axis and outcome percentage is the Y axis. The successful launches are in blue, the failed launches are in orange and canceled launches are in grey.
https://github.com/Stephaniepaul44/kickstarter-analysis/blob/master/Outcomes_vs_Goals.png
### Challenges and Difficulties Encountered
Some potential challenges with this data analysis would be not filtering the data to theaters for the outcomes based on launch or not looking at the right columns for the countif formula.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The conclusions I came to based on the analysis of theater outcomes based on launch date were that the launches in May - July were most successful and there were large number of canceled launches in January. 
- What can you conclude about the Outcomes based on Goals?
The conclusions I can to based on the analysis of play outcomes based on goals were that the most successful campaigns were the ones with a goal of less than $1000 and the campaigns with the largest goal were least successful. 
- What are some limitations of this dataset?
The data set provided is only categorized by country. If further analysis is needed in the US more data would need to be provided. 
- What are some other possible tables and/or graphs that we could create?
A scatter graph could also be used to show the trends in the data. 
