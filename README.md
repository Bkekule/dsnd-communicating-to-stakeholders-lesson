
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Stack Overflow data from 2017 to better understand:

1. How other developers suggested breaking into the field (what education to pursue)?
2. What factors about an individual contributed to salary?
3. How bias played a role in the suggestions of developers for how to break into the field?
4. What was the state of bootcamps for assisting individuals with breaking into developer roles?
5. How were bootcamps assisting with increasing diversity in tech careers?

The full set of files related to this course are owned by Udacity, so they are not publicly available here.  However, you can see pieces of the analysis here.  This README also serves as a template for students to follow in creating their own project README files.


## File Descriptions <a name="files"></a>

1. `HowToBreakIntoTheField.ipynb` - Explores what current developers recommend for breaking into the field. Analyzes the `CousinEducation` survey column to rank suggestions (online courses, books, bootcamps, etc.) and investigates whether recommendations differ based on the gender of the person asking (bias analysis).

2. `BootcampStats.ipynb` - Investigates the impact of coding bootcamps on job placement and salary. Compares bootcamp graduates to non-bootcamp respondents across gender diversity, formal education levels, time-to-employment after graduation, and salary distributions.

3. `Salary.ipynb` - Builds predictive models for developer salary using sklearn's LinearRegression. Walks through iterative feature engineering with both numeric and categorical variables, evaluates model performance (R-squared), and identifies which factors most influence salary.

4. `Salary_ML.py` - A standalone Python script containing reusable functions (`clean_data` and `find_optimal_lm_mod`) for the salary prediction pipeline. Handles data cleaning (missing value imputation, dummy variable creation) and finds the optimal linear regression model by testing different feature-count cutoffs.

Each notebook is exploratory in nature, with markdown cells walking through the thought process for individual steps.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).  Otherwise, feel free to use the code here as you would like! 

