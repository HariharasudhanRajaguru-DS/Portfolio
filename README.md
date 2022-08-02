### [IBM Capstone Project - Space X Falcon 9 First Stage Successful Landing Prediction](https://hariharasudhanrajaguru-ds.github.io/Project-1/) 

 
## Step 1 : Problem definition 
Countries are spending a vast amount of money to send satellites to space. Once a rocket reaches the right distance from Earth, it releases the satellite or spacecraft. The stages used in rockets are left in space as junk. Space X successfully brings its first stage back to earth safely. So that it can be used in the next space launches. It can save a lot of money. Initially, there are failures in bringing the first stage back to Earth. Nowadays Space X successfully brings back the first stage. In this project, we are going to find what are KPIs helping for a successful first-stage launch.

## Step 2 : Data collection 
The data of previous launches gathered from Space X Rest API, also from Wikipedia by Web Scrapping with Beautiful Soup(bs4). 

## Step 3 : Data Preparation
These data must be cleaned. With the help of Pandas data frame, we can able to view the data in dataframe. The data was wrangled for further analysis. There may be columns without values, few data may don't add any value to the analysis.

## Step 4 : Data Analysis (Exploratory Data Analysis - EDA)
Exploratory Data Analysis helps us to plot to scatter plots, bar charts and many more to identify the relationships between the key factors for a successful landing.

## Step 4.a : Analyzing the Launch site using Folium maps
The launch success rate may depend on many factors such as payload mass, orbit type, and so on. It may also depend on the location and proximities of a launch site, i.e., the initial position of rocket trajectories. Finding an optimal location for building a launch site certainly involves many factors and hopefully we could discover some of the factors by analyzing the existing launch site locations.


Marking all launch sites on a map
Marking the success/failed launches for each site on the map
Calculating the distances between a launch site to its proximities

From the analysis we can able to provide solutions for the following questions:

1.Are launch sites in close proximity to railways?

2.Are launch sites in close proximity to highways?

3.Are launch sites in close proximity to coastline?

4.Do launch sites keep certain distance away from cities?

Conclusions:

1.launch sites are in close proximity to equator to minimize fuel consumption by using Earth's ~ 30km/sec eastward spin to help spaceships get into orbit.
2.Launch sites are in close proximity to coastline so they can fly over the ocean during launch, for at least two safety reasons--
(1) crew has option to abort launch and attempt water landing
(2) minimize people and property at risk from falling debris.
3.Launch sites are in close proximity to highways, which allows for easily transport required people and property.
4.Launch sites are in close proximity to railways, which allows transport for heavy cargo.
5.Launch sites are not in close proximity to cities, which minimizes danger to population dense areas.

## Step 5 : Building Machine Learing model



