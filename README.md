
## Project Overview

For this project, we'll use data cleaning, imputation, analysis, and visualization to generate insights for a business stakeholder. We'll be using Python's Pandas for data manipulation and Matplotlib for visuzlizations.

## Business Understanding

Stakeholders's company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. We are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. We'll translate findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

##  Data Understanding and Analysis

### Source of data
We'll be using [dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters. The data has no copyright, meaning that we can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

### Description of data

The data comes from National Transportation Safety Board aviation accident [dataset](https://www.ntsb.gov/Pages/AviationQueryV2.aspx).
The accident data has been in collecion since the 40s. During the decades the dataset schema changed: new variables got added, some variables stoppped being reported, for some variables reporting format had changed. 
That being said, the dataset is not uniform and contains a lot of missing data.

The dataset contains 31 columns (mix of numerical and categorical) and 90348 rows. Each row has represents details about a reported accident or incident.

### Data Cleaning

We're going to perform initial cleaning to get rid of duplicates in Make and Model. 
We'll use column with FAR description codes to identify commercial flights and update information in column describng Purpose of the Flight.


### Selecting relevant columns

We'll be using columns describing injury count and type, columns describing make and model, date, and purpose of the flight to determine the additional filtering.

![](results/nj_By_FlightPurpose_Unfiltered.png)

### 


### Historical data 
![](results/nj_By_FlightPurpose_Unfiltered.png)


Three visualizations (the same visualizations presented in the slides and notebook)


## Conclusion


Summary of conclusions including three relevant findings