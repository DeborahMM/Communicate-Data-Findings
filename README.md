# Communicate-Data-Findings
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.

## Dataset
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area (San Francisco, East Bay, San Jose). This dataset requires some data wrangling in order to make it tidy for analysis. There are multiple data files that will need to be joined together for a full year’s coverage. The combined 2018 Ford GoBike System Data contains 1,863,721 trips. 156,703 points were removed from the analysis due to inconsistencies.

(Source of the Dataset: https://s3.amazonaws.com/fordgobike-data/index.html)


## Software
Python (Numpy, Pandas, Matplotlib, Seaborn, datetime, haversine, glob)
Jupyter Notebook 


## Summary of Findings
Material included in the explanatory presentation:
- An overwhelming number of users are subscribers.
- Although the correlation map revealed a positive strong linear relationship between the trip distance and trip duration, the plot matrix did not show a correlation which may be due to the use of electric bikes and regular bikes. 
- The average distances are similar, but customers have slightly higher averages. 
- The most frequently used trips last 5-10 minutes during peak hours on the weekdays from April through October among customers and subscribers. 
- The most frequently used trips are 0.5-1 km during peak hours on the weekdays from May through October among customers and subscribers.


Material NOT included in the explanatory presentation:
- The trip duration and distance distributions are skewed to the right with a number of unusual outliers.
- The overall monthly bike ride gradually increased and plateaued, peaking in October. 
- The hourly bike trend is binomial with peaks at 8 AM and 7 PM.
- While the highest peak is on Tuesday, followed by Wednesday and Thursday, the lowest peaks are on the weekend. 
- The most popular trip is from the San Francisco Ferry Building (Harry Bridges Plaza) to the Embarcadero at Sansome St.
- The trip durations for both the customers and subscribers are right-skewed, even more so for subscribers. However, the average is 13 minutes for customers and 9 minutes for subscribers. 
- Also, the trip distances for both the customers and subscribers are right-skewed, even more so for subscribers. However, the average distances are similar. 


## Key Insights for Presentation
The behavior of customers and subscribers during peak hours were further analyzed.


## List of Sources
- Importing multiple csv files: https://stackoverflow.com/a/21232849 
- Haversine package description: https://pypi.org/project/haversine/
- Communicate Data Findings: Example Project (Udacity Resource)
