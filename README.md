# Next_Product_To_Buy
Sample study: This study file demonstrates Next-Product-To-Buy modeling using a test performed on 30,000 customers.
**This study is then used on a different circumstance and larger dataset to identify the best product.**

Sample Study Details:
Offers to buy a book were sent out in one category to 10,000 randomly selected customers. Another 10,000 in second and another 10,000 got an offer in third category. The dataset contains information on responses from these 30,000 customers. The task is to use the available data to find the best book to offer each of the 30,000 customers in the test, as well as the best book to offer an additional 10,000 customers that were not part of the test. 

The study uses logistic regression with buyer as the response variable and customer characteristics and book categories as the explanatory variables. The model is modified using interactions. We want to predict what each customer would have done if we had sent him/her any one of the three offers (from 3 book categories: Art, DIY, Cook). 

***Actual Study Details:***

Dataset used to investigate opportunities to decrease customer churn at S-mobile. The sample consists of three parts:

A training sample with 27,300 observations and a 50% churn rate ("training == 1")
A test sample with 11,700 observations and a 50% churn rate ("training == 0")
A representative sample with 30,000 observations and a churn rate of 2%, i.e., the actual monthly churn rate for S-mobile ("is.na(training)" or "representative == 1")

Variables
customer: Customer ID
churn: Did consumer churn in the last 30 days? (yes or no)
changer: % change in revenue over the most recent 4 month period
changem: % change in minutes of use over the most recent 4 month period
revenue: Mean monthly revenue in SGD
mou: Mean monthly minutes of use
overage: Mean monthly overage minutes
roam: Mean number of roaming calls
conference: Mean number of conference calls
months: # of months the customer has had service with S-Mobile
uniqsubs: Number of individuals listed on the customer account
custcare: Mean number of calls to customer care
retcalls: Number of calls by the customer to the retention team
dropvce: Mean number of dropped voice calls
eqpdays: Number of days customer has owned current handset
refurb: Handset is refurbished (no or yes)
smartphone: Handset is a smartphone (no or yes)
creditr: High credit rating as opposed to medium or low (no or yes)
mcycle: Subscriber owns a motorcycle (no or yes)
car: Subscriber owns a car (no or yes)
travel: Subscriber has traveled internationally (no or yes)
region: Regions delineated by the 5 Community Development Council Districts (e.g., CS is Central Singapore)
occupation: Categorical variable with 4 occupation levels (professional, student, retired, or other)
training: 1 for training sample, 0 for test sample, NA for representative sample
representative: 1 for representative sample, 0 for training and test sample



