{\rtf1\ansi\ansicpg1252\cocoartf2706
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;\f1\fnil\fcharset0 HelveticaNeue-Bold;\f2\fnil\fcharset0 HelveticaNeue-Italic;
}
{\colortbl;\red255\green255\blue255;\red34\green45\blue53;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c17647\c23137\c27059;\cssrgb\c100000\c100000\c100000;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa240\partightenfactor0

\f0\fs32 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 This assignment is about\'a0
\f1\b Feature Engineering with Logistic Regression
\f0\b0 . To begin, you'll need to create code that loads in the data(the file data.csv is found in the one-drive assignments folder under a3 directory) and builds a Logistic regression model to classify the breast cancer tumor type ; Malignant(M) as +ve class and Benign as -ve class and output the predictions in a CSV format.\
To get a full grade on this assignment, you'll need to:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Explore different features for your regression model. And compare the model performance using different features.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Create plots to show model performance and perform error analysis to understand how your model is performing.\cb1 \
\pard\pardeftab720\sa240\partightenfactor0
\cf2 \cb3 \strokec2 The process you explore will be reflected in your write-up, but your code must reproduce your output for us to recreate your results.\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b \cf2 About the data\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0
\f0\b0 \
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. Details can be found on UCI Machine Learning Repository:\'a0{\field{\*\fldinst{HYPERLINK "https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29"}}{\fldrslt \cf2 \cb3 \ul \ulc2 \strokec2 https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29\cb1 \ulnone \
\pard\pardeftab720\partightenfactor0
\cf2 \cb3 \ul \ulc2 Links to an external site.\cb1 \ulnone \
}}\pard\pardeftab720\sa240\partightenfactor0

\f1\b \cf2 Please submit your answers on Canvas before the deadline (Sep 20
\fs24 th
\fs32 \'a05:59p CT)
\f0\b0 \
\pard\pardeftab720\sa120\partightenfactor0

\fs36 \cf2 Submitting your work:\
\pard\pardeftab720\sa240\partightenfactor0

\fs32 \cf2 Once you are done create a compressed file called\'a0
\f2\i yourUTEID_a3.zip
\f0\i0 . Upload/Submit this file on the canvas before the due date.\
Upload your materials and all your code and data.\
Your upload must include be as following:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls2\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Code: Python (.py) files or IPython notebook\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Output: CSV (.csv)\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Write-up: PDF (.pdf)\cb1 \
\pard\pardeftab720\sa240\partightenfactor0
\cf2 \cb3 \strokec2 Your PDF write-up should have:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls3\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 A discussion of what you tried\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Plots to show your error analysis\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 A discussion of what directions worked (and which didn't) You are limited to 500 words (but unlimited figures)\cb1 \
}