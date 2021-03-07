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

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
