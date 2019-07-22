# Question 1

**List as many use cases for the dataset as possible.**
- Churn prediction;
- Sales prediction (based on seasonality);
- Product recomendation (based on other users).


# Question 2

**Pick one of the use cases you listed in question 1 and describe how building a statistical model based on the dataset could best be used to improve the business this data comes from.**

Based on sales prediction, it is possible to improve stock management, based on seasonalities, reducing or increasing the stock for specific months over the year.


# Question 3

**Implement the model you described in question 2, preferably in Python. The code has to retrieve the data, train and test a statistical model and report relevant performance criteria. Ideally, we should be able to replicate your analysis from your submitted source-code, so please explicit the versions of the tools and packages you are using.**

For packages used see [requirements.txt](requirements.txt).
For model development and explanation see [jupyter notebook](https://github.com/melloGuilherme/data_challenge/blob/master/Sales Prediction.ipynb)


# Question 4

**1. Explain each and every of your design choices, you can use jupyter notebooks. (e.g., preprocessing, model selection, hyper parameters, evaluation criteria). Compare and contrast your choices with alternative methodologies.**

For model development and explanation see [jupyter notebook](https://github.com/melloGuilherme/data_challenge/blob/master/Sales Prediction.ipynb)

**2. Describe how you would improve the model in Question 3 if you had more time.**

It is possible to improve the model using fewer points ahead. In this case we would use all the point available before a new prediction, training a new model for each prediction. In this case, it will possibly better capture the trend component over the former training points.