# Kickstarting with Excel

## Overview of Project
### Purpose
This project is a detailed analysis of a large set of Kickstarter data that has been combed through and analysed for visual understanding. Several conclusions and charges have been put together using skills and tools learned on Excel.

## Analysis and Challenges
Upon analyzing the Kickstarter data, I carefully combed through the data by first organizing the original data sets. The original data set ended in column N and was further extended using excel tools to allow better interpretation of the data. Columm O was a percentage calculation that was rounded using the =ROUND() function. After copying the data to all the cells and applying a color scale conditional formating, we can visually see that the red cells are 0% funded and blue are 100% or more. A similar conditional formatting was applied to the outcomes column where red was failed projects and green were successful projects. A potential challenge would have been separating Column N, Category and Subcategory, if the data was not split between a backslash. Excel does offer a fantastic tool called "Text to Columns" that allows the user to split data in a cell to mulitple columns for further organiztion. This would cause an issue if the column was sorted in several diffrent ways instead of one continuous method. A new skilled learned was converting Unix Timestamps in to a readable format. The data set used Unix timestamps that were in their raw format. The formula =(((J2/60)/60)/24)+DATE(1970,1,1) was used to conver these into a human-readable date that could be easily analyzed even further. Although the data set had over 4,000 rows, excel did majority of the work as it is an excellent tool to analyze data sets as long as the user knows what he or she is looking for. I believe that this project is not as challenging as what is to come in our Bootcamp.

### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The Theater outcomes have the most successful projects in May. Canceled projects do not have much of a variance as they range between 3 - 4 cancelled projects each month with the exception of January which has the most canceled shows by double (7). It is fair to say that canceled shows are not dependant on independant months or volume of projects. We can also say that failed projects average around 40 with December almost tying to the same amount of successful projects as failed. After the month of May, successful theater projects decline at a steady rate as failed project remain contstant. We can assume that there are other factors playing significant roles on the success of a play.


- What can you conclude about the Outcomes based on Goals?

Smaller projects with goals less than $5,000 are largely more successful than the larger projects with the exception of projects in between $35,000 - $44,999. Its fair to say that since the number of projects total 9 projects between the 2 data points, it can be seen as these projects were unique since the successful line has a natural declining slope and is inversely related to the number of failed projects. 

- What are some limitations of this dataset?

Out of the total of 1,047 projects, 720 are less than 4,999 which means that there are more values available to projects less than $4,999 to get a better representation of the percentage of successful projects. It could be fair to say, with a larger data set, the graph could show a smoother decline in successful projects as the goal increases. Another limitation would be the popularity of each project could play a significant role on whether the project has a higher change of being pledged/backed. This could give us a better understanding on why some of the larger projects were greatly successful. 

- What are some other possible tables and/or graphs that we could create?

A great table to create would be a representation between the outcomes of each project vs the timeframe. We could see how the timeframe could affect the success of a goal at various goal points. Another great table would be the amount of backers for each project versus the outcome. It could be that larger amount of backers could lead to higher success rates and could potentially be evidence of popularity of each project. I find that popularity of a project could be a huge quantitative data set that could give further insight on why certain projects succeed and other fail. 
