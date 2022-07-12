![](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing/blob/main/images/banner.jpg)
# Customer Classification for Bank Direct Marketing
#### Author: Nurgul Kurbanali kyzy
### Table of Contents
* [Overview](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing#overview)
* [Business Understanding](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing#business-understanding)
* [Data Understanding](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing#data-understanding)
* [Conclusion and Recommendations](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing#conclusion)
* [Future Considerations](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing#future-consideration)
##  Overview
As It is a marketing problem a lot of resources are included and it is very important to optimise results to save resources. The target variable is ‘deposit’ which reads yes or no based on success or failure of phone calls. Finding out only those clients which have higher chances of saying yes to subscription of term deposit , will save a lot of manhours and efforts. 
Predicting as many positives as possible out of actual positives from dataset is the goal here, thus recall has been chosen as one of the performance matrices along with an accuracy score. As our data are imbalanced, we used oversampling method during the model building process. After preprocessing the data, we build nine model including baseline model. The optimal model we get is Random Forest Classifier.
## Business Understanding
A term deposit is a cash investment held at a financial institution. Your money is invested for an agreed rate of interest over a fixed amount of time, or term. The bank has various outreach plans to sell term deposits to their customers such as email marketing, advertisements, telephonic marketing, and digital marketing.
The older marketing options have contributed minimal in increasing the business of banks. Due to internal competition and financial crisis European Banks were under pressure to increase their financial assets. They offered long term deposits with good interest rates to the people using direct marketing strategy but contacting many people takes lot of time and success rate is also less. So they want to take help of the technology to come up with a solution that increases the efficiency by making fewer calls but improves the success rate.
Portuguese Banking Institution has provided the data related to marketing campaigns that took over phone calls. Finding out the characteristics that are helping Bank to make customers successfully subscribe for deposits, which helps in increasing campaign efficiently and selecting high value customers.
The goal of this project is to building Machine Learning model that learns the unknown patterns and predicts whether client will subscribe(yes/no) a term deposit (variable y).
## Data Understanding
Data set is taken from [UCI Machine Learning repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing). This data based on direct marketing campaigns of a Portuguese banking institution. The marketing campaigns are based on phone calls and related to 17 campaigns, which occurred from May 2008 to November 2010. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be (or not) subscribed.
## Conclusion 
Among all models that I build, Logistic Regression and Random Forest algorithms performed well. An oversampling technique such as SMOTENC did not much help on models' performance. As a final and best model I chose Random Forest with the recall score 84% and an accuracy score 84%. Mainly model does a good job of decreasing false-positive which leads to avoiding losing future customers but identifying them as SUBSCRIBED.<p>
![](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing/blob/main/images/conf_matrix.png)<p>
![](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing/blob/main/images/class_report.png)<p>
## Recommendations
![](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing/blob/main/images/feat_importance.png)
1. Develop a marketing strategies during the Calls: Since duration of the call is the feature that most positively correlates with whether a potential client will subscribe to a term deposit or not, by providing an interesting questionaire for potential clients during the calls the conversation length might increase. Of course, this does not assure us that the potential client will suscribe to a term deposit! Nevertheless, we don't loose anything by implementing a strategy that will increase the level of engagement of the potential client leading to an increase probability of suscribing to a term deposit.
2. The successful outcome of the previous marketing campaign did positively affect customers to subscribe to upcoming campaigns.I would highly recommend developing a loyalty program for the previously subscribed clients by giving them some bonuses and unique offers.
3. House Loans and Balances: Potential clients in the average and high balances are less likely to have a house loan and therefore, more likely to open a term deposit. Lastly, the next marketing campaign should focus on individuals of average and high balances in order to increase the likelihood of suscribing to a term deposit
## Future Consideration
This modelling is based on behaviour of clients and not on their motivations. The features reveal the actions of client but not his/her thought process. So more descriptive features can be useful here for example interview summary. In that case natural language processing will give better results. In these times of crisis preserving the relationship with best customers is more crucial than ever. Using these results bank can specifically target clients and gain higher success in their endeavours. Saving a lot of time by not focusing on clients with less probability is yet another advantages of this project
  
### For More Information
You can review my full analysis in my [Jupyter Notebook](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing/blob/main/notebook.ipynb) or my [presentation](https://github.com/kamalova/Customer-Classification-for-Bank-Direct-Marketing/blob/main/presentation.pdf). <p>
For any additional questions, please contact Nurgul Kurbanali kyzy at nurkamalova@gmail.com

#### Repository Structure

