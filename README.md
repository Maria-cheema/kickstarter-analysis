# Kickstarting with Excel

## Overview of Project 
In the data we had to import the data into table for analysis. The projects consisted of applying filters, formulas, generating and interpreting the pivot table and pivot charts.

### Purpose
The purpose of this project is to do the comparison of the finding results of the campaigns based of their Outcomes Based on Launch Date and goals. We explicitly looked at the results of theaters and plays to find which ones were successful, failed and canceled.
Another purpose to of this project was help us learn how to use different exercises to get your results such as: converting Unix Timestamps into month/day/year format, using Pivot Table and Pivot Charts to show specific data like theaters and provide the visual summary of the outcomes by using charts.

## Analysis and Challenges
Much of the data analysis achieved by filtering the data simply by the theater and play trends. 
Two factors were analyzed, Outcomes Based on Launch Date and Outcomes Based on Goals.
After looking at the data few conclusions can be drawn.

### Analysis of Outcomes Based on Launch Date
By looking at the line chart below when campaigns were created and ended. We can conclude that in the month of May-June-July trend for theater seems to be more successful and success rate to be falling in the month of Jan-Feb and lowest in the month of December
![image](https://user-images.githubusercontent.com/120526544/209026287-25fb5b50-5bd1-46d8-af60-e523cf2670a2.png)

### Analysis of Outcomes Based on Goals
The data was again filtered in the data set for the play subcategory. Goals were varied from <1000 and >50,000 in the group of $5,000 to show the total number of successful, failed, and canceled outcome for each and convert in into percentage. There is about 50% chance for theater play to be successful if the goal is less than $20,000. From this we can conclude that higher the campaign goal, less chance of becoming successful and more chances of being failed campaign.
![image](https://user-images.githubusercontent.com/120526544/209026350-6d4846bf-ebda-4543-ab5a-d504086cefb8.png)

### Challenges and Difficulties Encountered
One of the challenges, I confronted was with the COUNTIFS statement. I thought if I drag it down across cells, it’ll automatically adjust it, but this was not the case. I had to change the figures in each cell. Another thing was percentage canceled projects had zeros, which I checked and verified the formula for accuracy. I filtered the raw data to confirm my finding about 0 plays canceled. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
By viewing the line graph the two conclusions I can draw are the May and June months to be successful in launching theater project and December to be the least successful month. Another conclusion to draw is that there were 0% theater projects cancelled. 

- What can you conclude about the Outcomes based on Goals?
By looking at the graph, you can conclude that play campaign with higher goal to be failing and not successful. Therefore, we see that the project goal less than $5000 were to be more successful.

- What are some limitations of this dataset?
Some of the limitations of this dataset were canceled theater projects as there were not examples given in subcategory. Another was to identify the gender to help determine the targeted audience. 
- What are some other possible tables and/or graphs that we could create?
A graph to show the comparison of the countries in determining which campaigns are more successful in certain countries.

