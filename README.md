# Kickstarting with Excel

## Overview of Project

The purpose of the project was to analyize kickstarter campaigns by launch date and goal amount. The goal was to see when would be the best time to launch a campaign and what was the percentage of successful campaigns based on goal amount.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Began by creating a column within the kickstarter data to extract the year from the date created. Then created a pivot table to see the successful, failed, and canceled campaigns seperated by month. The pivot table was filtered by the parent category and years. The charts columns were outcomes and the rows were date created. The values were the count of outcomes. The table was then filtered to only show the Theater campaigns. Using the pivot table, a pivot chart was created to visualize the data from the table. Using a line graph shows the month versus the sum of the campaign outcomes. Three lines show the trend of the successful, failed, and cancelled campaigns.

### Analysis of Outcomes Based on Goals
First created a table with rowas labeled with goal intervals and columns labeled by number of success, failed, and canceled, total projects and percentage of success, failed, and canceled. The number of campaign outcomes were found by using a COUNTIF function that iterated through the goals column of the succesful campaigns and produced a sum that was within the given ranges. The same was done for failed and canceled campaigns. Then the total projects were found by adding the successful, failed, and canceled campaigns together. Then the percentage of each outcome was found by taking the sum out of the total. From this tables a line graph was created that showed the relationship between the goal range and the percentage of each outcome. 

### Challenges and Difficulties Encountered

A possible change in analyzing the data is double checking your work. Because there are many data entries it is difficult to estimate the correct outcome when using functions that count or sum up columns of data. If the data set was smaller, it can be easier to predict what the analysis should show. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

From the pivot graph, "Theater Outcomes based on launch date", 111 successful campaigns were launched in May which is the max number of successful campaigns launched out of all the other months. From the same graph, the majority of failed campaigns launched around June, July, and October. The number of failed campaigns also has a peak in May, however, this is likely due to the majority of total campaigns launched in May. Therefore, as the number of campaigns are launched increase, the number of failed campigns is likely to increase as well. However it was still only slightly higher than the other max in October. 

- What can you conclude about the Outcomes based on Goals?

From the graph, "Outcomes based on goal", the line graph shows that there were more successes when the range was either less than 1000 and between 35000 to 44999.   

- What are some limitations of this dataset?

A limitation of the data can be the advertising surrounding the successful campaigns. This data does not show how the campigns were able to draw attention the the kickstarter in order to get people to donate. 

- What are some other possible tables and/or graphs that we could create?

There is data on the launch and deadline of the campaigns so it can be analyzed if the length of the campign affected its success. 
