# Kickstarting with Excel

#### Brian Gerrard's analysis on Kickstarter data 
---
## Overview of Project
For this project I analyzed Kickstarter data to educate Louise on crowdfunding by pulling insights, trends, and highlighting the factors that go into launching a successful crowdfunding campaign. Louise is launching her first campaign on Kickstarter for her play “Fever” and has a budget of $12,000. 

### Purpose
This analysis was performed on several thousand crowdfunding projects with the goal of uncovering insights that will help Louise launch and run a successful campaign for her play.



## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Theater campaigns launched in the middle of the year (May, June, and July timeframe) are more successful than campaigns launched throughout the rest of the year. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/75700317/107574717-feee8400-6bbc-11eb-97ea-9e1f1dd40d5e.png)

Though there are more campaigns launched during those months, the success rate of that 3 month timeframe (successful campaigns/total campaigns) is only a few points higher than the average success rate per month. For example: 166 campaigns were launched in May and 111 of those were successful. If you look just at successes May has the most by a large amount, but if you look at the success rate (successful campaigns/total campaigns) for May, that is 67% which is only 6% higher than the yearly average (see below).

![Successful_Outcome_Rate](https://user-images.githubusercontent.com/75700317/107580467-986d6400-6bc4-11eb-963b-d03e25de5c83.JPG)

 
### Analysis of Outcomes Based on Goals
Kickstarter provided insight into outcomes relating to play campaigns. Since Louise’s goal was $12,000 she fell into the $10,000-$14,999 goal range.

There were 72 total plays in the $10,000-$14,000 goal range, 39 of the 72 were successful which means there is a roughly a 54% chance of successfully hitting her goal of $12,000.  

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/75700317/107574773-0dd53680-6bbd-11eb-85cb-7667ddb14567.png)

To take this a step further, when looking at the success to failure ratio per outcome group, it is interesting to point out that the first two groups (Less than 1000, 1000 to 4999) are significantly higher than the other groups. That said, if you are looking to launch a Kickstarter campaign for a play, it’s best to have a goal no greater than $5,000. 

### Challenges and Difficulties Encountered
The first challenge I ran into during my analysis was converting the “launched_at” and “deadline” data to a date format. By converting this data to a date format this allowed me to look at campaign outcomes over time and figure out when the best time during the year is to run a campaign for Louise. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
   - It is safe to say that Kickstarters for Plays that launch during the middle months of the year (May, June, July) are more successful than those launched any other time in the year.
   - September is the worst month to launch a Kickstarter campaign for Plays with the highest failure rate of 47% (failed outcomes/total outcomes).
   
- What can you conclude about the Outcomes based on Goals?
  - There is approximatelty a 54% chance that Louise will successfully hit her goal of $12,000 based on the $10,000-$14,999 goal range
  
- What are some limitations of this dataset?
  - This data set included several Kickstarter projects whose campaigns were still live during my analysis. Since I am unable to determine if a live campaign is a success or failure this poses a limitation within the dataset. 
  - Some projects have multiple campaign launches which poses a limitation within the data set because it skews the outcome of a given category. For example: The play "Beirut, Lady of Lebanon" is a project that launched a campaign in 2016 that failed by only pledging $1,225 of their $30,000 goal. This project launched a second campaign in 2017 and was successful (pledging $4,250 with a goal of $4,000). 

- What are some other possible tables and/or graphs that we could create?
  - Success rate based on Staff Picks - Do staff picks have any affect on whether a campaign is successsful or not?
  - Campaign relaunch success rate - There were some projects that launched more than one campaign. Do failed or cancelled have a better chance of succeeding if they launch multiple campaigns?

## Data Dictionary
This data was publically collected from Kickstarter, a platform where people can post projects and publicly raise money through crowdfunding. The dataset consists of 4,114 different Kickstarter campaigns across 21 countries the world. For my analysis I focused on the below data points:

•	Goal – how much money a campaign needs for the project to succeed 

•	Pledged – the amount of money a campaign actually earns

•	Outcomes – did the campaign meet their goal (Successful, Live, Failed, Cancelled)

•	Country – the country in which the campaign started 

Here is a table of the fields and key terms I used to conduct my analysis. 

![Data Dictionary](https://user-images.githubusercontent.com/75700317/107574818-1b8abc00-6bbd-11eb-9a8f-89f50208ad8a.JPG)
