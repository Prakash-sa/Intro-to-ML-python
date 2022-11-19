{\rtf1\ansi\ansicpg1252\cocoartf2706
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;\f1\fnil\fcharset0 HelveticaNeue-Bold;\f2\fnil\fcharset0 HelveticaNeue-Italic;
\f3\fnil\fcharset0 HelveticaNeue-BoldItalic;}
{\colortbl;\red255\green255\blue255;\red34\green45\blue53;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c17647\c23137\c27059;\cssrgb\c100000\c100000\c100000;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid101\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid201\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid3}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa120\partightenfactor0

\f0\fs43\fsmilli21600 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Assignment 2\
\pard\pardeftab720\sa240\partightenfactor0

\fs32 \cf2 This coding challenge is designed to test your skill and intuition about exploratory Data Analysis, building a regression model and its evaluation for structured datasets. For the challenge we will use two datasets.\
Please deliver your answers as if you were handing off work to another data scientist joining your team.\'a0\
Here\'92s what we\'92re looking for:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Explanations of your intent, methods, conclusions, and any assumptions\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Clear, documented, and well-structured code\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Methods you attempted that didn't work\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Ideas you didn't have time to complete but would have done with more time\cb1 \
\pard\pardeftab720\sa240\partightenfactor0

\f1\b \cf2 \cb3 \strokec2 Please answer completely all questions and submit your answers before the deadline.
\f0\b0 \
\pard\pardeftab720\sa120\partightenfactor0

\fs36 \cf2 Submitting your work:\
\pard\pardeftab720\sa240\partightenfactor0

\fs32 \cf2 Once you are done create a compressed file called\'a0
\f2\i yourUTEID_a2.zip
\f0\i0 . Upload/Submit this file on the canvas before the due date.\
\pard\pardeftab720\sa120\partightenfactor0

\fs36 \cf2 Question 1 (4 points)\
\pard\pardeftab720\sa240\partightenfactor0

\fs32 \cf2 For Question 1 we use the data collected from a mock company which consists of an asynchronous stream of event-based client messages. Each message has a timestamp, a type code corresponding to the triggering event, and some metadata about that event.\
Data Schema\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b \cf2 When
\f0\b0  : Event time-stamp\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 site_id
\f0\b0  : The site id for a given organization\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 ap_id
\f0\b0  : The access point id for a given site\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 client_id
\f0\b0  : The client id for a given site\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 wlan_id
\f0\b0  : The wireless local area network id for a given site\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 event_code
\f0\b0  : The event code\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 reason_code1,2,3
\f0\b0  : DIfferent reason codes for each event (generally the reason code doesn\'92t exist or is zero if the event is successful)\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 rssi
\f0\b0  : Received Signal Strength Indicator\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 rssi_of_request
\f0\b0  : Received Signal Strength Indicator of the request signal\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 fw_id
\f0\b0  : The Firmware id of the access point\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 channel
\f0\b0  : The channel which was used during the event\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 latency1.2
\f0\b0  : Event latency in the term in millisecond\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 Lease_time, rebind_time, renewal_time
\f0\b0  : Different time duration associated to the event in millisecond\cf2 \cb1 \strokec2 \uc0\u8232 
\f1\b \cf2 \cb3 \strokec2 time_since_req
\f0\b0  : elapsed time since first request response in millisecond\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls2\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	1	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Load, read and clean 
\f3\i\b \ul A2_question1_data.csv 
\f0\i0\b0 \ulnone \'a0 file.\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	2	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Plot the time series of the hourly number of events for a random access point. [2 points]\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	3	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 We would like to get a rough sense of event transitions e.g. transitions from event 4 to event 7, or event 15 to event 23. Provide state transition distribution for client events? [2 points]\cb1 \
\pard\pardeftab720\sa120\partightenfactor0

\fs36 \cf2 \cb3 \strokec2 Question 2 (6 points)\
\pard\pardeftab720\sa240\partightenfactor0

\fs32 \cf2 Task: Build a Linear Regression Model to predict Housing Prices using\'a0
\f1\b Scikit-learn
\f0\b0 .\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls3\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	1	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Read the Dataset - 
\f3\i\b \ul A2_question2_data.csv
\f0\i0\b0 \cb1 \ulnone \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	2	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 In your work/notebook please show the basic statistics on the dataset. Are any data points missing? Explain any preprocessing steps and exploratory data analysis that was performed before you start building the model.\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	3	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Split the data into train/validation/test sets (Typically 70%,10%,20%).\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	4	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Build and evaluate the model. Feel free to add/drop features to tune your model performance.\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	5	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Please explain your work and findings.\cb1 \
}