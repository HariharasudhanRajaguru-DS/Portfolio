### [IBM Capstone Project - Space X Falcon 9 First Stage Successful Landing Prediction](https://hariharasudhanrajaguru-ds.github.io/Project-1/) 

 
## Step 1 : Problem definition 
Countries are spending a vast amount of money to launch satellites in space. Once a rocket reaches the right distance from earth, it releases the satellite or spacecraft. The stages used in rockets are left in space as junk. Space X successfully brings its first stage back to earth safely. So that it can be reused in the next space launches. It can save a lot of money and reduce development time. Despite the initial failures, Space X has successfully brought back and reused the first stage. In this project, we are going to find the KPIs relevant for a successful first-stage launch.

## Step 2 : Data collection 
The data of previous launches were gathered from Space X Rest API, also from Wikipedia by Web Scrapping with Beautiful Soup(bs4).

## Step 3 : Data Preparation
The collected data must be cleaned. With the help of Pandas data frame, we can view the data in the data frame. The data was wrangled for further analysis. There may be columns without values, few data may not add any value to the analysis.

## Step 4 : Data Analysis (Exploratory Data Analysis - EDA)
Exploratory Data Analysis helps us to plot data into scatter plots, bar charts and many more to identify the relationships between the key factors for a successful landing.

## Step 4.a : Analyzing the Launch site using Folium maps

The launch success rate may depend on many factors such as payload mass, orbit type, and so on. It may also depend on the location and proximities of a launch site, i.e. the initial position of rocket trajectories. Finding an optimal location for building a launch site certainly involves many factors and hopefully we could discover some of the factors by analyzing the existing launch site locations.

This can be achieved by:
1. Marking all launch sites on a map; 
2. Marking the success/failed launches for each site on the map; 
3. Calculating the distances between a launch site to its proximities.

From the analysis, we are able to provide solutions for the following questions:
1. Are launch sites in close proximity to railways?
2. Are launch sites in close proximity to highways?
3. Are launch sites in close proximity to coastline?
4. Do launch sites keep certain distance away from cities?

Conclusions:
1. Launch sites are in close proximity to equator to minimize fuel consumption by using Earth’s ~ 30km/sec eastward spin to help spaceships get into orbit.
2. Launch sites are in close proximity to the coastline so they can fly over the ocean during launch, for at least two safety reasons– 
 (1)crew has option to abort launch and attempt water landing 
  (2)minimize people and property at risk from falling debris.
4. Launch sites are in close proximity to highways, which allows to easily transport the required people and property.
5. Launch sites are in close proximity to railways, which allows the transport of heavy cargo.
6. Launch sites are not in close proximity to cities, which minimizes danger to population-dense areas.

## Step 5 : Building Machine Learing model
In this step, the data collected has been split into train and test datasets.

I have used the following Machine Learning models: K Nearest Neighbor(KNN), Decision Tree, Support Vector Machine, Logistic Regression.

All the train data sets were fitted into the models and test data helped to predict the outcome of the trained models. Furthermore, the data were plotted into a confusion matrix to analyse the prediction vs actual results. Also, the model‘s accuracy has been calculated using score function to find the best model.

## Step 6 : Story Telling_Final Presentation
The PDF presentation provides the overall process and the outcomes of the complete project.

[IBM_Data Science_Capstone_Project_Fianl Presentation____](https://github.com/HariharasudhanRajaguru-DS/IBM_Data-Science-/blob/main/ds-capstone-template-coursera%20-Final%20submit.pdf)

____


### [Exercise : Face landmark detection](https://github.com/HariharasudhanRajaguru-DS/Data-scientist-exercises/blob/main/face.py)

Face lanmark detection 

![sample output](HariharasudhanRajaguru-DS/Data-scientist-exercises/blob/main/images/Face_landmark__PIC_68.png)








