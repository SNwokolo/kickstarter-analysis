# kickstarter-analysis
analyzing the kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to help Louise figure out how different fundraising campaigns turned out in relation to their launch dates and funding goals. This would help provide her with some direction as to when the best time is to launch her production and the best funding goal amounts to aim for.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Dates
![Launch_dates](resources/Launch_dates.png)
![Theater_Outcomes_vs_Launch(resources/Theater_Outcome_vs_Launch.png)
The analysis of the data in this section shows the amounts of theater productions that have either been successful, failed or canceled for all the months of the year across different years. 

### Analysis of Outcomes Based on Goals
![goal_vs_outcomes](resources/goal_vs_outcomes.png)
![Outcomes_vs_Goals](resources/Outcomes_vs_Goals.png)
In this section, the data shows how the production of plays were either successful, failed or got canceled based on the goal  amount of the campaign funding provided to the production

### Challenges and Difficulties Encountered
One difficulty I encountered in trying to calculate the data was in the 'Outcomes based on goals' data. Here, I found I made a few errors when using the COUNTIFS function because of nested nature if the formula. It took a few trial and error sessions before I found the proper combinations of ">= and <" for the goal amounts listed.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
From the ‘Theater outcomes by launch date” data, it can be concluded that through the years, the most successful outcomes for the theater category can be seen in the month of May and the least in the month of December. It can also be concluded that the most failed outcomes were observed between the months of May and October while the least amounts can be seen in November. Therefore, Louise is more likely to get a successful outcome if her theater production us launched in the month of May or June.
- What can you conclude about the Outcomes based on Goals?
For the ‘Outcomes based on goals’ data it can be seen that there were no plays canceled for any of the goal amounts between $1000 to $50000 or more. It can also be observed that the most successful plays had goal amounts between $35000 and $44999 at 66.67% while the highest amount of failed plays had goal amounts between $45000 and $49999 at 100%. From this information, Louise should look at having campaign funding goals for plays around $35000 to $40000 if she was looking to see more successful outcomes.

- What are some limitations of this dataset?
Some of the limitations of this dataset include the fact that this particular data set is rather vast in terms of studying the trends across the years as opposed to picking a specific year to observe the trends in outcomes and also the fact that the data was not filtered according to country as the outcomes of the production could vastly vary from country to country.

- What are some other possible tables and/or graphs that we could create?
One example of a table that could be created from this data to help in the analysis process would be making a pivot table that sorts the outcomes by the years of production instead of the months - this would apply to the ‘theater outcomes by launch date’ data. Another example of data that could be collected to see trends to help Louise with her analysis would be to create a pivot table that calculates the outcomes based on the average donations of a particular subcategory (for example theater) across various months of the year. This can also be sorted by country in order to have a smaller sample size and a column chart could be plotted in order to show the trends and observe which months seemed to have the highest average donations.
