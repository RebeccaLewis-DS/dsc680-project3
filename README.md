# A Data Story about a Bike that Goes Nowhere
## DSC 680 - Applied Data Science - Project 3

Peloton® is a digital workout provider that sells fitness equipment along with a streaming subscription for cycling, strength, running, and other floor workouts. Motivation is a requirement for sticking to any routine. Knowing your motivating factors and using them strategically can lead to success in achieving your goals.  The online fitness community provides many avenues of motivation including community, convenience, competition, and data. Developing a reproducible method to identify the factors that can improve performance and results can allow users to benefit even more from their investment.  This project examined the Peloton® workout history for an individual user to determine the factors that influence their performance, correlation between workouts and weight, and improvement in overall fitness over time.  The relationships between performance metrics were identified during correlation analysis.  Visualization confirmed consistent activity overall was associated with weight loss; however, exercise was not the biggest contributing factor.  Modeling using a blended regression algorithm was able to successfully rate each workout based on the average metrics during the cycling workout.

### Contents
Root
- Project Proposal - LewisRebecca_Project3_Proposal.pdf
- Final Paper - LewisRebecca_Project3_Paper.pdf
- Final Slides - LewisRebecca_Project3_Presentation.pptx
- For a recorded presentation in mp4 format, please contact me at revlewis79@gmail.com.

Data
Data was downloaded using a specific user account from the Peloton API and Apple Health Kit in the Data Wrangling Script.  To download your own data, you must have an active peloton account.  If you do not, you may use the datafiles included here:
- instructors.txt - Instructor information in JSON format
- workouts.txt - details on workouts completed in JSON format
- workout_summary.txt - general information about the workouts in JSON format.
- workout_performance.txt - performance metrics for each workout in JSON format.
- weight.csv - Apple health metrics

Scripts
Scripts must be executed in this order:
- LewisRebecca_Project3_DataWrangling.ipnyb - Data Wrangling using Python within Jupyter Notebook - Must have a peloton user account to run this script.
- LewisRebecca_Project3_DataPreparation.ipnyb - Data Preparation using Python within Jypyter Notebook
- LewisRebecca_Project3_DataProfiling.ipnyb - Data profiling using pandas-profiling library in Python within Jupyter Notebook
- LewisRebecca_Project3_EDA.ipnyb - Exploratory Data Analysis using R within Jupyter Notebook
- LewisRebecca_Project3_Modeling.ipynb - Predicting the Difficulty Rating using pycaret in Python within Jupyter Notebook

### Requirements
Python 3 in Jupyter Notebook - Packages include pandas, numpy, pycaret, datetime, pandas-profiling, json, requests, xmltodict
R in Jupyter Notebook - Packages include ggplot2, tidyverse, ggcorrplot, reshape2, zoo, corrplot, Hmisc, PerformanceAnalytics, Ggally, R.utils

### Usage
1. Download the files in the same folder structure.
2. Unzip the data.zip into the data folder.
3. Run the scripts in the following order:
    1. LewisRebecca_Project3_DataWrangling.ipnyb - Must have a peloton user account to run this script.
    2. LewisRebecca_Project3_DataPreparation.ipnyb 
    3. LewisRebecca_Project3_DataProfiling.ipnyb 
    4. LewisRebecca_Project3_EDA.ipnyb
    5. LewisRebecca_Project3_Modeling.ipynb 














