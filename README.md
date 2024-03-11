Business Context:


Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

![image](https://github.com/Niharika-Bathula/yes-bank-ml/assets/142409759/8784ba22-42f2-4345-817e-19868bc2fee1)


Conclusions Drawn :



Using data visualization on our target variable, we can clearly see the impact of 2018 fraud case involving Rana Kapoor as the stock prices decline dramatically during that period.

After loading the dataset, found that there are no null values in our dataset nor any duplicate data.

There are some outliers in our features however this being a very small dataset, dropping those instances will lead to loss of information.

I found that the distribution of all the variables is positively skewed. So performed power transformation on them.
There is a high correlation between the dependent and independent variables. This is a signal that the dependent variable is highly dependent on our features and can be predicted accurately from them.

Found that there is a rather high correlation between our independent variables. This multicollinearity is however unavoidable here as the dataset is very small.

Implemented several models on our dataset in order to be able to predict the closing price and found that all our models are performing remarkably well and knn regressor is the best performing model with A R2 score value of 0.993115 and scores well on all evaluation metrics.

![image](https://github.com/Niharika-Bathula/yes-bank-ml/assets/142409759/3947ad54-e874-46bf-80bd-8703b2cdd17a)

Conducted comprehensive bivariate and multivariate analyses to explore relationships between variables, gaining insights into underlying patterns and dynamics within the dataset.

Employed advanced regression methodologies including K-Nearest Neighbors (KNN), Lasso, Ridge and Elastic Net regression, leveraging their respective strengths to optimize predictive performance and mitigate overfitting.

Demonstrated exceptional predictive accuracy with the KNN regressor model, achieving an outstanding R2 score of 0.993115, indicative of its superior performance and potential practical application in real-world scenarios.


 

 

