# An Analysis of Kickstarter Campaigns

## Overview of Project
This project uses a Kickstarter dataset to uncover trends related to the Arts & Media field, particularly plays. This project analysis is intended for Louise.

### Purpose
The purpose of this analysis is to gain insights on how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges
The dataset needed additional columns to analyse the data (e.g. Category & Subcategory column got split into 2 extra columns to show the parent category and the subcategory). By performing this split, it was easier to manipulate the data for a detailed analysis.

### Analysis of Outcomes Based on Launch Date
I am mainly focusing on 3 outcomes in this analysis (successful, failed and canceled) of Plays based on their launch date. In order to do this, a "years" column needed to be created to get the year the campaign was launched, so I can see seasonal trends during the year. 
I notice that the highest number of campaigns (166 total) launched was in May. May also had the most successful number of campaigns, however I notice a decline around the end of the year (oct-dec) resulting in the increase in failed campaigns during that period. The number of cancelled plays is fairly consistent throughout the year, peaking a bit in January, where Holiday season or back-to-work might be a factor.

### Analysis of Outcomes Based on Goals
In this analysis, I want to analyse the percentage of successful, failed and canceled plays based on the funding goal amount. In order to tackle this problem, the data needed to be displayed and summarized in a manner where I can capture the data in different buckets of goal amount. A new sheet was created and with the use of formulas, I was able to get the amount of plays based on their outcome, within each goal amount range.
I notice that there are a lot more successful plays where the goal range is lower than $15K (even better if it is lower than $5K) and in the range of around $35K-45K. No plays got canceled throughout the years, irrespective of their goal amount, making the outcome binary; where lots of plays were successful, we had lower number of failed plays, and vice versa.

### Challenges and Difficulties Encountered
The challenge I faced in this project was using the COUNTIFS function. I was not aware of the parameters the formula takes, so that got me Googling a bit and understanding how it works. The video in the hint of the assignment was very helpful as well.
But the main challenge I will find soon is how to use Git and/or Github to upload my file and add pictures to my README doc. I'm leaving this part to after I complete and write this documentation (:


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
I notice that the highest number of campaigns (166 total) launched was in May. May also had the most successful number of campaigns, however I notice a decline around the end of the year (oct-dec) resulting in the increase in failed campaigns during that period. The number of cancelled plays is fairly consistent throughout the year, peaking a bit in January, where Holiday season or back-to-work might be a factor.

- What can you conclude about the Outcomes based on Goals?
I notice that there are a lot more successful plays where the goal range is lower than $15K (even better if it is lower than $5K) and in the range of around $35K-45K. No plays got canceled throughout the years, irrespective of their goal amount, making the outcome binary; where lots of plays were successful, we had lower number of failed plays, and vice versa.

- What are some limitations of this dataset?
The lack of data specifically on plays in the dataset to make a more insightful analysis. Only ~26% of the dataset is related to plays (or 1066 out of 4114 datapoints). Also the dataset is limited to only one platform (Kickstarter); it would be great to also see if we come to the same conclusions based on another dataset from another crowdsource platform (like answering questions like "are campaigns tend to be more successful in May?" etc)

- What are some other possible tables and/or graphs that we could create?
Other tables of other subcategories could be beneficial to cross check if Louise should better invest her time and effort elsewhere where there are more successes. We can also create a table to see the ratio of pledged amount to goal amount, so that Louise can have a more realistic ballpark on how much she should aim. Creating multiple Pivots and charts will help summarize and get an overall view of the Arts & Media field.
