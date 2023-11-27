# Exploratory Analysis of Restaurants in Chicago
Analyzing restaurant data in Chicago and locating the two nieghborhoods with the highest density of failed restaurant inspections. Answering some general questions about this data from the data frame, as well as performing some basic statistical analysis comparing the two neighborhoods to the rest of the city.

## Data Analysis
Looking at a heatmap of the city of Chicago, we can see the hotspots of locations where we see multiple failed food inspections are most dense in.

![Heat Map of Chicago](https://github.com/dpatt830/Restaurant-DataFrame-Project2/master/map.png? "Map of Chicago")

The two densest areas of multiple failed resturant inspections are located along the street in northern Chicago Devon and the street in southern Chicago, Cermak. These streets are both home to large ethnic populations and their respective neighborhoods are Little India and Chinatown. 

Knowing that these are where most of failed food and restaurant inspections are located, we can see how each neighborhood compares to the rest of the city's restaurants. 

![Bar Graph](https://github.com/dpatt830/Restaurant-DataFrame-Project2/blob/master/bar.png? "Bar Graph")
![Data Table](https://github.com/dpatt830/Restaurant-DataFrame-Project2/blob/master/data_table.png? "Data Table")

The data table depicts the total number of inspections over a ten year period, and how many have passed or failed and where the restaurant was located in. The bar graph displays the number of failed inspections as a percentage relative to the number of resturants in that area, and compares those percentages to each location.

Looking at the data, we can see that the percentage of failed restaurant inspections between the whole city and Chinatown are very similar, but Little India has a larger percentage of failed inspection compared to the two other locations.

To test a location's signifcance on the inspection result, three chi-squared tests were take. First, a chi-squared test comparing the three locations (Chinatown, Little India, and the Rest of Chicago) to see if location was significant on the result of the inspection. Then two following tests to see if there were significant differences in failed inspections among the two neighbor hoods compared to the rest of the city. 

The results of each test are as follows:
*	**All Locations** :
  * Chi-Squared = 33.51157988326079
  * Resulting p-value = 5.2850960980274587e-08
*	**Chinatown vs. Rest of City**: 
  * Chi-Squared = 3.0671475475622234
  * Resulting p-value = 0.07988953622172074
*	**Little India vs. Rest of City**: 
  * Chi-Squared = 30.588134772465153
  * Resulting p-value = 3.190388850340393e-08

From the resulting tests it can be concluded that there is a significant relationship between location/neighborhood and inspection result, and the probability of failed inspection for restaurants in Devon/Little India is significantly greater than the rest of the city. 

As we can see there are apparent significant differences in failed food inspections and overall a high volume of failed food inspections in two highly populated ethnic communities in Chicago. Further research should go into what causes these failed inspections in these two neighborhoods. Could it be the number of restaurants in the area, the restaurants not following food safety protocols, or ethnic biases?
