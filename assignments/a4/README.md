{\rtf1\ansi\ansicpg1252\cocoartf2706
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;\f1\fnil\fcharset0 HelveticaNeue-Bold;\f2\fnil\fcharset0 HelveticaNeue-Italic;
}
{\colortbl;\red255\green255\blue255;\red34\green45\blue53;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c17647\c23137\c27059;\cssrgb\c100000\c100000\c100000;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid101\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid301\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid4}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa240\partightenfactor0

\f0\fs32 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Text classification algorithms are at the heart of a variety of software systems that process text data at scale. In this assignment we will be working on building and evaluating a Supervised Text Classification Model.\
Here\'92s what to concentrate on while you deliver any of you assignments:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Explain your approach/methods, conclusions, and any/all assumptions\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Clearly document and structure your code\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Describe any ideas you attempted that didn't work\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Describe interesting ideas you didn't have time to complete; but would have tried if you were to have more time on your end.\cb1 \
\pard\pardeftab720\sa240\partightenfactor0

\f1\b \cf2 \cb3 \strokec2 Please answer all questions and submit your answers on Canvas before the deadline (Sep 27
\fs24 th
\fs32 \'a05:59p CT)
\f0\b0 \
\pard\pardeftab720\sa120\partightenfactor0

\fs36 \cf2 Submitting your work:\
\pard\pardeftab720\sa240\partightenfactor0

\fs32 \cf2 Once you are done create a compressed file called\'a0
\f2\i yourUTEID_a4.zip
\f0\i0 . Upload/Submit this file on the canvas before the due date.\
\'a0\
Question 1 (4 points)\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls2\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	1	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Read the text 
\f2\i txt
\f0\i0 \'a0 file.\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	2	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Using the text file, calculate; (1) average word length (2) average sentence length and (3) the number of times the word \'93king\'94 appears\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	3	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Calculate the TF-IDF scores of all the words in the text file (feel free to remove stop words for this). Submit the \'93term, tf-idf score\'94 as an output file.\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	4	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Display the top 100 TF-IDF terms in a Word cloud.\cb1 \
\pard\pardeftab720\sa240\partightenfactor0
\cf2 \cb3 \strokec2 Question 2 (6 points)\
Your work will be evaluated on the following aspects of your work:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls3\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Step 1: Gather/Load Data (Using sklearn.datasets is acceptable)\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Step2: Define your problem (Choose any 1 category as positive class and define a binary classification problem. For example GCAT or MCAT or ECAT as positive class)\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Step 3: Prepare Your Data (Select, Preprocess, transform to features, choose your features and explain)\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Step 4: Choose a Model for classification ( SVM, Logistic Regression or other)\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Step 5: Build, Train, and Evaluate Your Model\cb1 \
\pard\pardeftab720\sa240\partightenfactor0
\cf2 \cb3 \strokec2 Datasets - Run your model on the Datasets below. Explain your work and findings clearly.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls4\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}{\field{\*\fldinst{HYPERLINK "http://www.ai.mit.edu/projects/jmlr/papers/volume5/lewis04a/lyrl2004_rcv1v2_README.htm"}}{\fldrslt \expnd0\expndtw0\kerning0
\ul \outl0\strokewidth0 \strokec2 RCV1 Test CollectionLinks to an external site.}}\cb1 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \
\pard\pardeftab720\sa240\partightenfactor0
\cf2 \cb3 \strokec2 Note: There are two versions of the test collection. RCV1-v2 distribution is available on the web. For this assignment, just using the datasets in scikit-learn library\'92s dataset is sufficient.\
}