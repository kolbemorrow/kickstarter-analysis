# Kickstarting with Excel
 
## Overview
##### How Kickstarter Theater Play Campaigns perform in relation to their launch dates and set funding goals.
  Performing an analysis of Kickstarter theater play fundraising campaigns to determine which factors ensure a successful campaign. Through this analysis we can find if a specific campaign launch date and fundraising goal amount will indicate a greater chance for a successful campaign.
 ### Purpose
  Determine the optimal campaign launch time and funding goal amount to have a successful, fully funded Kickstarter campaign.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
	To find if a theater campaign has a greater chance of success based on a specific launch date, the data must be organized into a pivot table. This table categorizes theater campaigns by fundraiser performance and relates them to the launch date month.
  ![Pivot_table_theater](https://user-images.githubusercontent.com/99298165/160296540-c4bba926-687c-42a3-aa35-2f27b505a2a5.png)
Through this table I was able to create a line graph visually demonstrating that the month of May will most likely have peak performance for a theater play fundraiser.
  ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/99298165/160296561-5780856b-c6f7-44e8-bb1a-679732a555cd.png)
  
### Analysis of Outcomes Based on Goals
	Now that I understand when it is best to launch a campaign, I need to determine what funding goal will be successful. Using excel functions I created a table from the original Kickstarter data to organize the campaigns by set ranges of funding goal amounts. 
![Theater_Outcome_table](https://user-images.githubusercontent.com/99298165/160296790-19ac7709-1339-4010-9dad-897f63ee6c55.png)  
  This will allow me to visually demonstrate how the funding goal set relates to a campaign's performance with a graph. Again using functions I was able to calculate the percentage of successful, failed or canceled campaigns for each funding goal range. 
![Theater_Outcomes_percent_table](https://user-images.githubusercontent.com/99298165/160296810-df88fada-b9fa-4ca4-a912-240bcccd6c4b.png)
  Through this table I created a line graph to demonstrate what goal amount will most likely be reached, between $35,000 and $44,999.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99298165/160296829-0726a2dd-a613-46ad-a95c-74136682f8b6.png)

### Challenges and Difficulties Encountered
	During the percentage by performance calculations, I came across a challenge with the values for goal ranges that had zero campaigns in their performance categories. After debugging my formulas to account for zero values I was able to get the correct zero percent as the value.
![Theater_Outcomes_errors](https://user-images.githubusercontent.com/99298165/160296942-89ff8ec1-128b-40db-8b57-803689e8578d.png)

 ## Results
	Based on the visuals created from the data I can determine the month of May would be the best time of year to start a fundraiser for a play with a total goal between $35,000 and $44,000 for the greatest chance of success.
- What are two conclusions you can draw about the Outcomes based on Launch Date?
  After creating visuals of the outcomes versus launch date the peak month for theater campaign success is May. This will also steadily decline after May until its worst performing month of December. 
![Outcomes_vs_Goals_detail](https://user-images.githubusercontent.com/99298165/160297302-ed4a2ef2-cc5d-4a3c-a0cf-3ec5bbc5bc91.png)
A campaign launched during the last week of April will utilize the entire peak time period during May.
- What can you conclude about the Outcomes based on Goals?
  The line graph of outcomes versus goals shows two values that had the highest percent successful, under $1,000 or between $35,000 and $44,999. We understand that under $1,000 would not be sufficient funding so a goal between $35,000 and $44,999 would work best. This goal range, however, is also nestled between two peak failure campaign ranges Taking this into consideration the best goal amount is $40,000.
- What are some limitations of this dataset?
  Although this data set takes much into consideration, I would like to factor in how long the campaigns were live. This could show if an earlier launch with a higher campaign goal that is live longer outperforms a later launch with a lower goal that is live for less time, a later launch with a larger goal and longer live time, etc. These campaigns could also be affected by the number of donations submitted at a given time. Do fundraisers perform better when there is a peak number of donations happening at the beginning or end of a goal? Would the amounts of individual donations or number of donors total indicate greater chance of success? More data about timelines for multiple factors could lead to greater efficiency reaching campaign goals.
- What are some other possible tables and/or graphs that we could create?
A clustered column graph for the outcomes versus goals data would demonstrate the same results in a similar shape to the line graph. A pie graph of the successful outcome percentages would show which goal amount would also work best.
![Outcomes_vs_Goals_clustered_column](https://user-images.githubusercontent.com/99298165/160297660-08f505a6-ec14-47bc-a09a-32df11e9278e.png)
