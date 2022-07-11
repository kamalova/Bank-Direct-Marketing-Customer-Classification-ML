![](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing/blob/main/images/banner.jpg)
## Customer Classification for Bank Direct Marketing
#### Author: Nurgul Kurbanali kyzy

### Table of Contents
* Overview
* Business Understanding
* Data Understanding
* Modeling
* Conclusion and Recommendations
* Future Work

###  Overview
As It is a marketing problem a lot of resources are included and it is very important to optimise results to save resources. The target variable is ‘deposit’ which reads yes or no based on success or failure of phone calls. Finding out only those clients which have higher chances of saying yes to subscription of term deposit , will save a lot of manhours and efforts. 
Predicting as many positives as possible out of actual positives from dataset is the goal here, thus recall has been chosen as one of the performance matrices along with an accuracy score. As our data are imbalanced, we used oversampling method during the model building process. After preprocessing the data, we build nine model including baseline model. The optimal model we get is Random Forest Classifier.
### Business Understanding
A term deposit is a cash investment held at a financial institution. Your money is invested for an agreed rate of interest over a fixed amount of time, or term. The bank has various outreach plans to sell term deposits to their customers such as email marketing, advertisements, telephonic marketing, and digital marketing.
The older marketing options have contributed minimal in increasing the business of banks. Due to internal competition and financial crisis European Banks were under pressure to increase their financial assets. They offered long term deposits with good interest rates to the people using direct marketing strategy but contacting many people takes lot of time and success rate is also less. So they want to take help of the technology to come up with a solution that increases the efficiency by making fewer calls but improves the success rate.
Portuguese Banking Institution has provided the data related to marketing campaigns that took over phone calls. Finding out the characteristics that are helping Bank to make customers successfully subscribe for deposits, which helps in increasing campaign efficiently and selecting high value customers.
The goal of this project is to building Machine Learning model that learns the unknown patterns and classifying whether client will subscribe(yes/no) a term deposit (variable y).
### Data Understanding
Data set is taken from [UCI Machine Learning repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing). This data based on direct marketing campaigns of a Portuguese banking institution. The marketing campaigns are based on phone calls and related to 17 campaigns, which occurred from May 2008 to November 2010. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be (or not) subscribed.
