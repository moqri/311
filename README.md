# 311 - A Real-world Data Science Project 
#### A Project of Data Smart City Colution - Ash Center at Harvard Kenedy School (http://datasmart.ash.harvard.edu/)

# Objective
The city of Somerville, MA is among the leading innovators for 311 services in the US. While a small city, the customer-service approach, passion for advancing the public good and willingness to try new things set Somerville 311 apart from its peers. Somerville recently created a regional 311 administrators network for other small and mid-sized cities in the Boston region. Participants include Chelsea, Malden, Revere, Everett, Cambridge and others. This network is seeking a research partner for a pro bono (or nominal stipend) research project. The ideal candidate is a graduate student seeking a summer project or a fall 2017 research project. A researcher completing a summer project may be invited to present at the inaugural Harvard Data-Driven Government Conference in November 2017. 
The purpose of the research project is to use open data available in Somerville and many other cities, to answer the following questions:
Key questions:
• What 311 call types are predictors of property crime? (311 call types that are correlated with property crime (burglary, larceny, motor vehicle theft) occurring after the 311 call with a lag of 1 week to 1 month) for a city? For a neighborhood? 
• What 311 call types are predictors of violent crime? (311 call types that are correlated with violent crime (homicide, rape, robbery, aggravated assault) occurring after the 311 call with a lag of 1 week to 1 month) for a city? For a neighborhood?

# Preparation
0. Create a Github account and fork this project
1. Install Python 2.7
2. Add Python Pandas Package
3. Install Jupyter Notebook

# Data
https://raw.githubusercontent.com/moqri/311/master/311_Constituent_Services_Daily_Calls.csv

# Analysis
## Step 1: Standardization
At this stage we standardize the data so that our analysis could be replicated for other cities in future
### Code
https://github.com/moqri/311/blob/master/311_transformation.ipynb

To open the code you need to have Jypouter Notebook installed
### Demo
http://bear.warrington.ufl.edu/analyticslab/311/311_transformation.html

## Step 2: Exploration
At this stage, we explore and visualize the data to understand the context and find interesting patterns in the data
### code
https://github.com/moqri/311/blob/master/311_exploration.ipynb

### Demo
http://bear.warrington.ufl.edu/analyticslab/311/311_exploration.html

## Step 3: Aggregation
At this stage, we aggregate the data based on time and lcoation
### code
https://github.com/moqri/311/blob/master/311_aggregation.ipynb

### demo
http://bear.warrington.ufl.edu/analyticslab/311/311_aggregation.html
## Step 4: Correlation
At this stage, we add the crime data and see if there is any correlation between 311 reports and crime
### code
https://github.com/moqri/311/blob/master/311_crime.ipynb

### Demo
http://bear.warrington.ufl.edu/analyticslab/311/311_aggregation.html

## Issues
When you encounter an issue, please use the issue button on this page and submit an issue first
Then, if you could find the fix, please send me a pull requst. If you can't find the solution, I'll to my best to address the issue
