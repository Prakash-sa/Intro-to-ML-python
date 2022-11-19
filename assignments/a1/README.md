{\rtf1\ansi\ansicpg1252\cocoartf2706
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 HelveticaNeue-Bold;\f1\fnil\fcharset0 HelveticaNeue;\f2\fnil\fcharset0 HelveticaNeue-Italic;
}
{\colortbl;\red255\green255\blue255;\red34\green45\blue53;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c17647\c23137\c27059;\cssrgb\c100000\c100000\c100000;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa120\partightenfactor0

\f0\b\fs43\fsmilli21600 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Exploratory Data Analysis
\f1\b0 \
\pard\pardeftab720\sa240\partightenfactor0

\f0\b\fs32 \cf2 The required resources for this assignment is available\'a0{\field{\*\fldinst{HYPERLINK "https://utexas-my.sharepoint.com/:f:/g/personal/jyothi_vinjumur_ischool_utexas_edu/ElH0cJCgAnJGvf5wGCQLZXUBPvoo4cjH4zAssq0bXO5HEg?e=I2KHyr"}}{\fldrslt \ul here\cb1 \ulnone \
\pard\pardeftab720\partightenfactor0
\cf2 \cb3 \ul \ulc2 Links to an external site.\cb1 \ulnone \
}}\pard\pardeftab720\sa240\partightenfactor0

\f1\b0 \cf2 This coding challenge is designed to test your skills on how to perform exploratory data analysis and give you the opportunity to understand and analyse data using descriptive statistics with python coding language.\
Please deliver your answers as if you were handing off work to someone who does not know anything about the data or Machine Learning.\
Here\'92s what to concentrate on while you deliver any of you assignments:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0\cf2 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Explain your approach/methods, conclusions, and any/all assumptions\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Clearly document and structure your code\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Describe any ideas you attempted that didn't work\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Describe interesting ideas you didn't have time to complete; but would have tried if you were to have more time on your end.\cb1 \
\pard\pardeftab720\sa240\partightenfactor0

\f0\b \cf2 \cb3 Please answer all questions and submit your answers on Canvas before the deadline (Sept 6
\fs24 th
\fs32 \'a06p CT)
\f1\b0 \
\pard\pardeftab720\sa120\partightenfactor0

\fs36 \cf2 Submitting your work:\
\pard\pardeftab720\sa240\partightenfactor0

\fs32 \cf2 Once you are done create a compressed file called\'a0
\f2\i yourUTEID_a1.zip
\f1\i0 . Upload/Submit this file on the canvas before the due date.\
Task Details:\
For this assignment we use the data collected from National Health and Nutrition Examination Survey.\
\pard\pardeftab720\sa240\partightenfactor0

\f0\b \cf2 \ul \ulc2 Data fields and Data Dictionary
\f1\b0 \ulnone \
\pard\pardeftab720\sa240\partightenfactor0

\f0\b \cf2 SEQN
\f1\b0 \'a0\'96 Respondent Sequence Number. \'a0Both males and females 12 YEARS - 150 YEARS\

\f0\b ALQ101
\f1\b0 \'a0- Response variable. 1: YES, 2: NO,9: DON\'92T KNOW\
Survey Question: In any one year, have you had at least 12 drinks of any type of alcoholic beverage?\

\f0\b ALQ110
\f1\b0 \'a0\'96 Response variable. 1: YES, 2: NO,9: DON\'92T KNOW\
Survey Question: In your entire life, have you had at least 12 drinks of any type of alcoholic beverage?\

\f0\b ALQ130
\f1\b0 \'a0\'96 Response variable.\
Survey Question: In the past 12 months, on days that you drank alcoholic beverages, on the average, how many drinks did you have?\

\f0\b SMQ020
\f1\b0 \'a0\'96 Smoked at least 100 cigarettes in life; 1: YES, 2: NO, 7: REFUSED, 9: DON\'92T KNOW\

\f0\b RIAGENDR
\f1\b0 \'a0\'96 Gender value\

\f0\b RIDAGEYR
\f1\b0 \'a0\'96 Age in years at screening\

\f0\b RIDRETH1
\f1\b0 \'a0\'96 Race/Hispanic origin\

\f0\b DMDCITZN
\f1\b0 \'a0\'96 Citizenship Status\

\f0\b DMDEDUC2
\f1\b0 \'a0\'96 Education Level \'96 Adults 20+\

\f0\b DMDMARTL
\f1\b0 \'a0\'96 Marital Status\

\f0\b DMDHHSIZ
\f1\b0 \'a0\'96 Total number of people in the household\

\f0\b WTINT2YR
\f1\b0 \'a0\'96 2year MEC exam weight. Value of 0 means not Examined.\

\f0\b INDFMPIR
\f1\b0 \'a0\'96 Ratio of family income to poverty\

\f0\b BPXSY1
\f1\b0 \'a0\'96 Systolic: Blood pressure (first reading) mm Hg\

\f0\b BPXDI1
\f1\b0 \'a0\'96 Diastolic: Blood pressure (first reading) mm Hg\

\f0\b BPXSY2
\f1\b0 \'a0- Systolic: Blood pressure (second reading) mm Hg\

\f0\b BPXDI2
\f1\b0 \'a0- Diastolic: Blood pressure (second reading) mm Hg\

\f0\b BMXWT
\f1\b0 \'a0\'96 Weight (kg)\

\f0\b BMXHT
\f1\b0 \'a0\'96 Height(cm)\

\f0\b BMXBMI
\f1\b0 \'a0- Body Mass Index (kg/m**2)\

\f0\b BMXLEG
\f1\b0 \'a0- Upper Leg Length (cm)\

\f0\b BMXARML
\f1\b0 \'a0- Upper Arm Length (cm)\

\f0\b BMXARMC
\f1\b0 \'a0\'96 Arm Circumference(cm)\

\f0\b BMXWAIST
\f1\b0 \'a0\'96 Waist Circumference(cm)\

\f0\b HIQ210
\f1\b0 \'a0\'96 Time when no insurance in the past year. 1: YES, 2: NO,9: DON\'92T KNOW\
\'a0\
\pard\pardeftab720\sa120\partightenfactor0

\f0\b\fs36 \cf2 Question 1\'a0
\f1\b0 \
\pard\pardeftab720\sa240\partightenfactor0

\fs32 \cf2 Load, read and clean/preprocess (if required) the data file.\
Import required libraries. Describe the data with plots and explain your work about any patterns you find about this dataset.\
Do you find any interesting relationships between any data fields in the data? Show your work and explain all your findings about the dataset.\
\'a0\
\pard\pardeftab720\sa120\partightenfactor0

\f0\b\fs36 \cf2 Question 2\'a0
\f1\b0 \
\pard\pardeftab720\sa240\partightenfactor0

\fs32 \cf2 Get the stats about the proportion of women and men who smoke.\
Let\'92s say, our hypothesis is the proportion of women who smoke is equal to the proportion of men who smoke.\
Write the code and explain your findings and your inference.\
\'a0\
\pard\pardeftab720\sa120\partightenfactor0

\f0\b\fs36 \cf2 Question 3\'a0
\f1\b0 \
\pard\pardeftab720\sa240\partightenfactor0

\fs32 \cf2 Get the stats about the percentage of datapoints in the population that have graduated college (using the educational attainment variable DMDEDUC2).\
Analyze (if any) the relationship between Education Level (DMDEDUC2) and Ratio of family income to poverty (INDFMPIR)\
}