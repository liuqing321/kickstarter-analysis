# Kickstarting with Excel

## Overview of Project

Louise wants to start out a crowdfunding campaign to help fund her play, Fever.Thus, she wants to analyze crowfunding data to determine whether there are specific factors that make a project's campaign successful. Through the analysis, she could manage her project better and get greater outcome.

### Purpose

The purpose of the analysis is to help Louise find out how different campaigns fared in relation to their launch date and their funding goals. Also we will see if there is any pattern that Louise could follow to make her own campaign successful. 

## Analysis and Challenges
There are two strategies for the funding campaign. 
- Launch the campaign at the right time
- Adjust the budget/goal to a reasonable amount

So I translate those strategies into two quesiton, 
 1. Which month would be the best time to start the campaign?
 2. What is the relationship between goal and outcome? 

To solve the problems, I started with the variables in those two questions,

-Month

-Goal 

-Outcomes

The main chanllenge is to process the data and find representative indicators for a successful campaign. Another chanllenge is to find suitable graphs and chart to illstruate the relationships among those variables. 

I tried to establish the relationships between different variables. So I inserted a pivot table and pivot chart, in which I could observe the changes and relationships for different datasets. And finally I find out the percentage of successful outcome should be the best indicator for this analysis. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/88631769/131232042-705ae716-39d7-462d-a982-db71e05339c0.png)

   * For theater project campaign, May is the most successful month because The number of successful outcome in May is the highest. Dec is the worst month because the number of failed outcome in Dec is high while the number of successful outcome is at its lowest point.Louise would receive more pledges if she launch her funding campaign in May. 
 
   * Theater is the most popular entertainment. Most of the successful campaign outcomes happened in the category of theater. 
   
- What can you conclude about the Outcomes based on Goals?
  ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/88631769/131597336-2c6d3cf2-e51e-4e5e-ab99-8ae119915e9f.png)


   * Louise's budget is $10,000.00. The possibility of achieving that goal is 48%. If she  could lower her budget to $5,000.00, the possibility for a successful campaign could be higher. 
 
   * The rate of success inversely related to the amount of campaign goal when the campaign goal is less than $35,000.00. When the campaign goal is greater than 35,000.00 and less than $45,000.00, the rate of success and the amount of campaign goal is positive correlated. When the campaign goal is higher than $45,000.00, the chance of failure or cancellation become very high. To receive more pledge, Louise could take some risks and change her goal to $40,000.00. 
 

- What are some limitations of this dataset?

   * We don't know where Louise is going to launch her campaign. The dataset includes worldwide campaign information, which could result in a misleading conclusion. People from different countries and cultures would have different preferences for entertainment activities. if the dataset includes massive data from a place where people like activities other than theater, Louise might draw a conclusion that she should not start the campaign at all. To get a more accurate projection for the coming funding campaign, Louise needs to gather the campaign data in the region where people's preferences and income level are similar to the preferences and income level in the region her campaign will take place. 
 
   * The dataset is not recent. People's preferences and income level could have changed greatly in the past four years. For example, because of COVID pandemic, people start fearing participating in activities involve large crowds. And average income in US has been significantly affected by economic slowdown. Although the data analysis suggested that her funding campaign has a very high possibitliy of success, the fact is that people are less interested in theater in recent days and they are less likely to pledge generously on a play. 
 
 
- What are some other possible tables and/or graphs that we could create?

   * The pie chart for successful outcomes based on the parent categories. 
   * The 100% stacked column could be used to show the percentage of different outcomes for EACH parent/sub category.  
 
