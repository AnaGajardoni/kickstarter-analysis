# Kickstarting with Excel

## Overview of Project
Louise is a playwriter who wants to start a $10,000 crowdfunding campaign for her next play. In order to help Louise with the funding, we analysed data from Kickstarters trying to relate successful (and unsuccessful) fundings to different variables such as goal, pledge, date the funding started, etc in the search of patterns that might guide her make a more reasonable decision.


### Purpose
The purpose of this project is to find out how viable it is to have/start a funding for a theater/play that needs $10,000 and, based on data gathered at Kickstarter funding, advise Louise on making decisions to maximize her chances of success.


## Analysis and Challenges
In the data used for our research, there were more than 4,000 records of campaigns. The target of the campaigns was diverse: from film to food, from photography to technology, from games to journalism. With such diversity, one of the challenges encountered was to make as truthful conclusions as possible, filtering data that would be most relevant.

Another challenge was to understand data - that is not always readily available. In this case, we could list two minor adjustments: dates were recorded in Unix format and had to be converted and there was just one column listing Category/Subcategory which had to be split so we could make more precise queries. 


### Analysis of Outcomes Based on Launch Date
On a first analysis, the focus was to understand how relevant Launch Date was to a successful outcome. For that, the initial mass of data was narrowed down to show only the parent category of interest (theater) and the number of outcomes were grouped according to each possible outcome (successful, failed and canceled) in a pivot table. The idea was to find if there was a pattern throughout the year - following the seasons, for instance. 

When examining the chart based on the table created, we can clearly see that May is the most promising month to launch a funding campaign like this. Not only does it have the most successful campaigns, but it is also in May that lies the biggest gap between successful and failed/canceled projects.

### Analysis of Outcomes Based on Goals
The analysis based on goals, on the other hand, focused on the most successful intervals for goals. The outcomes were split in the following intervals
 * less than 1000 (<=1000)
 * greater than 1000 and less than 4999 (>=1000 and <4999)
 * greater than 5000 and less than 9999 (>=5000 and <9999)
 * greater than 10000 and less than 14999 (>=10000 and <14999)
 * greater than 15000 and less than 19999
 * greater than 20000 and less than 24999
 * greater than 25000 and less than 29999
 * greater than 30000 and less than 34999
 * greater than 35000 and less than 39999
 * greater than 40000 and less than 44999
 * greater than 45000 and less than 49999
 * greater than 50000


### Challenges and Difficulties Encountered

## Results



- What are two conclusions you can draw about the Outcomes based on Launch Date?
The biggest challenge is the mass of data itself - that is not large enough to really make a good conclusion. 

The data was filtered so as to show the spread of outcomes (successful, failed and canceled) throughout a calendar year covering all the data available (from 2009 to 2017) only for the category of interest. The chart below shows clearly that the best month to lauch a campaign is May - but not only that - May is also the month in which the gap between successful projects and failed or canceled ones is the biggest.

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?



This project aims to analyse data from Kickstarters taking into account Goals, Pledges, How Successful the funding was (some fundings go really beyond their initial goal), Dates the funding happened so as to understand whether our client Louise's project 
 In analysing such information, the project searches for patterns and clues to help understand the chances of success of a given project.
