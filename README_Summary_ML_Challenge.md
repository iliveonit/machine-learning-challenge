# SUMMARY - Machine Learning Homework
# Machine Learning Homework - Exoplanet Exploration

### July/19/2020: Gretel HW Tips
1. Choose 1 single Jupyter Notebook for all Models
2. Instead of MinMaxScalar you can use "Standard Scalar"

### Possible Models to try for this Challenge

* LinearRegression
* Lasso, Ridge, and ElasticNet
* Decision Tree
* Random Forest

### Summary Reporting

### Create a README that reports a comparison of each model's performance as well as a summary about your findings and any assumptions you can make based on your model (is your model good enough to predict new exoplanets? Why or why not? What would make your model be better at predicting new exoplanets?).

In the Jupyter Notebook, I have tried the challenge outcome prediction and accuracy using the LinearRegression and Lasso, Ridge, and ElasticNet models.

The thumbrule while comparing MSE and R2 scores is:

There is no correct value for MSE. 
Simply put, the lower the value the better and 0 means the model is perfect. 
Since there is no correct answer, the MSE’s basic value is in selecting one prediction model over another.

Similarly, there is also no correct answer as to what R2 should be. 100% means perfect correlation. 
Yet, there are models with a low R2 that are still good models.

In this Homework challenge, below is the comparision output for selected Models: 

Linear Regression MSE   : 0.9434798994822639, R2: 0.0263946174118056
Lasso MSE               : 0.9456506730038898, R2: 0.024154530700689958
Ridge MSE               : 0.9434799015304657, R2: 0.026394615298204305
ElasticNet MSE          : 0.9442725687599838, R2: 0.025576638061292845

Based on above comparision, I understand:
- Based on MSE value - Linear Regression model is the best
- Based on R2  value - Lasso Model is the best.
