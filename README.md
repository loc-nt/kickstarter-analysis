# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

### Challenge:

From the "Outcomes Based on Goals" analysis, even though campaigns with goals ranging from $35,000 - $45,000 have a considerably high success rate (67%), there are only 10 projects total. Thus, it is too early to draw a conclusion from this goal range unless we have more supporting data. However, projects with goals less than $5,000 have the highest success rate (more than 70%) over 720 data rows. Therefore, starting a "plays" project with goals less than $5,000 seem to be the safest strategy.
![Outcomes Based on Goal](https://github.com/loc-nt/kickstarter-analysis/blob/master/Module%201%20Challenge_Outcomes%20Based%20on%20Goal.png)


In addition, according to the "Outcomes Based on Launch Date" analysis, theater projects started in May  returns the highest number of success, while the number of failed projects looks pretty consistent through out the year. Similarly, the number of successful project goes down all the way to December, almost equal to the number of failure. Therefore, you will have the highest chance of success if you start a theater project in May, and try to avoid the ending months of the year, especially December.
![Outcomes Based on Goal](https://github.com/loc-nt/kickstarter-analysis/blob/master/Module%201%20Challenge_Outcomes%20Based%20on%20Launch%20Date.png)


Despite the information we can get, this dataset has three main limitations. Firstly, it does not have a clear explanation on the outcome status. For instance, how can you tell a campaign is canceled? Was it canceled by the owner, or by the system if it stays live longer than a number of months? Giving a clear definition of this outcome status might give us more insight on why there was completely zero cancelled project in "plays". 

Secondly, the two analysis are independent from each other: one is looking at the theater category, while the other is looking at the plays subcategory. It would be better to see a combined analysis for both theater and plays. For example, seeing the seasonal factor in plays, with goal less than $5,000, can confirm if May is still the best month to start a new project in this subcategory.

Last but not least, based on Louise’s background, she's trying to find out whether the length of a campaign contributes to its ultimate success or failure. The analysis was focusing on the launch date only, and forgetting to include the end date and calculate the duration of the campaigns. I would suggest conduct this month duration analysis which will provide additional valuable insight for Louise.




