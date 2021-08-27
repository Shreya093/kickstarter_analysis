# Kickstarting with Excel

## Overview of Project

In this module we will be doing analysis on the fundraising campaign based on the data provided in the kickstarter dataset. 

### Purpose

The purpose of this project is to help Louise for her fundraising campaign. As per her campaign she wants to know how all the campaigns in the kickstarter dataset succeeded in respect to their launch dates and their funding goals.

## Analysis and Challenges

As per the data provided in the kickstarter dataset we need to analyse the outcomes (successful,failed and canceled) for all the campaigns based on their launch dates and funding goals. Louise needs to analyse the outcome of camapigns under the category "theater" and sub category "plays" inorder to find all the succcessful,failed,canceled campaigns as per the launch date and the goal amount required to run a successful campaign.

### Analysis of Outcomes Based on Launch Date

Below are the points we found out as per the analysis based on Launch Date :
1. As per Louise's requirement we will carry forward our analysis on the kickstarter dataset by creating a pivot table.
2. We need to create the table by filtering out the parent category by every month on the basis of successful, failed and canceled outcomes of the kickstarter campaign.
3. Through the pivot table and charts/graphs we conclude that in the month of May the kickstarter campaign was the most successful for all the campaigns under each parent category and in the month of July the campaign had a downfall by the most number of canceled and failed outcomes.

### Analysis of Outcomes Based on Goals

Below are the points we found out as per the analysis of outcomes based on Goals :
1.  By filtering out the kickstarter campaigns on the basis of sub category "plays" we conclude that the campaigns were the most successful (with 76%) when the goal for it has been less than $1,000.
2. Through our analysis we also found that the goal above $45,000 were the most unsuccessful and failed campaigns under the sub category "plays".
3. There were no canceled campaigns for sub category "plays".
Hence, from our analysis based on goals we can conclude that inorder to run a successful campaign for "plays" Louise need to set her goal within $1,000.

### Challenges and Difficulties Encountered

1. One of the challenges which we can look for is to find the outcomes of all the campaigns as per their goal amount and the pledged amount they have collected and then do the analysis based on the outcomes (successful,failed,live and canceled) with respect to the currency for different countries. 
2. We can also find out the which campaigns have done a good job by analysing their amount of fund and average donations collected around the year. 

## Results

- What are two conclusions you can draw about the Theater Outcomes based on Launch Date?

The two conclusions  on Theater Outcomes based on Launch Date are :
1. The kickstarer campaign under the parent category "theater" was the most successful in May with 111 theater campaigns.
2. We also conclude that though May was the most successful based on launch date it also had highest amount of failed theater campaigns. January had the most number of canceled theater campaigns.

- What can you conclude about the Outcomes based on Goals?

According to the outcomes based on goals we can conclude that inorder to run a successful campaign the goal amount should not be more than $1,000 for sub category "plays" as those campaigns were the most successful with the success rate of 76%.

- What are some limitations of this dataset?

Inorder to carry out the correct analysis, the kickstarter dataset requires proper cleaing of the data by formatting the rows and colums inorder to make the data readable. The deadline and the launch dates are mentioned in the Unix timestamp which needs to be converted into readable date format.

- What are some other possible tables and/or graphs that we could create?

We can also create below possible tables/graphs:
1. We can create pivot table and graphs for all the campaign outcomes(successful,failed,canceled and live) based on the pledged amount.
2. We can also create tables/graphs inorder to find the outcomes of campaigns based on all countries.
3. We can create tables/graphs for all the campaigns based on their parent category and sub category.
