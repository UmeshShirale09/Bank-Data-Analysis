# Bank-Data-Analysis

<h2> Problem Statement </h2>

The data is related to direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to assess if the product (bank term deposit) would be ('yes') or not ('no') subscribed 

<h2> Objective </h2>
1. Maximize the sales of bank deposit product to increase the revenue of bank.
<hr>


<b> Dataset : </b>	bank-full.csv

<b> Dataframe Shape :	</b> 45211 rows, 17 columns

<b> Total No. of features	: </b> 17

<b> Library Package Used	: </b> Numpy, Pandas, seaborn, Sklearn
<hr>

Attribute Information:
Input variables:
# bank client data:
1 - age (numeric) <br>
2 - job : type of job (categorical:
'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','t
echnician','unemployed','unknown') <br>
3 - marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means
divorced or widowed) <br>
4 - education (categorical:
'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown') <br>
5 - default: has credit in default? (categorical: 'no','yes','unknown') <br>
6 - housing: has housing loan? (categorical: 'no','yes','unknown') <br>
7 - loan: has personal loan? (categorical: 'no','yes','unknown') <br>
# related with the last contact of the current campaign:
8 - contact: contact communication type (categorical: 'cellular','telephone') <br>
9 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec') <br>
10 - day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri') <br>
11 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the 
output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed.
Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark
purposes and should be discarded if the intention is to have a realistic predictive model. <br>
# other attributes:
12 - campaign: number of contacts performed during this campaign and for this client (numeric, includes
last contact) <br>
13 - pdays: number of days that passed by after the client was last contacted from a previous campaign
(numeric; 999 means client was not previously contacted) <br>
14 - previous: number of contacts performed before this campaign and for this client (numeric)  <br>
15 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success') <br>
# social and economic context attributes
16 - Has the client subscribed to a term deposit? (binary: 'yes','no') – Target Variable <br>
