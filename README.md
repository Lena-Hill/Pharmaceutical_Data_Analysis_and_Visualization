Module 5 Challenge: Data Visualization

Overview
In this project we were asked to analyze mouse study data for a pharmaceutical company. We were provided with two data sets: mouse metadata and study results. 

Dependencies
For this project we used: 
  Pandas
  matplotlib.pyplot</li>
  scipy.stats</p>

Data Preparation
1. Combine CSV files
    Read the CSV files
    Combine the two files using the common column'Mouse ID'
2. Check mice count
    Check the total number of mice in the combined dataframe. This dataset contains 249 mice
3. Remove duplicates using the 'duplicated' function
    Check for mouse IDs with duplicate time points.
    Display the data associated with duplicate mouse IDs. 
    Create a cleaned dataframe with duplicate data removed

Summary Statistics included mean, median, ariance, standard deviation, and SEM of the tumor volume for each regimen using the 'groupby' and 'agg' functions.

We performed the following data visualization: 
1. Bar plot using Pandas to show the total number of rows (Mouse ID/Timepoints) for each drug regimen.
2. Repeated the first plot using Matplotlib
3. Created two pie plots using Pandas and Matplotlib
4. Box plot usining Matplotlib to show the distribution of the final tumor volume for mice in each treatment group
5. Line plot and Scatter plot: We generated a line chart of tumor volume vs timepoint for a single mouse treated with Capomulin, and a scatter plot of mouse weight vs average tumor volume for the entire Capomulin treatment group.
6. Linear regression model between mouse weight and average tumor volume for the entire Capomulin group.
7. Linear Regression between weight and average tumor volumes for the entire Capomulin group.
8. We then plotted the linear regression model on top of the scatter plot to visualize the relationship between mouse weight and average tumor volume.

Analysis:
The linear regression mmodel showed a positive correlation between tumor volume and mouse weight, to no one's surprise. The study showed varying efficacy among the different regimens. Further insights could be gained by delving deeper into specific aspects of the study, or posing additional questions. 

Resources: 
Thanks once again to the UT Data Bootcamp course materials including recorded lectures, Google, classmates, ChatGPT, and YouTube. 
