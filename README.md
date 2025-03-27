Wine is a beverage made from fermented grapes and other fruit juices with a low amount of alcohol content. Wine is the second most popular alcoholic drink in the world after beer, and it is one of the most highly consumed beverages.

Generally, the quality of wine is graded based on the taste of the wine and vintage but this process is time-consuming, costly, and not efficient as the quality of the wine also depends on other physiochemical attributes like fixed acidity, volatile acidity, etc. Also, it is not always possible to ensure wine quality by experts when there is a huge demand for the product as it will increase the cost significantly.

Objective:
Moonshine is a red wine company that produces premium high-quality wines. The company wants to improve its production efficiency and reduce the cost and additional time involved in wine tasting. Moonshine company have to build a predictive model that can help to identify the premium quality wines using the available data.

The model can make wrong predictions as:

Predicting a wine is of premium quality when it is of non-premium quality.
Predicting a wine is of non-premium quality when it is of premium quality.
**Which case is more important? **

If the model predicts a wine is of non-premium quality but it is of premium quality then the company would incur the loss of good wine and resources used.
If the model predicts a wine is of premium quality but it is not then the company would roll out low-quality wine which would affect their customer base and their reputation.
f1 score = 2precisionrecall / (precision +recall)

Which metric to optimize?

We would want F1-Score to be maximized, the greater the F1-Score higher the chances of predicting both the classes correctly.
