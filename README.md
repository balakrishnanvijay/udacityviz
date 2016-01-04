# Final project for Udacity Viz course by Vijay Balakrishnan

##Summary: 

I chose the baseball player performance dataset. It has some very good Measures like the average and the Home Runs. Baseball being a athletic game, it has some relevant phyical dimensions of players like height, weight, handedness. I wanted to assess the impact of height and weight on a player's performance - Average & HomeRuns. I also intended to bring out the correlation between the handedness and the effect of the physical parameters on performance.


##Design: 

- It was a case of distribution/spread across various (3) parameters - hence bubble chart was a natural choice to represent all of this together. 
- Handedness was the low cardinal categorical variable and hence was a natural choice to represent color
- I initial tried to represent the difference in height in terms of the radius of the bubble but it wasnt very visually apparent as the range was too small
- Based on feedback, I switched to Home Runs for the variation in radius and also switched to 2 separate bubble charts for height and weight separately as each had a varying impact. 
- Based on feedback, I also enabled animation and filtering based on selection of the handedness from the legend and this enabled analysis of each of those categories separately.


##Feedback:

1. One of the most popular feedback I received for my initial version was to switch from Height to Home Runs for the radii of the bubbles
2. Another important feedback was that in order to make the visualization self-explanatory and interactive, I need to bring-in filtering based on the Handedness selection from the legend
3. Also, one of my colleagues advised me to include animation so that people understand when a Handedness category vanishes from the chart
4. A feedback that I transformed was to show height and weight as dual axes ... this helping to tell a story and hence I switched to 2 separate charts for each of those dimensions


##References:
1. https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.axis#title
2. http://stackoverflow.com/questions/25416063/title-for-charts-and-axes-in-dimple-js-charts
3. http://www.lornajane.net/posts/2013/dimplejs-bubblescatterplots-and-joind-in-data
4. https://github.com/PMSI-AlignAlytics/dimple/blob/master/examples/advanced_lollipop_with_hover.html
5. http://dimplejs.org/advanced_examples_viewer.html?id=advanced_price_range_lollipop




