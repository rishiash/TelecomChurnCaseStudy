# Telecom Churn Case Study 
> By Rishi Shah


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Goal is to predict if the customer will churn or not in a particular month based on the past data
- The data for June, July and August have been separately analyzed.
- Detailed EDA was conducted on the data.
- Principal Component Analysis (PCA) was used to reduce the dimensions of the data.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Looks like the network has not acquired any new customers or they have not shared the data of new customers. The network operator should focus on acquiring new customers
- We analyzed the data month wise instead of analyzing all data together since we are now comparing apples to applies while analyzing the data separately that was not the case
- The data is highly imbalanced. The model has been structured so that the sensitivity is high. So there maybe more false positives but it is better to have false positives compared to false negatives
- The month of June is not helping much in terms of determining who will churn but July and Aug have key indicators. To derive the final result I have done a binary and of the churn prediction of July and Aug
- On analysing the features, it looks like the local calls are the most important features for both July and August. Focussing on providing some discount or offers on local calls or additional minutes for local calls for same price will prevent churn
- Offering discount or offers on roaming calls will also help reduce the churn. The model predicts roaming calls as an important factor
- Recharge amounts seems to be an important variable. Lower amounts of recharge indicate possibility of churn 
- Lower average revenue also indicate possibility of churn

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Acknowledgements
- The project was worked by Rishi


## Contact
Created by [@rishiash] - feel free to contact me!

