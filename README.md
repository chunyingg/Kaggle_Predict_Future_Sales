# Kaggle_Predict_Future_Sales
competition : https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview
## Description
This challenge serves as final project for the "How to win a data science competition" Coursera course.

In this competition you will work with a challenging time-series dataset consisting of daily sales data, kindly provided by one of the largest Russian software firms - 1C Company. 

We are asking you to predict total sales for every product and store in the next month. By solving this competition you will be able to apply and enhance your data science skills.


## Data Preprocessing
https://nbviewer.jupyter.org/gist/chunyingg/bfa56153f35a4702c34a58c9bafddf26
## Model Selection
  1. LightGBM : https://nbviewer.jupyter.org/gist/chunyingg/e41bf0ad4c2cd2ded687da722890eb3b
  2. XGboost : https://nbviewer.jupyter.org/gist/chunyingg/39768692b3779b262c95bcad54d425a1
  3. Neural Network : https://nbviewer.jupyter.org/gist/chunyingg/afb55dcece49c14c6bcc73aa47a17fc1
## Ensemble
https://gist.github.com/chunyingg/cd2db7e653da8c0ac0b420b3803f900e
## Vote
I uesd all the data of predictions to generate a new outcome. The method is giving weights according to their performance.
## Conclusion
The best performance of single models is lightgbm, and the Neural Network is the worst and the most time consuming.
However, the outcome of esemble and vote is better than all the single model.
## Reference
Learning from this kernal
https://www.kaggle.com/dhimananubhav/feature-engineering-xgboost
