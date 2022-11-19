# Exploratory Data Analysis
The required resources for this assignment is available hereLinks to an external site.

This coding challenge is designed to test your skills on how to perform exploratory data analysis and give you the opportunity to understand and analyse data using descriptive statistics with python coding language.

Please deliver your answers as if you were handing off work to someone who does not know anything about the data or Machine Learning.

Here’s what to concentrate on while you deliver any of you assignments:

Explain your approach/methods, conclusions, and any/all assumptions
Clearly document and structure your code
Describe any ideas you attempted that didn't work
Describe interesting ideas you didn't have time to complete; but would have tried if you were to have more time on your end.
Please answer all questions and submit your answers on Canvas before the deadline (Sept 6th 6p CT)

## Submitting your work:
Once you are done create a compressed file called yourUTEID_a1.zip. Upload/Submit this file on the canvas before the due date.

Task Details:

For this assignment we use the data collected from National Health and Nutrition Examination Survey.

Data fields and Data Dictionary

SEQN – Respondent Sequence Number.  Both males and females 12 YEARS - 150 YEARS

ALQ101 - Response variable. 1: YES, 2: NO,9: DON’T KNOW

Survey Question: In any one year, have you had at least 12 drinks of any type of alcoholic beverage?

ALQ110 – Response variable. 1: YES, 2: NO,9: DON’T KNOW

Survey Question: In your entire life, have you had at least 12 drinks of any type of alcoholic beverage?

ALQ130 – Response variable.

Survey Question: In the past 12 months, on days that you drank alcoholic beverages, on the average, how many drinks did you have?

SMQ020 – Smoked at least 100 cigarettes in life; 1: YES, 2: NO, 7: REFUSED, 9: DON’T KNOW

RIAGENDR – Gender value

RIDAGEYR – Age in years at screening

RIDRETH1 – Race/Hispanic origin

DMDCITZN – Citizenship Status

DMDEDUC2 – Education Level – Adults 20+

DMDMARTL – Marital Status

DMDHHSIZ – Total number of people in the household

WTINT2YR – 2year MEC exam weight. Value of 0 means not Examined.

INDFMPIR – Ratio of family income to poverty

BPXSY1 – Systolic: Blood pressure (first reading) mm Hg

BPXDI1 – Diastolic: Blood pressure (first reading) mm Hg

BPXSY2 - Systolic: Blood pressure (second reading) mm Hg

BPXDI2 - Diastolic: Blood pressure (second reading) mm Hg

BMXWT – Weight (kg)

BMXHT – Height(cm)

BMXBMI - Body Mass Index (kg/m**2)

BMXLEG - Upper Leg Length (cm)

BMXARML - Upper Arm Length (cm)

BMXARMC – Arm Circumference(cm)

BMXWAIST – Waist Circumference(cm)

HIQ210 – Time when no insurance in the past year. 1: YES, 2: NO,9: DON’T KNOW

 

### Question 1 
Load, read and clean/preprocess (if required) the data​ ​file.

Import required libraries. Describe the data with plots and explain your work about any patterns you find about this dataset.

Do you find any interesting relationships between any data fields in the data? Show your work and explain all your findings about the dataset.

 

### Question 2 
Get the stats about the proportion of women and men who smoke.

Let’s say, our hypothesis is the proportion of women who smoke is equal to the proportion of men who smoke.

Write the code and explain your findings and your inference.

 

### Question 3 
Get the stats about the percentage of datapoints in the population that have graduated college (using the educational attainment variable DMDEDUC2).

Analyze (if any) the relationship between Education Level (DMDEDUC2) and Ratio of family income to poverty (INDFMPIR)
