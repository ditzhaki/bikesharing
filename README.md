# NYC Citibike Bikesharing

## Overview

The focus of this challenge is to explore the possibility of starting a bikeshare business (like that of citibike in nyc) for the town of Des Moines, Iowa. With potential investors already identified, the goal is to convince them that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis. 

Although Des Moines is vastly different than New York City, analyzing data from Citibikes can help identify some key points such as who uses the bikeshare program, when, and where. The Tableau Story containing the relevant visualizatinons  can be found at the following [link](https://public.tableau.com/app/profile/diana6142/viz/NYCCitibikeAnalysis_16585883991620/NYCCitibikeAnalysis?publish=yes).

## Results

### Customer Breakdown

To kick off our analysis, we can dive into the breakdown of the types of customers and genders that use the bikeshare program.

![Customer Type](https://user-images.githubusercontent.com/101564349/180615551-0abfa2fc-04b2-47b1-a8e2-5e12a3516722.png)

Our first visualization shows that those who use the bikeshare program are split between short term customers and annual subscribers, with subscribers accounting for over 75% of users. 

We can similarly explore the gender breakdown of the users.

![Gender Breakdown](https://user-images.githubusercontent.com/101564349/180615739-7e5f1338-49be-4a73-a8b1-d76d7d45f98f.png)

From our pie chart, we can see that majority of users are males accounting for approximately 65% of users while females only made up approximately 25%. The remainder are unknown / undeclared. 

### Checkout Times

The next portion of our analysis depicts the checkout time for users.

![Checkout Times for Users](https://user-images.githubusercontent.com/101564349/180615989-30b8309b-10a6-48cc-8bef-620e4ce659e2.png)

From the figure above, we can see the relationship between the number of trips and their duration. The graph shows that the majority of trips are under a half-hour in length with a steep drop as the duration increases to an hour. We can further analyze the relationship by breaking it down by gender.

![Checkout Times by Gender](https://user-images.githubusercontent.com/101564349/180616307-6df210c0-3fc2-4fff-992a-216e2a7a0277.png)

The relationship between number of trips and their duration remains the same for each gender. This visualization further supports that majority of users are those that identify as male.

### Trips by Weekday

Next, we can take a look into the relationship between the number of trips and the weekday through the use of a heatmap. The heatmap helps show weekly usage patterns. 

![Trips by Weekday](https://user-images.githubusercontent.com/101564349/180616681-7371b28b-8145-4648-ae4e-3ab92db04b64.png)

From our heatmap, we can see that the majority of bike trips occur during the weekday (Monday - Friday) and specifically, during commute times (morning and evening). On the weekends, we can see that majority of bike rides inversely occur in the middle of the day. We can further break down this data by gender. 

![Trips by Gender](https://user-images.githubusercontent.com/101564349/180617132-c0ca58a3-6020-4798-a99b-1275f5c74da7.png)

Breaking it down by gender reveals the same pattern that the number of trips occurring are done mostly by males while the pattern between number of trips and commute time remains the same for each gender.

### User Trips by Gender

To conclude, we can look at a heatmap that summarizes the patterns we have seen from the visuals above.

![User Trips by Gender](https://user-images.githubusercontent.com/101564349/180617242-4c3208bd-6828-4694-9249-42b7d5cf6b1f.png)

The heatmap is broken down by user type, gender, weekday, and number of trips. This heatmap reinforces how much of the userbase is dominated by male, subscribing users.

## Conclusion

In summary, it is clear that Citibike is popular within New York City where there is a dense population, constant traffic, and limited parking. The user base consists of mostly male individuals and subscribers who travel by bike at peak commute times. 

Two additional visualizations that should be performed with the given data are:

* Trip duration & Number of rides by age to explore the impact that age may have on citibike participation.
* Start and end locations during peak commute times to explore the neighborhoods with the most bikers. 
