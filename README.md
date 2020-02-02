## Classifying bad loans with Lending Club loan data

Click [here](https://nbviewer.jupyter.org/github/lethnam/predicting_bad_loans_with_LendingClub_data/blob/master/lending_club.ipynb) to see the codes + interactive plots

The data are obtained from [Kaggle](https://www.kaggle.com/wendykan/lending-club-loan-data). The data can also be downloaded from the [Lending Club website](https://www.lendingclub.com/info/statistics.action). My objective is to classify whether a loan will become bad (i.e. late payments, charged off or defaulted) based on a borrower's personal characteristics. In this notebook,

1. I first check and transform the data to gather all the necessary predictors. There are nearly 150 indicators in the data set. Based on the descriptions, I select about 20 variables that I think can help to distinguish the bad loans from the good ones. These variables reflect, for example, the annual incomes, overall debts, purposes of borrowing, places of residence, etc.
2. Then, I do extensive exploratory data analyses that involve data visualization with matplotlib, seaborn and plotly
3. For the classification of bad loans: I compare the performances of the models: Support Vector Machine, Logistic Regression, Decision Tree, Random Forest, AdaBoost with Decision Tree, Adaboost with Random Forest, and Extreme Gradient Boosting library XGBoost. Most models perform well, with high accuracy scores.