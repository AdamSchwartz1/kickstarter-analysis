# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this project was to assist Louise in her quest to run a successful kiskstarter campign. Her goal was to raise enough money to fund her play. I used excel to manipulate data from over 4000 kickstarter campaigns to try and analyze trends based on simliar projects and what their outcomes were.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The first analysis I did was to look at the outcomes based on when the theater campaigns were started. The table I created focused on successful, failed, and canceled campaigns and the months when they began. This is the line chart I created to demonstrate my findings. 
![Theater_Outcomes_vs_Launch](/Theater_Outcomes_vs_Launch.png).

### Analysis of Outcomes Based on Goals

For the analysis of the outcomes based on the goal of the campaign, I narrowed the results to look at plays specifically. In this search, I found the number of successful, failed, and canceled play campaigns as well as the percentage of each of those outcomes. I used this line graph to demonstrate my findings. 
![Outcomes_vs_Goals](/Outcomes_vs_Goals.png).

### Challenges and Difficulties Encountered

One of the challenges I faced was getting the correct format for the "countif" formula for the outcomes based on goal analysis. I originally filtered the kickstarter sheet to "successful" and "plays" but then realized that information would not hold when those filters were removed. I decided to add those conditional arguements to the count if statement so the formula showed exactly what we were looking for and so it was easy to use the same formula in the other colums while just changing the outcome status. Another difficulty I had was figuring out how to get the line chart formatted correctly for the outcomes based on goals analysis. When I created the graph, the y-axis values were not formatted correctly and the legend names weren't what I wanted them to be. Through some research, I was able to change the axis values to a percentage format and I was able to rename the legend values.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

I came up with two conclusion from the outcomes based on launch date graph. First, I found that campaigns started in Late spring and early summer had the most successful campaigns. Out of the 839 successful theater campaigns, 44 % of them happened between April and July.

Second, I found that December is the worst month to start a campign. December only had a 49% successful campaign rate while the next lowest success rate was October with 57%.

- What can you conclude about the Outcomes based on Goals?

My conclusion from the analysis on the outcomes based on goals was that the lower the goal, the more likely you were to have a successful outcome. If your goal was set at less than $20,000, you have a 68% chance at having a successful campaign.

- What are some limitations of this dataset?

One of the main limitations of this dataset that I noticed is that this data was from campaigns started between 2011 and 2017. It's hard to gauge how well a project might fair in 2021 because there's no data in the last year or two to back it up. A couple factors about the age of this data is that more people may know about kickstarter now and are willing to donate and the value of inflation is not accounted for.

- What are some other possible tables and/or graphs that we could create?

Another table I created to look at for my analysis was a stacked bar graph for the outcomes based on goals. If you put the total projects as the y-axis, the goal ranges on the x axis, and the number of successful, failed, and canceled items as the stacked columns, it does a really nice job showing the distribution of outcomes. You can see that a high volume of campaigns have a goal of less than $15,000 and that you have a high chance of running a successful campaign if your goal is less than $5,000.
