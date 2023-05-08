# LogisticRegressionTradingStrategy
Application of Logistic Regression for a trading strategy

This code provides an example of how one can apply machine learning techniques to generate trading signal. Presented technique would involve applying logistic regression model to predict wether the market movements would be UP or DOWN.

To determine if the market would go up or down, the model will use laggged returns as a feature to predict market movements. 

Logistic Regression returns as an output binary dependent variable. Basic algorithm would work as follow:
- If predicted value is 1, it is a **LONG** signal (model predicts that market will move up) - in other word buy signal,
- If predicted value is -1, it is a **SHORT** signal (model predicts that market will go down) - in other words sell signal.

Tested instrument would be **S&P 500 E-mini** futures contract (ticker: ES=F).
