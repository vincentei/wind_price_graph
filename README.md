##### Summary
The scatterplot shows the relation between the average daily wind energy and the whole sale electricity price in Germany. Each dot represents a weekday (excluding weekends/mondays) in the year 2015. When there is more wind energy, prices for electricity tend to be lower.


##### Design
The main story I want to tell is how daily wind energy influences electricity prices in Germany. I want to show in an interactive way that on days with lots of wind, prices for electricity are lower than on days with less wind. For this, the initial idea was to draw two timeseries (wind and price) with length of a year. The timeseries must appear gradually on the screen so that the viewer could see how on days with high wind energy prices are lower.  

To draw a timeseries that appears smoothly on the screen was quite a challenge. In the end I used a "curtain" method to slowly reveal the timeseries. After collecting feedback it became clear that showing two timeseries is not the most effective way of visualising the effect of wind energy on electricity prices. Therefore I changed the chartype to a scatter plot.

For the color of the dots I used a color from colorbrewer.org. Avoiding on purpose 'hard' colors as these are unpleasant to look at.

A tooltip is added so the viewer could inspect the dots and see the values.

##### Feedback
The following persons are asked for feedback:
Carolina (my girlfriend)
Tom (colleague same team)
Henry (colleague other team)

###### First design - index1.html
The feedback here is that the timeseries is not showing smoothly on the screen (it does appear gradually but with shocks). Other feedback is that if I want to show the influence of wind on price I might be better making a scatter plot instead of drawing two time series at the same time.

###### Second design - index2.html
After experimenting a bit I am able to draw a timeseries that appears smoothly on the screen. I use a "curtain" that disappears gradually. Feedback here is that the timeseries does not focus on the relation between wind and prices. So I will revert to making a scatter plot.  

###### Third design - index3.html
Feedback here is:
Put the axis labels on the outside.
Cut off the x-axis
Include a tooltip

###### Final design - index_final.html
See index_final.html

##### Resources
stackoverflow
http://bl.ocks.org/
colorbrewer.org
udacity.com


