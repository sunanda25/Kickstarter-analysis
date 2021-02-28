# Analysis of Kickstarter Campign
## Overview
Louise is a play writer and is seeking to crowdfund her play “Fever”. With the help of 9 years (2009-2017) of Kickstarter data, trends and patterns can be identified using Excel functionalities. The analysis below provides insight into the chance of success for Louise’s Kickstarter campaign based on the funding goal and the time of launch. The results have been summarized using pivot tables and Graphs for Louise to decide.
## Analysis and Challeges
Louise wants to analyze two factors. They are:
1.	Outcomes based on Launch Date
2.	Outcomes based on Goals

### Analysis of Outcomes Based on Launch Date
A pivot table was created to summarize the monthly performance of Kickstarter campaigns related to Theater to compare if an outcome is “successful”, “failed” or “canceled”. The summarized data shown in the pivot table is shown as a Line graph below:

![image](https://user-images.githubusercontent.com/76491891/109406049-f11e5a00-7943-11eb-80b3-ec52ec8ff5a9.png)

By analyzing the Line graph for the outcomes based on Launch date:
*	Majority of Kickstarter campaigns related to Theater that are successful were launched in May or June.
*	Kickstarter campaigns related to Theater launched in December have an equal chance to be successful or failed campaigns.

### Analysis of Outcomes Based on Goals
Using the COUNTIFS () function in Excel, the number and percentage of successful, failed, and canceled Kickstarter campaigns have been categorized based on the goal range (< 1000 - >50000) column. A line graph has been created using the categorized data as shown below:



By analyzing the Line graph for the outcomes based on Goals:
*	If the campaign Goal amount is lower, then the chance of success rate is higher. From the above line graph, we can say that most successful campaigns have low goal amounts like $5000 or less.
*	If the campaign Goal amount is higher, then the chance of failure rate is higher. From the above line graph, we can say that most failed campaigns have higher goal amounts like $45000 or more.

### Challenges and Difficulties Encountered
*	In the Kickstarter table, we have Category and subcategory in the same column. By dividing the column into Parent category and subcategory it was easy to use the columns for analysis.
*	The values in the Goals column are not in a format to use directly in a formula. The COUNTIFS() formula had to be manually entered for each category.

## Results
### Conclusions about Outcomes based on Launch Date
* Upon analyzing outcomes using Launch date, if Louise launched a Kickstarter campaign for her play in May or June it is more likely to be successful. 
* If she launched a Kickstarter campaign for her play in December, there is an equal chance of success or failure. 

### Conclusions about Outcomes based on Goals
* Upon analyzing outcomes based on Goals, if Louise’s Kickstarter campaign has a goal amount lower than $5000, it is likely to be successful. 
* If the Goal amount is more than $45000 there is a higher chance for the Kickstarter campaign to fail.

### Limitations
*	Dataset provided was for the years 2009-2017, a more recent dataset is required to provide accurate analysis for Louise. 
*	The dataset provided only shows Kickstarter campaigns, however it is not the only crowdfunding platform.
*	Data from other crowdfunding platforms is required to do a complete analysis. 

### Possible Tables/Graphs
*	A trend of average donations can be plotted for all sub-categories under theater. To do this, a pivot table can be created with sub-categories as rows and years as columns.
*	A summary of outcomes can be shown with respect to the campaign duration. To do this, a pivot table can be created with duration as rows and outcomes as columns. This information can be shown visually as a line graph. 
