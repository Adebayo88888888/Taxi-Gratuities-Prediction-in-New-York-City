# Predicting-Taxi-Gratuities-in-New-York-City


### Business Understanding:

The project aims to predict whether a rider will leave a generous tip during New York City yellow taxi trips in 2017. The goal is to help taxi drivers achieve a livable wage by understanding the factors that encourage riders to leave tips.

### Data Understanding:

The NYC Taxi and Limousine Commission data came from NYC.gov. The data consisted of approximately 408k unique trips and 18 features. The features included information on trip duration and destination, vendor used, toll information, and payment type. The bar chart below shows the breakdown of how many generous tippers (>20%) versus non-generous tippers that exist in the data set. 


### Modeling and Evaluation:

A random forest model comprising 100 decision trees was used to determine feature importance in who would tip generously or not. The below plot shows that trip duration, distance, and the cost of a fare were the Top 3 most important factors in determining a generous tipper from a non-generous one. The overall model performed with 86% accuracy and 72% precision. 

 
## Conclusion:

This model can benefit Taxi Drivers in knowing if they will be tipped generously or not; however, running a parametric model to determine how much each variable will influence the actual price of the tip. In the future, adding more information on a rider’s past tipping behavior may also be beneficial in helping the stakeholder address the business problem
