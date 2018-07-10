---
layout: post
title: Project 1 - WTWY MTA
---
Back Story:
WomenTechWomenYes(WTWY) has an annual gala at the beginning of the summer each year. WTWY is looking to fill the 
event with individuals passionate about increasing women presence in technology, and continue to build awareness in tech.
WTWY wants to place street teams at NYC subway stations to collect emails and send out tickets to the gala to individuals who signed up.
WTWY hired us to analyze New York MTA subway station data, to optimize the placement of outreach teams. 

Objective:
Maximize attendees to the WTWY gala.
Make optimal use of WTWY resources.

Sumary of Recommendations:
We recommend WTWY to send out the outreach teams on Tuesday, Wednesday and Thursday to the following stations grouped by amount of resources:

|Minimum Resources|More Resources|Many Resources|
|-----------------|--------------|--------------|
|Grand Central|Grand Central|Grand Central|
|Union Square|Union Square|Union Square|
|		  |23rd Street   |23rd Street   |
|                 |Penn Station  |Penn Station  |
|                 |              |Herald Square |
|                 |              |59th Street/Lexingtion|

Summary of Approach:
Besides ridership data obtained from the MTA website we also analyzed the proximity of staions to biggest tech companies, and to universities in NYC.
In addition, we looked at the demographic data of the area near subway station with a focus on percent of women and education level in that area.

Factor 1 - Ridership:
Assumptions and Data Selection: We assumed that the next event is scheduled for the end of June 2019; therefore, we focused on analyzing MTA ridership data from May and June of 2018. 
We observed in the data that some turnstile entry counter has been reset, resulting in extreme outliers in daily entries data for those turnstiles. We set a cut-off at 250,000 entries per day, 
based on the maximum daily entry value reached at the busiest station - Penn station. 
The top 25 stations with the highest total entries for two months are listed below: 
|#|STATION|TOTAL ENTRIES|
|1|Penn Station| 8,323,703|
|2|Grand Central| 7,358,475|
|3|34 ST-Herald SQ| 5,873,328|
|4|23 ST| 5,459,788|
|5|14 ST-Union SQ| 5,248,712|
|6|42 ST-Port Auth| 5,055,567|
|7|Fulton ST| 4,904,257|
|8|Times SQ-42 ST| 4,627,688|
|9|86 ST| 4,187,086|
|10|125 ST| 4,090,078|
|11|Canal ST| 3,950,373|
|12|59 ST Columbus| 3,418,306|
|13|Path New WTC| 3,375,987|
|14|59 ST| 3,303,662|
|15|96 ST| 3,256,211|
|16|Flushing-Main| 2,908,865|
|17|14 ST| 2,849,220|
|18|Chambers ST| 2,819,174|
|19|JKSN HT-Roosvlt| 2,634,502|
|20|47-50 STS Rock| 2,529,138|
|21|28 ST| 2,355,283|
|22|50 ST| 2,300,911|
|23|72 ST| 2,174,790|
|24|Atl Av-Barclay| 2,145,434|
|25|Jay ST-Metrotec| 2,020,911|

Factor 2 - Proximity of Stations to Major Tech Companies
WTWY is focused on inviting women in tech to their gala; therefore, we believe our analysis will add more value by researching which stations are close to major tech companies headquartered in NYC, 
thereby increasing the likelyhood of reaching out to the right target audience who are working in tech companies. 
We approached the problem by first finding the top 30 tech companies, by employee count, that are headquartered in NYC and measured the straight-line distance between each tech company to each individual station. 



![alt_text](http://zwmiller.com/projects/images/monte_carlo/part5/business_impact.png)
