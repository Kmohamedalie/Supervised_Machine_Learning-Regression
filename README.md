# Supervised Machine Learning - Regression Algorithms
<a href='https://developers.google.com/machine-learning/intro-to-ml/supervised'>Supervised learning</a>: is a type of machine learning in which machine learn
from known datasets (set of training examples), and then predict the output.
A supervised learning agent needs to find out the function that matches a given sample set.
Supervised learning further can be classified into two categories of algorithms:

1) Regression : When the outcome is pure numeric value. 
	eg : Home price prediction. You are trying to estimate value of price.

2) Classification : When the outcome is a category/class. 
	eg: Fraud detection. You are trying to identify Yes/No class

<br>
Note this is not an exhaustive list since most classification alogrithms can also perform regression task example <a href="https://scikit-learn.org/stable/auto_examples/ensemble/plot_gradient_boosting_regression.html">xgboostRegressor</a>,  <a href="https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html">RandomForestRegressor</a>, also even though the name says <a href="https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html">Logistic regression</a> it is a classification algorithm:
<br>
<br>
<table>
   <thead>
      <tr>
         <th>Algorithms</th>
         <th>Notebooks</th>
        <th>Datasets</th>
      </tr>
   </thead>
   <tbody>
      <tr>
        <td>Linear Regression </td>
        <td><a href="https://github.com/Kmohamedalie/Supervised_Machine_Learning-Regression/blob/master/Notebook/Simple_Linear_Regression_with_Statsmodels.ipynb">statsmodels </a> <a href="https://github.com/Kmohamedalie/Supervised_Machine_Learning-Regression/blob/master/Notebook/Simple_Linear_Regression_with_Sklearn_SAT_and_GPA.ipynb">sklearn</a></td>
        <td><a href="https://github.com/Kmohamedalie/Supervised_Machine_Learning-Regression/blob/master/Dataset/SAT_GPA.csv">SaT and Gpa</a> <br/> <a href="https://github.com/Kmohamedalie/Supervised_Machine_Learning-Regression/blob/master/Dataset/real_estate_price_size.csv">Real estate price</a> </td>
      </tr>
      <tr>
        <td>Multiple Linear Regression </td>
        <td><a href="https://github.com/Kmohamedalie/Supervised_Machine_Learning-Regression/blob/master/Notebook/Multiple_Linear_Regression_with_Statsmodels_SaT_and_Gpa.ipynb">Statsmodels_SaT_Gpa_Mult </a> 
		<br/> 
		<a href="https://github.com/Kmohamedalie/Supervised_Machine_Learning-Regression/blob/master/Notebook/Real_Estate_Housing_Statsmodels.ipynb">Statsmodels_Real Estate price </a> </td>
        <td><a href="https://github.com/Kmohamedalie/Supervised_Machine_Learning-Regression/blob/master/Dataset/SAT_GPA_mult.csv"> SaT and Gpa Mult</a> <br/>
		<a href="https://github.com/Kmohamedalie/Supervised_Machine_Learning-Regression/blob/master/Dataset/real_estate_price_size_year.csv">Real Estate price </a></td>
      </tr>  
      <tr>
        <td>Lasso and Ridge </td>
        <td><a href="https://github.com/Kmohamedalie/Supervised_Machine_Learning-Regression/blob/master/Notebook/Ridge_and_Lasso_Regression_Hitters_baseball.ipynb">Regularization</a></td>
        <td><a href="https://github.com/Kmohamedalie/Supervised_Machine_Learning-Regression/blob/master/Dataset/Hitters.csv">Hitters Baseball</a></td>
      </tr>  
    
   </tbody>
</table>
