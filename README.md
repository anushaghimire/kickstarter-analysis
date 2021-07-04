# Kickstarting with Excel
## Overview of project 
### Purpose
The purpose of this analysis is to look at how theatre campaigns specifically "plays" performed in relation to their launch dates and their funding goals. We are also looking at the best time of the year to hold the campaign as well as to understand how much funding we need for our campaign to be successful.
## Analysis and Challenges
### Analysis of Outcomes based on Launch date
I performed an analysis of Theater outcomes of campaigns based on their launch date. As you can see on the chart, the most successful month that launched the most successful Kickstarter campaigns was May. After the May high of 111, there is a slow decline in successful campaigns through the summer months. Launches in the fall, the winter, and the springs months were mostly around 60 campaigns.  December had the worst month with the lowest number of successful campaigns of 37, almost equal to 35 failed launches. Overall the number of successful campaigns is higher than failed and canceled campaigns throughout the year. According, January had the highest number of canceled campaigns at 7, while the rest of the year monthly canceled campaigns were in low digits. 
![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85364095/124396157-cdd23580-dcbc-11eb-9049-834ef2ed2fde.png)

### Analysis of Outcomes Based on Goals
The campaign which had less than $1000 goals had the most successful outcome and lowest failed outcomes. There are not any projects that got canceled based on the goal amount, with the % canceled flatline at zero for all goals. I found that there is a 50/50 chance of successful and failed outcomes which has a goal amount of $15000 to $19999. The campaigns which had a budget of $4999 and less had the most successful results. We can see that the budget of $45000 to $49999 had 0% success and 100% failed outcome. 
![outcomes vs goal](https://user-images.githubusercontent.com/85364095/124396126-aa0eef80-dcbc-11eb-98f6-6ba361e2cdc5.png)

### Challenges and difficulty Encountered
The first difficulty while doing this analysis was to convert the date of both deadlines and launch to the readable format. But a quick google search was helpful. The next difficulty I faced was using the function COUNTIFS(). In retrospection, the COUNTIFS() function was working properly, but I did not account for the fact that using "> 1000" vs ">=1000", first one would exclude 1000 in counting, while the second one would include it. In essence, the excel function is only good if one understands the logic properly and completely.  
## Results
#### - What are two conclusions you can draw about the Theater Outcomes by Launch Date?
* The campaigns that were launched in May and June had the most successful outcomes. They both had more than 100 successful outcomes. I would advise launching Loise her Kickstarter in May or June. 
* I would not recommend launching theater campaigns in December and January because both months have the lowest number of successful outcomes. 
#### - What can you conclude about the Outcomes based on Goals?
* The lower the amount of the goal, the higher is the success rate. The campaigns which had goal amount of < 1000 and <= 4999 had the most successful outcomes which were over 70%. 

#### - What are some limitations of this dataset?
The one limitation of this data set is the duration of the campaigns. Although the data set presented here is extensive with a lot of details on where and when it does not have much information that could help pinpoint why certain campaigns failed. Did those failed campaigns due to lack of resources or people or other circumstances. A lot of failed campaigns during the month of December, did those fail due to Christmas/New year holiday activities or due to weather?  Did the time spend to promote the campaign had any influence on the outcomes?
#### - What are some other possible tables and/or graphs that we could create?
Another possible table one could create is to classify the countries into bigger geographic locations such as continents Europe, Asia, or locations with similar cultural and geographical links. The logistics of travel between two countries in Europe would be similar to two different states in the US, so summarizing the successes and failures based on locations can help pinpoint why certain campaigns failed. Moreover, Theater is very much dependent on the cultural aspect. Certain Hollywood movies are box office flops in Asia and vise versa as they can not capture the audience properly. A kissing scene, between two characters in a show, may be perfectly fine in one place, but the same could result in a ban in another location based on cultural limitations.    
