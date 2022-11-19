This coding challenge is designed to test your skill and intuition about exploratory Data Analysis, building a regression model and its evaluation for structured datasets. For the challenge we will use two datasets.

Please deliver your answers as if you were handing off work to another data scientist joining your team. 

Here’s what we’re looking for:

Explanations of your intent, methods, conclusions, and any assumptions
Clear, documented, and well-structured code
Methods you attempted that didn't work
Ideas you didn't have time to complete but would have done with more time
Please answer completely all questions and submit your answers before the deadline.

## Submitting your work:
Once you are done create a compressed file called yourUTEID_a2.zip. Upload/Submit this file on the canvas before the due date.

### Question 1 (4 points)
For Question 1 we use the data collected from a mock company which consists of an asynchronous stream of event-based client messages. Each message has a timestamp, a type code corresponding to the triggering event, and some metadata about that event.

### Data Schema

When​: Event time-stamp
site_id​: The site id for a given organization
ap_id​: The access point id for a given site
client_id​: The client id for a given site
wlan_id​: The wireless local area network id for a given site
event_code​: The event code
reason_code1,2,3​: DIfferent reason codes for each event (generally the reason code doesn’t exist or is zero if the event is successful)
rssi​: Received Signal Strength Indicator
rssi_of_request​: Received Signal Strength Indicator of the request signal
fw_id​: The Firmware id of the access point
channel​: The channel which was used during the event
latency1.2​: Event latency in the term in millisecond
Lease_time, rebind_time, renewal_time​: Different time duration associated to the event in millisecond
time_since_req​: elapsed time since first request response in millisecond

Load, read and clean ​A2_question1_data.csv​ ​file.
Plot the time series of the hourly number of events for a random access point. [2 points]
We would like to get a rough sense of event transitions e.g. transitions from event 4 to event 7, or event 15 to event 23. Provide state transition distribution for client events? [2 points]

### Question 2 (6 points)
Task: Build a Linear Regression Model to predict Housing Prices using Scikit-learn.

Read the Dataset - ​A2_question2_data.csv
In your work/notebook please show the basic statistics on the dataset. Are any data points missing? Explain any preprocessing steps and exploratory data analysis that was performed before you start building the model.
Split the data into train/validation/test sets (Typically 70%,10%,20%).
Build and evaluate the model. Feel free to add/drop features to tune your model performance.
Please explain your work and findings.
