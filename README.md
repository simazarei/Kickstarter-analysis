# Kickstarting with Excel

## Overview of Project
Louise wants to know how different campaigns fared in relation to their launch dates and their funding goals. There are 4,014 different campaign between _2009_ to _2017_ took place throughout the world . We want to comb the data in favore of Louise's desire to run her play _Fever_ campaign which has a budget of 10,000 $ and falls under _Theater_ Category.
### Purpose
The purpose is to find out what makes a campaign project _Successful_ or _Failed_. We are going to visualize _Theater_ campaign which has three subcategories based on its launch dates and funding goals to deliver the outcome to Louise and help her within her choice of  setting her campaign budget, campaign goal and launch date of her _play_ campaign to make it successful.
## Analysis and Challenges
### Analysis of Outcome based on Launch Date
The outcome based on launch date as is displayed below, shows that out of _1,369_ campaigns in _Theater_ category and _Play_ subcategory _839_ campaigns were _Successful_ which is _61%_ of all and _493_ campaigns have _Failed_ which comes to _36%_. Between March to May the campaign outcomes increased, and it peaked in May by _111_ and reached to 100 on June and it dropped afterwards till end of the year. The outcomes fluctuated from Jan to March around 60. On Dec, the outcomes of _Successful_ and _Failed_ met at around _35_. The month that launched the most successful Kickstarter campaigns was May. However, January, June, July and October all had roughly the same number of failed campaigns launched.

![](Resources/Theater_Outcomes_vs_Launch.png)
 
### Analysis of Outcome based on Goals
The most _successful_ campaigns are in the groups of _[Less than 1000]_ and _[1000-4999]_ which have more then _70%_of success and the biggest rate of failed campaigns belongs to _[45000-49999]_ and _[Greater than 50000]_ which is almost 90% to 100%. The Line chart shows that in order to acheive Louise's goal we need to focus on the group that her goal has been set.

![](Resources/Outcomes_vs_Goals.png)


###Challenges and Difficulties Encountered
Campaign goals have a huge diversity from 1$ to more than 50000$ which makes the analysis process scattered. To tackle this issue goals are grouped between a range to make the analysis process possible, and the outlier of goals should be removed from the dataset.
There is a column in the worksheet named "Category and Subcategory," which groups a main category with all its subcategories for instance _Theater_ has three subcategories of _Plays_, _Musical_ and _Spaces_. We made our data more detailed by splitting the Category and Subcategory column into two distinct columns: "Parent category" and "Subcategory." This gives us additional data to use in our analysis.


## Results
- What are two conclusions you can draw about the Theater Outcomes by Launch Date? 
1) The _successful_ campaigns for _theater_ have the launch date started on March and goes up till May and stays _successful_ in June and July as well which seems to be related to the seasonal conditions.
2) The _Failure_ campaigns seem to have a small flactuation anround 40.
- What can you conclude about the Outcomes based on Goals?
1) Campaigns with the lower goals seem to be more achievable in terms of success. 
2) Campaigns with a greater number of projects reflects more realistic outcomes.
- What are some limitations of this dataset?
For campaign goals bigger than _[15000-19999]_ the number of data is insufficient. For instance there is only one failure in campaign with the goal of _[45000-49999]_ that makes it 100% _Failed_.
- What are some other possible tables and/or graphs that we could create?
Another factor that can come to play is the duration of each campaign. Since we have the deadline date we can create the chart and analyze how our campaings are affected by run time of theirs.

