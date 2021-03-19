# France_Emissions
France CO2 code file- here we look into the matter further and try to analyze which production(coal ,oil, cement ,gas, flaring gas) creates 
the most CO2 emissions and 
thus can be targeted to reduce France's share of carbon footprint.
Pie-chart describing top 3 contributors of CO2 in Production sector are shown and only these columns
are considered for predicting values further.
We predict future values of : 1. Production CO2 and 2.France's global share CO2 to see 
how it will increase/decrease in future.
We use Random Forest Regression and  XGBoost models as it outperformed K-NN,Linear Regression and SVR . 
Also we use k-fold cross validation technique for model evaluation so that we know the evaluation metrics
we get are dependable not just a fluke.
