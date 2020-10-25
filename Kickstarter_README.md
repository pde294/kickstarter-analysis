# Kickstarting with Excel

## Overview of Project

### Purpose
-	The purpose of this project is to analyze trends for various Kickstarter campaigns for our playwright, Louise,  to help her understand how she should run her own campaign. 
-	This analysis will help her with decisions such as determining the launch date and the ideal goal she should set. 


## Analysis and Challenges
-	To understand how launch date impacted outcomes, I created a pivot table and chart looking at the relationship of outcomes to the date a campaign was created. 
-	I converted the dates into months to examine overall trends of launches by month. 
-	I also filtered the parent category for this table to only show results for “theatre”, the category that would be most relevant for Louise’s purposes. 
-	To understand how outcomes were affected by the goals set by the campaigns, I conducted an analysis using the COUNTIFS function to see how many plays were successful, failed, or canceled under certain ranges of values for goals.
-	For example, to count how many plays had a goal of less than $1000 and were successful in meeting that goal, I utilized a formula of =COUNTIFS(Kickstarter!$D:$D,"<1000",Kickstarter!$F:$F,"successful",Kickstarter!$R:$R,"plays").
-	I then analyzed the percentage of projects at each of the set goal ranges that were successful, failed, or canceled. For example, to see the per  To see the aforementioned code, please see 
-	[Kickstarter Challenge]( https://github.com/pde294/kickstarter-analysis/blob/5bd51d595f34d1130d5fe149c9e358e47f023673/Kickstarter%20Challenge.zip).
-	Finally, I created a table to illustrate the relationship of outcomes (by percentage of projects that were successful/failed/canceled) in comparison to the set ranges of values for goals

### Analysis of Outcomes Based on Launch Date
####Most Successful and Most Failed Campaigns by Date
 -    The largest number of successful campaigns were launched in May (111). However, the largest number of failed campaigns were launched in May as well (52). The month of May also saw the largest gap between the number of successful campaigns and the number of failed campaigns in a month (a difference of 59 campaigns). 
-	The months of June and July saw the second-highest (100) and third-highest (87) numbers of successful campaigns.  
-	The months of July and October saw the second-highest number of failed plays (50 for each month), and the month of June saw the third-highest number of failed campaigns (49). 
-	
#### Least Successful and Least Failed Campaigns by Date
-	The month that saw the least successful campaigns was December (37), and the month that saw the least failed campaigns was November (31).  
-	You can view the  “Outcomes Based on Launch Date” table at [Resources](https://github.com/pde294/kickstarter-analysis/commit/f55c2a7eac9ce899a18596ea445eec23c63d34a8)
o	
### Analysis of Outcomes Based on Goals
- The most successful campaigns had goals set in the $1000-4999 range (388 campaigns). 
-	The most failed campaigns also had goals set in the$1000-4999 range (146 campaigns).
-	The goal range that saw the least successful campaigns were those that fell in the $45,000-49,999 range (0 campaigns)
-	The goal range that saw the least failed campaigns were those that fell in the $40,000-44,999 range and the $45,000-49,999 range (1 campaign for each range).    
-	The goal range of $1000-4999 saw the largest difference between the number of successful campaigns and failed campaigns, where the number of successful campaigns was greater. 
-	For campaigns that had a goal greater that $50,000, there was the largest gap between campaigns that failed (10) and campaigns that were successful (2), where the number of failed campaigns were greater. 
### Challenges and Difficulties Encountered
- One challenge I ran into was ensuring data quality when I edited the various COUNTIFS formulas in my sheet. I noticed I had an error at one point when several of the cells under the “Percentage Failed” column were zero. While one value of zero would not have been enough for me to question what I was doing, seeing several values of zero caused me to want to know what was happening. When I checked my formulas in that column, I found I had a typo in the word “failed”. When I corrected my mistake, all of the values changed in the column. This error taught me to (a) check for data quality and (b) doublecheck anything that may look irregular in my sheet.  
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? May and June are when most campaigns are launched, and the most successful campaigns are launched in these months. 
-	Additionally, December is not the best time to launch a campaign, as you may have the least success with it. 

- What can you conclude about the Outcomes based on Goals? It is best to have a goal that is either less than $1000 or somewhere between $1000-4999. 

- What are some limitations of this dataset? There are several limitations to this dataset. It doesn’t indicate the potential number of people who the campaign reached out to for donations. It also doesn’t state if the particular playwright is an experienced playwright who is possibly reaching out to previous donors. Both the potential number of donors and the number of donors who previously donated to this playwright could illustrate interesting trends for this analysis. 

- What are some other possible tables and/or graphs that we could create? Other tables that could be created include (a) Outcomes versus Duration of Campaign, (b) Outcomes versus Staff Pick, and (c) Outcomes versus Country. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
