# matplotlib
In this challenge, I first started with mouse data and the study results in two different files. In order to accurately compare Capomulin with the other drug regimen's, I merged these dataframes together and deleted duplicate data to create a clean dataframe. After this, I used the groupby function to calculate the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen (Table 1 below).

![Table 1](Images/Table_1.png)

Next, I showed the total number of timepoints for all mice tested by drug regimen in a bar chart using both pandas and pyplot.

![Bar Chart](Images/Bar_Chart.png)

Next, I used a pie chart to show the distribution of male versus female mice using both pandas and pyplot.

![Pie Chart](Images/Pie_Chart.png)

Then, I calculated the final tumor volume of each mouse across the four drug regimens chosen, Capomulin, Ramicane, Infubinol, and Ceftamin. I used this filtered data frame to calculate the IQR and outliers for each drug regimen. I used these values to create a box and whisker plot to show the distribution of the tumor volume for each treatment group.

![Box & Whisker Plot](Images/Box_Whisker_Plot.png)

Lastly, I created a line plot to show the tumor volume over time for a single mouse treated with Capomulin and calculated the correlation coefficient using a scatter plot to show the tumor volumne versus the mouse weight.

![Line Plot](Images/Line_Plot.png)
![Scatter Plot](Images/Scatter_Plot.png)
![Linear Regression](Images/Linear_Regression.png)

![Line Plot](Line_Plot.png)
![Scatter Plot](Scatter_Plot.png)
![Linear Regression](Linear_Regression.png)

**For this challenge, I worked with bootcamp members Kimberly Reitema and Saroja Shrestha.
>>>>>>> e2dd641b4081e283fd4b1272f3dc08e2e70191fa
