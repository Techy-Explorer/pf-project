# Data Processing Project

## Student Information
**Name:** [Farhan Ali]  
**Roll No:** [012]  
**Section:** [BSDS-1A]  
**Subject:** [Proramming Fundamental]
**Project:** [Data Analysis]  

## Project Description
This project focuses on analyzing and processing of the data set of titanic survivals , onboarding **"titanic.csv"** dataset.The dataset includes **419 rows and 12 columns** of data related to  individuals' Name, such as age, survival levels, gender, and ticket and  other facilities.

The primary objectives are to clean, preprocess, and analyze the data to extract meaningful insights and trends related to Titanic Event.
 The project employs **Python's pandas library** for data manipulation and exploratory analysis.



### Dataset Details:
- *Rows:* 33
- *Columns:* 11
- *Attributes:* Includes various columns depending on the dataset used, such as numerical, categorical, and calculated fields. The attributes will be manipulated using functions to derive meaningful results.


### Project Objectives:
 *Data Cleaning and Preprocessing:*
   - Handle missing values effectively.
   - Rename or reformat columns for better usability.
   - Filter and sort data as needed.
   - and the total analysis performance.

     2. *Statistical Summaries:*
   - Use functions to calculate mean, median, mode of the given data of the people in titanic like a record of it, and other descriptive statistics.
   - Summarize data trends, such as totals and averages.

 *Visualization:*
   - Develop plots (bar charts, histograms, etc.) using functions.
   - Display trends visually for easier interpretation.
  
  ## for using graph .
   
df[["Survived"]].value_counts().plot(kind="bar",title="Survived_Persons",color="black")
here this code is use to present the data of specified data in the set

## for cleaning the null values.
df.dropna(inplace=True)
here each null values which is making the data set uncleaned is removed for the ease of data analysis


 *Function Design:*
   - Create reusable Python functions for:
     - Data filtering and grouping.
     - Statistical calculations.
     - Visualization generation
    
# why we use data set in our programming field?
## Key Insights
- Functions simplify repetitive tasks, enhancing code efficiency and readability.
- Statistical and visual analyses reveal trends and patterns in the dataset.
- The project highlights the importance of modular programming in data analysis.


## Tools and Libraries Used
- *Python*
- *pandas* for data manipulation
- *matplotlib* and *seaborn* for visualization

- metabolib is used for usually plotting graphs and visualizations etc.


## Future Enhancements
- *Interactive Dashboards:* Incorporate libraries like *Plotly* or *Dash* for dynamic visualizations.
- *Machine Learning Integration:* Use the preprocessed data for predictive analytics.
- *Advanced Statistical Functions:* Introduce hypothesis testing and correlation analysis
    

