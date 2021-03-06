# Battle-of-the-Neighborhoods
## Introduction
The basis of this report is to provide insight to anyone planning on opening a sushi franchise in 5 metropolitan locations within the United States. The United States has seen a flood of restaurants open and fail within the first year of opening. Clients interested in opening restaurants of any kind need to find the best location that will produce the most income. Most restaurants fail because they don’t get enough business, and most restaurants don’t get enough business because they aren’t a convenient option. This is especially important with niche food choices where choosing the right restaurant location can mean the difference between a thriving restaurant and one that was barely able to close out their first year.
## Business Problem
A potential client is interested in starting a sushi restaurant franchise and needs to know which of the 5 chosen locations would be best situated to begin the franchise. However, he does not know which location would be best suited for his beginning franchise. The client does not like to have a lot of competition as individuals that enjoy sushi are part of a niche group of cliental.The factors to consider are:
- The right target audience
- Population
- Demographics
- Number of competitors
## Data Set
Five total cities will be examined:
-	Lansing, MI
-	Grand Rapids, MI
-	Ann Arbor, MI
-	Traverse City, MI
-	Royal Oak, MI
### Data Set 1
Geographical coordinates data will be utilized as input for the Foursquare API, that will be leveraged to provision sushi restaurant venues information for each neighborhood. We will use the Foursquare API to explore neighborhoods in the noted cities above.
### Data Set 2
I will also be leveraging Wikipedia on population densities within the cities noted above. 
- https://en.wikipedia.org/wiki/Lansing,_Michigan 
- https://en.wikipedia.org/wiki/Grand_Rapids,_Michigan 
- https://en.wikipedia.org/wiki/Ann_Arbor,_Michigan 
- https://en.wikipedia.org/wiki/Traverse_City,_Michigan 
- https://en.wikipedia.org/wiki/Royal_Oak,_Michigan
### Data Set 3
I will be leveraging Wikipedia on demographics within the cities noted above: 
- https://en.wikipedia.org/wiki/Lansing,_Michigan#Demographics 
- https://en.wikipedia.org/wiki/Grand_Rapids,_Michigan#Demographics 
- https://en.wikipedia.org/wiki/Ann_Arbor,_Michigan#Demographics 
- https://en.wikipedia.org/wiki/Traverse_City,_Michigan#Demographics 
- https://en.wikipedia.org/wiki/Royal_Oak,_Michigan#Demographics
## Methodology
Data will be colleceted from Foursquare API for venues and then filtered by Sushi restuarant.

Data will be collected from Wikipedia for population and demographics then cleansed and stored within a local .csv file for easy consumption.

Finally, the data be will be visually assessed using graphing from various Python libraries
## Results
Examining the data from Foursquare we can see that there are multiple sushi restaurants located in each city. Total Number of Sushit Restaurants in: 
- Lansing, MI = 51
- Grand Rapids, MI = 55
- Traverse City, MI = 4
- Royal Oak, MI = 31
- Ann Arbor, MI = 61
This does not mean, however, that we automatically pick the lowest competition dense city as we also need to consider population desity.
![Lansing, MI](https://github.com/twmcintire/Battle-of-the-Neighborhoods/blob/master/Lansing.PNG)
Lansing, MI
![Grand Rapids, MI](https://github.com/twmcintire/Battle-of-the-Neighborhoods/blob/master/Grand%20Rapids.PNG)
Grand Rqapids, MI
![Traverse City, MI](https://github.com/twmcintire/Battle-of-the-Neighborhoods/blob/master/Traverse%20City.PNG)
Traverse City, MI
![Royal Oak, MI](https://github.com/twmcintire/Battle-of-the-Neighborhoods/blob/master/Royal%20Oak.PNG)
Royal Oak, MI
![Ann Arbor, MI](https://github.com/twmcintire/Battle-of-the-Neighborhoods/blob/master/Ann%20Arbor.PNG)
Ann Arbor, MI

Demographics is the next thing that was examined. 
![Demographics](https://github.com/twmcintire/Battle-of-the-Neighborhoods/blob/master/demographics.PNG)
Reviewing the data above for population and demographics on race and age, we can see that just because Traverse City only has 4 sushi restaurants it only has a population of 14674. So we need to determine the saturation point of a sushi restaurant.
## Discussion
As a final note, all of the above analysis is depended on the adequacy and accuracy of Four Square data. A more comprehensive analysis and future work would need to incorporate data from other external databases.
## Conclusion
Looking at the data for each city we can digest the following for each sushi restaurant there is the potential for X number of customers per city:
- Lansing Sushi Restaurant to Population Lansing:          2241
- Lansing Sushi Restaurant to Population Grand Rapids:     3419
- Lansing Sushi Restaurant to Population Traverse City:    3669
- Lansing Sushi Restaurant to Population Royal Oak:        1846
- Lansing Sushi Restaurant to Population Ann Arbor:        1868

Reviewing the data it would be the client's best option to open a starter franchise in either Traverse City or Grand Rapids because the compeition is relatively the same. One factor to keep in mind is that the Asian population according tot he 2010 Census shows that only 102 individuals living in Traverse City is of Asian decent whereas in Grand Rapdids there are 4323 individuals of Asian decent.
