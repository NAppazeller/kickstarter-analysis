# An Analysis of Kickstarter Campaigns
Perform analysis on Kickstarter data to uncover trends


## Overview of Project


Louise, an up and coming playwright, would like to launch a U.S. crowdfunding campaign to help fund her play "Fever". This will be Louise's first campaign and will have an estimated budget of $10,000-$12,000. She has requested an analysis of crowdfunding data to determine if there were specific factors that contributed to the success or failure of prior campaigns. 


### Purpose

Determine viability of crowdfunding campaign for the play, Fever, with the overall goal of providing a roadmap which mirrors prior successful campaigns.


## Analysis and Challenges

The information provided covers a period of nine years with data relating to 4,100+ campaigns that spans 13 different countries. Additionally, there are nine campaign categories which can be further broken down into 40+ subcategories.

Given the vastness of the data it was important to isolate only that which was applicable to the requested analysis. There were additional steps taken such as scrubbing the data to ensure certain data are presented in a consumable format (i.e. dates, etc.), debugging, and manipulation of said data for production of visuals that communicated the data story. By focusing on outcomes by launch data and goals we were able to visually display our findings in the form of line charts.



### Analysis of Outcomes Based on Launch Date


By looking at the line chart based on outcomes related to launch date the data shows the months of May and June both have a higher success rate.

![](https://github.com/NAppazeller/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

By looking at the line chart based on outcomes related to campaign goals the data shows a success rate slightly greater than 50% in the $10k-$14.9K range.

![](https://github.com/NAppazeller/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered

There was a minor issue of scope creep as Louise also requested analysis on a handful of plays from the Edinburgh Festival Fringe and musicals in Great Britain for a potential future project. Both requests were unrelated to the overall analysis.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on our analysis of outcomes by launch date we're confident recommending the campaign for Fever be launched in either May or June. On average there was a 60% success rate for theater campaigns during the year. However, during the months of May and June the success rate is 67% and 65%, respectively. Additionally, it would be advisable to not launch the campaign during the months of October or December as those months typically see the highest rates of campaign failure.


- What can you conclude about the Outcomes based on Goals?

Based on our analysis of outcomes by goals the margin for success narrows, but still shows promise. Given the campaign goal of $10-12K there is an approximate success rate of 54%.


- What are some limitations of this dataset?

Some limitations that may be impactful to this data set, and the launch of a successful campaign, are directly related to lack of data which may include the city the campaign is based in, campaign sponsor demographics, and money spent on marketing.


- What are some other possible tables and/or graphs that we could create?

A deeper dive into outcomes by goals related to the subcategory "plays" as well as the tightening the goals analysis ranges to mirror the campaign's goal range could produce more meaningful results. It may also prove helpful to look at outcomes based on launch date for the subcategory "plays" rather than the main category of theater. Determining contribution amounts based on the minimum number of contributors may be beneficial in determining incentives for campaign sponsors.
