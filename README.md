# Module 1: Kickstarter

Data Analysis Of Kickstarter Campaigns In The US and Great Britain

Overview of Project
Analysis was performed on kickstarter campaigns conducted in the United States and Great Britain. The purpose of this research was to identify variables which contribute to the success of fundraising campaigns such as date launched, length of campaign, and fundraising goal. These insights will help Louise make informed decisions about her kickstarter campaign.

Analysis and Challenges
I began by changing data formats on a few items and converting unix timestamps to readable dates (see screenshot "ConvertUnixTimestampToReadableDate"). It was a bit difficult to understand how unix timestamps work but after re-reading the material several times I now comprehend how they work. I filtered the data and created pivot tables/charts which highlight outcomes based on date and outcomes based on goals. With pivot tables I had some challenges determining which items to place in filters and values. I manipulated these items on the pivot table, observed what changes occurred, and with practice I determined how to properly configure count, values, rows and columns. Rounding to a percentage was a challenge (see screenshot "RoundingToPercentageWasChallenging"). After repeated attempts, trial and error, and re-reading the material I was able to accomplish the task. I applied conditional formatting to certain columns such as "Outcome". I used IFERROR function to input a specified value for cells which had null values. I created subcategories so we could drill down in the data to find campaigns that were similar to Louise's. Pivot tables and charts were created to visually present the trend lines. Scientific notation is still a difficult concept for me to grasp so I will need to research that further.

Results Based On Launch Date
Campaigns launched in May or June tend to yield the highest success rates. It would be wise for Louise to have her campaign running during these months. In contrast, December tends to have the least number of successful campaigns, picking back up again around February. For this reason I would not recommend running campaigns in December or January.

Results Based On Fundraising Goals
The data indicates that if you set your fundraising goal too high your campaign is less likely to be successful. Goals less than $1000 tend to be the most successful (82% success rate) with $1000-4999 coming in 2nd place with a 73% success rate. From there the success rate progressively declines as the fundraising goal amount increases. There is some deviation from this pattern with $35000-39000 and $40000-44999, both yielding a 67% success rate.

Limitations Of This Dataset
Outliers in the data (failed kickstarters with really large goals) skewed the distribution. This led to the failed kickstarters to have a higher standard deviation (3 times the IQR) whereas campaigns with other outcomes had a standard deviation of roughly 2 times the IQR. These outliers should be examined and possibly removed if they do not accurately represent the distribution.

Other Tables And Graphs
A pivot table and pivot chart could be created to analyze whether the "deadline" for a campaign has an impact on the success rate. The data could be filtered to examine particular months or specific times of a given month.