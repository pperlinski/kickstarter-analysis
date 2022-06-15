# An Analysis of Kickstarter Campaigns
Analyzing Kickstarter data to find trends

## Project Overview

The goal of this project was to identify possible trends in the rates of success or failure of Kickstarter campaigns, particularly in the category of theater and plays, and see if any conclusions could be made from the observations. In this scenario, the client, Louise, is planning the crowdfunding of her play “Fever” with a prospective budget of $10,000. The objective was to help her determine not only what her odds of success may be, but how she might be able to modify her launch strategy and budget to have a better fundraising outcome. 

## Analysis and Challenges

The raw tabulated sample set consisted of 4113 Kickstarter campaign launches over several years in a Microsoft Excel worksheet. The data is broken down by country, currency (all monetary amounts are calculated in US dollars), various categories and subcategories, goal amount, pledge amount, and dates of launch. The data on its own is too vast to be combed through individually, and making any meaningful connections while the data is presented in such a raw format can be tedious if not practically impossible. The first thing that needed to be done was to organize the data, and present it in such a way that the bigger picture could be seen at a glance. To do this we filtered the data, then using pivot tables and charts, we were able to sort and visualize it in ways that made sense to our goals.

## Optimizing Launch Dates

The first graph we produced from the data was a line chart of Kickstarter outcomes based on launch date. Categorized by successful, failed, canceled, and live campaigns, we were able to determine an optimal launch month from the campaign by being able to easily visualize all the data from the chart we made below. The pivot charts also let us filter by year, and by specifically the theater category, so our data isn’t contaminated by campaigns in other industries and fields.

We can see that May would be the ideal month to launch the campaign, as that month has the highest success funding kickstarters in the theater category. This makes sense possibly because it’s after tax season, people have money to spend, and they might be open to funding a play if they think it can get produced over the summer, a season in which people typically go out and visit venues more often. The winter would be the worst season, and probably because people’s money is going towards holiday shopping and traveling. So from analyzing this chart we’ve been able to optimize the timing of Louise’s campaign launch. But what about our budget? 
What is the optimum financial goal to set for the campaign to have the best odds of success?

## Kickstarter Goals and their Outcomes

Here we can see the relationship between a kickstarter campaign’s goal and whether it succeeded or failed (canceled campaigns are at a consistent zero throughout since there were no canceled campaigns in our sample of plays). There is an inverse relationship between how much a kickstarter campaign for a play asks, and its chances of success. Successful campaigns outnumber failed campaigns when cheap and barely any campaigns succeed past the 45 thousand dollar mark. However, looking at the graph, one might think there is suddenly a reversal of the relationship between the 35 and 40 thousand dollar amounts. It’s not that asking for more money suddenly makes people want to fund it more. It’s just that in the sample, the amount of kickstarters asking for that kind of money decreases as we go up the goal amount. There were only ten kickstarter campaigns asking between 35 and 40 thousand dollars, therefore we can’t make too good of a judgment of the correlation at this point because our sample becomes bottlenecked at this point and too small. However, the number of campaigns 20 thousand dollars and below is just over one thousand. We have a much better idea of the overall trend of success or failure here because our sample size is larger and we have more data. Judging from what we can see here, Louise’s best option would be to try and decrease her budget as much as possible. If she could cut her budget for the play in half or less she could significantly improve her odds of reaching her fundraising goals.

## Summary

In conclusion, we can determine that in order for Louise to have the best chance of success, she should launch her campaign in May, and reduce her budget down as much as she realistically can in order to improve her odds of having a successful fundraiser. The dataset can’t account for extraneous factors that might influence the funding of kickstarter campaigns, like if the economy was good that year, and outliers skew the data in specific places, but overall we were able to extract valuable knowledge from the data and were able to point Louise in the right direction.

	
