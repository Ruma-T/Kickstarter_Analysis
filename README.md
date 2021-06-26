# Kickstarting with Excel

## Overview of Project

Playwright Louise wanted to do crowdfunding campaign for her upcoming play "Fever" with $10,000. As it is a big amount to start with, she wanted to know whether there are specific factors which she needs to consider making her endeavor successful.
As a student of Data Analytics, we would be using our knowledge of Excel to help her find best time for launching date with respect to the months and fundraising goal comparing with percentage successful, failed, and canceled campaigns. 
We would be presenting her two pivot charts to show the differences visually, so that she would be able to get a better view of the numerical data representation.

### Purpose
Our purpose is to find out the trends using right tools for deeper analysis in excel with the help of conditional formatting using available data from previous years. Using the data, we would organize, sort, and analyze previous crowdfunding projects and make a line chart to visualize the information available briefly to her.
For Launch date, we would be representing month wise successful, failed, and canceled plays whereas, in outcome based on Goals, it would be according to the range.

## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date

Line chart drawn from pivot table shows the month wise successful, failed, and canceled Theater campaign adding a new column withb Year.
 
•	This pivot chart clearly shows, May is the best month to start the campaign and throughout summer it can work well. 
•	As expected, winter is not a good time for successful outcomes for theater.
•	Overall theater campaign was successful 60% and above 


![png_Theater_Outcomes_vs_Launch](https://github.com/Ruma-T/Kickstarter_Analysis/blob/a670a4f6cd09d7e3d80345482fbe17275377cd6e/Resources/Theater_Outcomes_vs_Launch.png)



### Analysis of Outcomes Based on Goals

According to the ranges given from less than 1000 to more than 50000 goal, percentage successful, percentage failed,and percentage cancelled plays were showed in the graph using COUNTIFs() functions and filters.. 
 •	This graph has both positive and negative slope throughout the range 1000 to 50000. 
 • There is an interesting pattern in the curve where sudden increase and decrease slope is seen cause of which could be explored more to maximize the goal.


![png_Outcomes_vs_Goals](https://github.com/Ruma-T/Kickstarter_Analysis/blob/87172aed1181383a45abb15c94915904abe0e19c/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
•	Being new to the Excel and programming, initially it was challenging for me to use conditions like Count If and CountIfs. 
•	Second challenge, I had to face is the range for 50000 and greater. Previous range was 44999 to 49999. According to the instruction ranges, 50000 was not counting. So, I had to include 50000 and greater, maintaining the similarity with the previous ranges. 
•	Third challenge, I faced was I did not save all my practice worksheets, and they were not organized and saved for Module1 challenge.
•	Finally, the size of my excel file was too big even after I zipped. I had overcome that by deleting all other sheets I prepared for practice. Now it is well below 25 MB. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

•	According to the Launch Date outcome, May is the most successful time to start a kickstarter campaign.
•	Throughout the summer it works well, especially Mar to May it has increasing trend whereas May to September it has decreasing trend; and she should avoid winter. 

- What can you conclude about the Outcomes based on Goals?
•	There is a negative slope from 1000 to 19999; whereas there is a positive slope from 30000 to 39999 and again negative slope from 40000 to 49999. 
•	100% campaign failed from 45000 to 49999
•	Though more than 70% successful campaigns were in the range of 1000 to 5000.
•	Louise should target 30000 to 50000 to maximize her campaign goal.


- What are some limitations of this dataset?
•	The dataset used is few years old, and in current situation of covid, there might be a sharp decline in in-person plays which will give a biased analysis.
•	The genre of the play is not defined here as there are different play lovers for different genre . This analysis is based on overall play kick starters data.


- What are some other possible tables and/or graphs that we could create?
•	We could have included year wise kick starters outcome.
•	We also could have included outcome based on country, so that Louise can have some idea where she can launch the Kickstarter campaign.
•	Pledged vs goal graph 



