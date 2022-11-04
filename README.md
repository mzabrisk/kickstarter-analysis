# Kickstarting with Excel

## Overview of Project
Our client, Louise, is attempting raise money for her play, *Fever*, through a kickstarter campaign. We were approached to conduct an analysis of previous kickstarter campaigns to evaluate the likelihood of her reaching her fundraising goals, and to determine factors that may influence success of her fundraising campaign. 

### Purpose
Analyze previous kickstarter data to determine if there is a correlation with kickstarter success and campaign launch date or the goal fundraising amount.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![](https://github.com/mzabrisk/kickstarter-analyis/blob/d667846cc97f8bef60c02d9c8a60cd353c1d7d55/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
![](https://github.com/mzabrisk/kickstarter-analyis/blob/b685dffefca36fc6d18d47c7c6e1135311e55421/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Overall, the dataset was very well organized and required very little cleaning. However, if it hadn't been covered in class, identifying the Unix Timestamps in the "deadline" and "launched_at" columns likely would have taken a while.

## Results

### Conclusions about the Outcomes based on Launch Date:

1. When it comes to kickstarter campaigns to raise money for theater isues, May appears to be the most successful month to launch a campaign, with the most successful campaigns (111), with only 52 failed campaigns.

2. December appears to be the worst month to launch a campaign to support theater issues, with nearly as many failed (35) campaigns as successful (37) campaigns.

### Conclusion about the Outcomes based on Goals?

For campaign goals <$35,000, there appears to be a negative correlation between goal amount and the success rate of a given campaign. For campaigns seeking <$15,000, odds of success were greater than odds of failure, while campaigns seeking ≥$20,000 were more likely to fail than succeed. Campaigns seeking between $15,000 and $20,000 had equal odds of success and failure. For campaigns seeking ≥$35,000, there was no clear pattern of success vs failure.

### Dataset Limitations:

The largest limitation with the dataset is that it doesn't take into account a couple of major variables, which are difficult to apply a value to:

1. The quality of the product the kickstarter campaign is supporting.

2. How well the kickstarter campaign was publicized.

When these factors are considered, it may become evident that campaign success is less dependent on fundraising goal, launch date, etc.

### Other recommended analyses:

1. A graph or table showing the success rate of campaigns (i.e. successful campaigns/total campaigns launched) by month would be very useful. From the currently provided graphs, it is hard to tell whether May had the most successful campaigns due to a higher success rate, or only due to more campaigns being launched.

2. A graph showing the success vs. failure of campaigns based on campaign duration. From the currently provided graphs, it isn't clear whether or not campaign duration plays a factor in campaign success.
