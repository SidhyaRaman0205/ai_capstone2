# Predicting Customer Churn for Telecommunication Companies

## Overview
#### The business problem I have been examining is addressing customer churn in telecommunication companies. I have used a data set from Kaggle that has information regarding this subject. The models I have used to help solve this problem are Decision Tree and Random Forest classifiers. These models output a percentage that will determine the accuracy of the model in predicting customer churn. The models were able to return an accuracy rate of 92 and 95% respectively. 

![Header image](https://www.cleartouch.in/wp-content/uploads/2022/11/Customer-Churn.png)

## Business Understanding
#### Customer churn is defined as the loss of customers, which is a serious issue for telecommunication companies because it is very costly to acquire new customers versus maintain customer retention. Thus, it would be more profitable for companies to avoid customer churn all together. Source used: https://www.zendesk.com/blog/customer-churn-rate/#:~:text=Churn%20rates%20are%20important%20because,is%20to%20keep%20existing%20ones.

## Modeling and Evaluation
#### The main models I used were decision tree and random forest classifiers which provided an accuracy percentage in determining how accurate they are in predicting customer churn. The random forest model performed very well with an accuracy percentage of 95%, followed by the decision tree model with 92%. 

## Conclusion 
#### Given that the Random Forest model was slightly more accurate in predicting customer churn, I would say that users could implement this model in their analysis. They could also use the seaborn python visualization library and the feature importance function to determine which features in their respective data set have the biggest impact on customer churn

## Repository Navigation:
#### An explanation of the repository organization: An explanation of the repository organization: The repository includes the data files (test.csv and train.csv) in the ProjectData folder, the. gitignore, capstone proposal, README.md, my project jupyter notebook, and the PDF to my project presentation. 
#### Links to the final notebook and presentation: Final notebook link: https://github.com/SidhyaRaman0205/ai_capstone2/blob/master/index.ipynb; Final Presentation PDF link: https://github.com/SidhyaRaman0205/ai_capstone2/blob/master/Capstone%20Presentation.pdf
#### Reproduction instructions (or a link to them): The data for this project can be found in the 'ProjectData' folder. The files in there are test and train.csv files. The libraries that were imported are numpy, pandas, matplotlib.pyplot, seaborn, sklearn.model_selection, sklearn.preprocessing, sklearn.metrics, and sklearn.tree. Given that decision trees and random forest models are built randomly, making sure that a random state is included for the test train split and building of the decision tree and random forest models is also important because it increases model performance. 
