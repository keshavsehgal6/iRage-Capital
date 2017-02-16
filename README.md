# iRage-Capital

The project consists of two i-python Notebooks: EDA and Tree_based

# EDA
EDA consists of Initial Exploratory Data Analysis. The analysis done on correlations, distributions of variables and time based distributions help us recognise initial set of important variables.

# Tree_based
For the Modelling part I have analysed only the tree based models, namely:

1. Random Forest Regressor:
  Used for predicting the returns. The model doesnot performs very good in these conditions. may be tried during further analysis.
2. Random Forest Classifier:
  Used for Classification of movement of Futures Prices. The model performs well but seems to be overfirrting, which needs to be controlled during further tweaking of parameters.
3. XGBoost:
  Used for Classification of movement of Futures Prices. The model is tried with very little variations. The model seems promising to approach this problem. Rigrous tunning and backtesting to be done as we move further with this model.
  
  In adition to this Models that can be tried for this problem is an LSTM. The code for that is in LSTM.ipynb, which is under progress. The run of this model is very slow for laptops and would need bigger syatem of the present dataset. Varitions in form of slicing the dataset and using just a small piece can be tried further for initial results.
