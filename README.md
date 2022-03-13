# Kickstarting with Excel

## Performing an analysis on Kickstarter data

### To determine how different campaigns fared in relation to their launch dates and funding goals

## Analysis and Challenges

### I performed an analysis of Kickstarter outcomes, based on their launch dates, in Excel. I used a pivot table to find the number of theater campaigns that were successful, failed, and canceled based on when they were launched. Once my data was organized, I created a line graph to visualize the relationship between the outcome of the campaign and the month it was launched.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/100643519/158037696-a59b98ed-0933-4d5c-89c4-18e4eeb805eb.png)

### I also used Excel to find the percentage of plays that were successful, failed, and canceled based on their funding goals. I created a new sheet, in the Kickstarter workbook, to organize the data I was looking for. I created dollar-amount ranges for the goal amounts. I used the COUNTIFS() function to find the number of plays that were successful, failed, or canceled based on their goal amount. Then I used the SUM() function to find the total number of plays for each range of goals. Once I knew the total number of plays for each goal range, I used those numbers to calculate the percentage of plays that were successul, failed, and canceled. After my table was completed, I created a line chart to visualize the relationship between the goal-amount ranges and the outcomes.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/100643519/158038479-6ab15343-783d-4954-9763-52050c31a860.png)

### Initially, when I wrote the COUNTIFS() function, I was referencing the pledged column for my less than range. I checked my work on the first column before copying and pasting the formula in the other columns. I used the SUM() function in the cell under the Number Successful column, and the COUNTIFS() function in another cell to compare the total number of successful plays from my table and the original Kickstarter sheet. When the numbers were not equivalent, I looked through my formula and found the mistake. 

## Results

- May and June are the best months to launch a Kickstarter campaign for a theater project. December is the least successful month to launch a Kickstarter campaign for a theater project.

- The number of successful campaigns is much higher for campaigns that asked for less than $25,000.

- A limitation to this dataset is that it is only using data from Kickstarter. It doesn't take into account the outcomes of any projects that received funding through other sources.

- We could create additional tables or graphs that combined the funding goals and launch dates.
