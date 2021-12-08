# Kickstarting with Excel

## Overview of Project

### Purpose
The data provided shows us many different categories related to kickstarters for fundraising campaigns. We are specifically looking into theater/plays to give Louise an analysis/recommendation for what she should do with her upcoming play kickstarter. The purpose of this analysis was to specifically visualize the outcomes of kickstarter campaigns based on their launch date as well as their financial goals in order to inform Louise on past trends supported by the data. 

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
The first analysis I performed was Theater Outcomes based on Launch date. To do this, I had to use the Year() function to find the launch year of all kickstarters. Once I had a new column with the Launch year, I used the 'Kickstarter' sheet to create a pivot table. By filtering by "Parent Category" I was able to find only Theater kickstarters. In the graph titled "Theater Outcomes Vs Launch" I have put the months on the x-axis and the count of outcomes on the y-axis in order to visualize the data shown in the pivot table to easily identify any trends. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/90940985/145268556-3edf56ba-1074-4a18-b7a1-a3d38ad0b82d.png)

### Analysis of Outcomes Based on Goals
For this analysis, we were looking at the outcomes based on each play kickstarter's goals. To do this analysis, we used the COUNTIFS() function in Excel to count each kickstarter outcome that fit the criteria speficied i.e. amount and subcategory. By looking at the graph below you can see the percentages of 'Successful', 'failed', and 'canceled' kickstarters at each goal range. This vizualization allows us to see the trends more clearly than in the table.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90940985/145268631-b195474b-2ae0-4cb3-9886-3ffe23e3a991.png)

### Challenges and Difficulties Encountered
A challenge you could run into regarding these analysis could be getting the parameters of the pivot table correct. Sorting the outcomes in descending order can be tricky as well as displaying only the months of each campaign. To solve each of those issues, you can use trial and error to mess with the setting and see what works, or you can try googling and looking at examples to help. A challenge I ran into was the Countifs formula, I was forgetting to add in the subcategory criteria. By leaving out the subcategory formula, I was getting a count of every category and this was diluting my results. After watching the rest of the hint video I was able to fix my mistake and finish my analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Two conclusions I can draw about the Theater Outcomes by Goal are that kickstarters launched in May clearly have the most successful kickstarters, and the winter months do not appear to be as successful as the spring/summer months.
- What can you conclude about the Outcomes based on Goals?
By looking at the analysis of the outcomes based on goals, as the goal increases in value, the percentage successful starts to decline. This shows me that the lower the kickstarter goal, the better the chances of successfully meeting that goal. Aside from the increase from 35,000 to 40,000 which could be due to other circumstances.

- What are some limitations of this dataset?
Some limitations of this data are that there could be outliers that skew the results, the data could be just a sample size and not contain all possible data for this analysis.

- What are some other possible tables and/or graphs that we could create?
We could also fine the difference in the launch date and due dates and compare the duration to the outcomes to see if there is any correlation between length of campaign and the outcome. We could also look at the number of backers vs the outcomes to see if the amount of backers has any significance on the outcome of the campaigns.