# An Analysis of Kickstarter Campaigns
## Overview of Project
Louise’s play *Fever* was $400 short from its fundraising goal in only about a month's span. Louise wants to understand if other plays were successful based on their launch dates and their funding goals. I created multiple charts to visually see the different campaign outcomes to make those comparisons. 
### Purpose 
The purpose of this analysis is to understand which starting months and which range of goals resulted in the most number of successful, failed, and canceled outcomes.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This chart shows how many successful, canceled, and failed theater campaigns that occured each month ranging from year 2014 to 2016.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/88408350/129803467-922ee355-5c67-4e89-ab79-9adc647ab949.PNG)

### Analysis of Outcomes Based on Goals
This chart shows the percentage of successful, canceled, and failed plays that occured in between a range of goals.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/88408350/129802943-e7085a25-98de-45dd-8376-95aa2d0e4fe2.PNG)

### Challenges and Difficulties Encountered
While analyzing the "Outcomes Based on Goals" chart, a challenge I encountered was thinking I put in the wrong formula under the "canceled" column because all of my results were zeros, which was very surprising. I dug a little deeper in the Kickstarter dataset and used a filter for "outcome" to show only "canceled" and a filter for "subcategory" to show only "plays". By doing so, I realized there were no plays that were canceled, so my formula was in fact correct. It is good to always double check your formulas, because having all zeros in certain situations might mean there is an error in your data.
## Results

- **What are two conclusions you can draw about the Outcomes based on Launch Date?**
  The month that launched the most successful Kickstarter campaigns was May. However, May, June, July and October all had roughly the same number of failed campaigns launched.
- **What can you conclude about the Outcomes based on Goals?**
  A goal of less than $1,000 has the highest chances of having a successful outcome on a play. On the other hand, the goal range of $45,000-$49,999 has a 100% chance of having a failed outcome.
- **What are some limitations of this dataset?**
  Some limitations of this project is that it does not explain how long each campaign lasted from launch date to end date. It would also help to filter the outcomes based on year, not just months to see if that played a factor in the results. Another limitation is that the "Outcomes based on Launch Date" looks at the parent category, theater, which includes musicals and plays, while the "Outcomes based on Goals" only looks at plays, so it is difficult to compare the two charts.  
- **What are some other possible tables and/or graphs that we could create?**
  Another pivot table with the subcategory, plays, should be created so that we have a more detailed analysis on how these results are compared to Louise's initial play *Fever*. There should also be a chart that has length of campaign from the beginning date to end date so that we can analyze the average of how long it usually takes to achieve the goal for each play. 

