# Excel Analysis of Kickstarter Campaigns
Performing Excel analysis on Kickstarter campaigns and their data, to map trends and produce meaningful conclusions.

## Overview of Project
Louise has created a kickstarter campaign for her play, *Fever*. In order to decipher trends and draw meaningflul conclusions, she is requiring the help of a data analyst to comb through, analyze and visualize the data of other kickstarter campaigns. In this project, the launch date, goals and outcomes of various theatre/play campaigns were analyzed using pivot tables, charts and excel calculations. 

### Purpose
By using the values and charts obtained through this excel analysis, Louise will be able to understand the outcomes of various campaigns in relation to their launch dates and funding goals. As a result, Louise wil be able to draw meaningful conclusions about her own play based on the trends of others. 


## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
To draw conclusions about theatre outcomes based on launch date, a pivot table (shown below) was created. The pivot table summarizes the count of successful, failed and canceled theatre campaigns based on the month they were launched. The pivot table also includes two filters that allow for easier read of outcomes based on specific parent categories and years. However, for the sake of this project, we have filtered the table to only look at theatre campaigns.

###### Pivot Table: Theatre Outcomes by Launch Date
![Theatre Outcomes by Launch Date - Pivot Table](Pivot_Table.png)

### Analysis of Outcomes Based on Goals
A table (shown below) was curated to understand the outcomes of theatre plays based on funding goals. For this analysis, we looked at 12 different funding goal ranges and the number of plays that were successful, failed or canceled in each range. The COUNTIFS function was used to gather the number of plays that fit into each category. 

###### Excel Table: Outcomes Based on Goals
![Outcomes Based on Goals - Table](Excel_Table.png)

### Challenges and Difficulties Encountered
The first pivot table that I created was not showing the same values as the reference table in the module notes. Although I correctly put the corresponding titles into the filter, column, row and values sections, the numbers were not adding up. I had to go back to the original Kickstarter data set and make sure that everything was in place. Although I didn't register it as a solution at the time, I decided to clear the filters one more time. Turns out, I didn't clear them properly the first time. Even a simple task such as removing filters can sometimes be overlooked in the midst of the thousands of data cells. While completing this project, I learned the importance of precision. Missing even a single character in a function can yield improper values. 


## Results
### Conclusions
- Based on the chart outlining theatre outcomes and launch date (shown below), we can conclude that theatre campaigns launched in May and June had higher success rates. Theatre campaigns launched in December had the lowest success rate.
###### Theatre Outcomes Based on Launch Chart
![Theater_Outcomes_vs_Launch](Theater_Outcomes_vs_Launch.png)                                       

- Plays that had a funding goal under $5000 were more successful than plays that had a higher goal (shown below). The overall trend shows that as funding goal increases, successful percentage decreases and failure percentage increases. 
###### Outcomes Based on Funding Goals Chart
 ![Outcomes_vs_Goals](Outcomes_vs_Goals.png)
 
### Limitations and Recommendations
###### Limitations
- After working with the first data set in the pivot table, we said that campaigns in May and June had higher success. However, it is also important to note that in general more campaigns were launched in those months. Instead of looking at percentages or ratios of success to failure, we simply looked at the count of success and failures. Yes the number of successful campaigns is larger in May than December, but the number of failures is also larger in May. Including more calculations that compares the datasets in relation to eachother or as percentages, will allow for more confident results. Additionally, the first analysis of theatre campaigns included both musicals and plays. The second analysis was filtered to only look at data from plays. Although, we can still draw conclusions from both analyses, it is better to be consistent with the category of data we are analyzing (i.e plays or musicals). Furthermore, each campaign had varying duration. The amount of time between launch and deadline could possibly affect the success of each campaign. However, this was never factored into our study on the outcomes of theatre and play campaigns. It is important to factor in all variables to better understand trends and their irregularities.
###### Recommendations
- We've created tables and charts comparing goals, launch dates and categories to campaign outcomes. Some other suggestions would be to find out which categories or subcategories receive the most pledges or donations on average. We can tabulate the mean, median, deviation and quartile ranges of pledges and donations for each category, just as we did for kickstarters in the US. This will give us some idea on which categories receive more support. We can also compare the duration of campaigns to their outcomes. We have looked at the launch dates and their effects on the outcome, but not the entire duration from beginning to end. We can create pivot tables and graphs to look at the outcomes of campaigns in relation to their duration. Does a longer campaign duration equate to higher success? 


For all data values, tables and charts, refer to [Kickstarter Challenge](Kickstarter_Challenge.xlsx)
