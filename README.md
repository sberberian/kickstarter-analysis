# Kickstarting with Excel

## Overview of Project

### Purpose
After the success of Louise's play, Fever, the following analyses were developed to compare the outcomes of various other campaigns using their launch dates and funding goals as a basis. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The first analysis seen below visualizes the volumes of campaigns with different outcomes across the month that they were launched. I created the chart based on a pivot table using the fields for parent category, years, outcomes, and launch date. Then, I adjusted the formatting to clear the buttons, added a title, and changed the colors. Now, it is clear to see which months had the most success or lack thereof and which months had the most canceled projects. 

![Theater_Outcomes_vs_Launch](C:\Users\saman\Downloads\Data Bootcamp\Crowdfunding Analysis\Challenge 1\Resources\Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The second analysis in the image below demonstrates the pecentage of plays within each outcome across the several ranges of funding goals. I pulled the quantities within each goal range for each outcome and summed every range in a new column. Finally, I took the sum of every range and divided them by the quantity for the outcomes down the rows to populate the percentages. The chart shows where the most and least successful funding goals are. 

![Outcomes_vs_Goals](C:\Users\saman\Downloads\Data Bootcamp\Crowdfunding Analysis\Challenge 1\Resources\Outcomes_vs_Goals.png) 

### Challenges and Difficulties Encountered
One brief trouble I had during the launch date analysis was remembering how to remove the filtering buttons on the chart to make it look more neat. After toggling with the various buttons and chart settings, I realized they could be hidden by simply right-clicking on the buttons and choosing to hide them. 

The main issue I faced with the funding goals task was when using the CountIf function to calculate the play quantities with the various filtering involved. When the formula kept failing, I reviewed the CountIf function more closely and realized the number filter for the funding goal range needed to have parenthesis around them. 

## Results

The launch date chart is clear that the most successful time to launch a theater campaign would be in May. However, May does have the most failed theater campaigns as well as October. It seems that it is better to launch as early in the summer as possible.

The funding goal chart demonstrates that lower goals have the highest chance of success with a decline as the goal size increase with the exception of a positive spike from 35000 to 44999. 

Limitations of this dataset include the fact that it is only a sample of all campaigns held. An additional analysis could be done to isolate the most successful play campaigns and observe if there is any connection between the topic of the plays and their success. 
