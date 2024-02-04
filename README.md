# python_api_challenge
WeatherPy Analysis:
The weather analysis of over 500 cities around the globe showed the relationship between various weather metrics and distance from the equator. The strongest relationship was found between an increase in temperature with an increase in absolute value of latitude. Lesser relationships were seen between humidity and cloudiness with an increase in absolute value of latitude, and no correlationship was seen between wind speed and latitude.

While the analysis was set to randomly pick cities throughout the entire globe, the actual results were skewed towards the northern hemisphere. This could be largely due to the population density of the southern hemisphere vs the northern hemisphere. Few cities exist between latitude -50 to -90 (including only Antartica and the tip of South America), whereas latitude 50 to 90 includes all of Canada, Russia, some of Europe, and more. Looking at the information behind the citypy package which was used to randomly choose the cities (https://github.com/wingchen/citipy/blob/master/README.md), the nearest city is chosen to a set of coordinates randomly given. Even if a random latitude on the southern hemisphere was given (i.e. -70), the closest city might be quite far away in a more positive latitude. Therefore with more data points, the examined relationships are stronger in the northern hemisphere than in the southern hemisphere.


Sources Used: 
for creating scatter plots: https://www.w3schools.com/python/matplotlib_grid.asp
for annotating linear regression plots: 
https://www.geeksforgeeks.org/matplotlib-pyplot-annotate-in-python/