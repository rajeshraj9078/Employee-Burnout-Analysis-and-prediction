# Employee-Burnout-Analysis-and-prediction
AICT IBM AI Internship project.

Employee burnout is a state of exhaustion caused by prolonged stress, negatively affecting well-being, productivity, and job performance. Recognizing and addressing burnout is crucial in today's fast-paced, connected world to ensure employee health and effectiveness.

This project explores regression techniques to predict employee burnout using factors like workload, mental fatigue, and work-life balance. The goal is to develop a model to identify individuals at risk, enabling organizations to address these factors proactively and promote employee well-being.

# Key Features:

$Dataset Analysis:$ Treats missing values, encodes categorical data, and explores correlations.

$Modeling Techniques:$ Implements regression models and evaluates performance using the R² metric.

$Business Impact:$ Provides actionable insights to prevent burnout and improve organizational health.


# Exploratory Data Analysis

Exploratory data analysis (EDA) is an important step in the machine learning process, as it allows us to gain insights into the characteristics and patterns of our data.
![1](https://github.com/user-attachments/assets/703fbf3a-bb51-44e7-a102-bce70b27a1a0)![2](https://github.com/user-attachments/assets/f47bc2b0-5ebe-48d3-9702-d8a47a58d54c)
Variables are strongly correlated with our target and, therefore, important to estimate it. This correlation can also be seen plotting the relationship within the variables.
![3](https://github.com/user-attachments/assets/eb61f92c-600e-469e-ab68-269767ca6518)
'Date_of_Joining' which contains dates on year 2008.
Prior to any analysis, the date of joining doesn't seem that could have a direct relationship with target.

![4](https://github.com/user-attachments/assets/cb66a8f5-45c9-4c11-acd2-dd4bc037e715)![5](https://github.com/user-attachments/assets/a253d1c2-946e-4526-86f0-5d5c030c86d2)

# Future
As the number of most important features is reduced, as we saw with the zero-valued coefficients of the lasso model, we could perform PCA over the polynomial features, eliminating half of them and preserving likely almost 99% of the variance. This will make our predictions faster although it doesn't seem to be a problem in this case.

Other things to prove is trying other linear models and more complex ones, although the relationship within the input features and target is very linear. For this, we could try:

Multivariate Adaptive Regression Splines
Deep Neural Network
KNN Regressor
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor

The most important variables that influences the burnout syndrome of an employee are mainly the mental fatigue and the amount of resource allocated (i.e. hours of work). Also, the main thing that seems to have a positive impact on reducing this effect is to have the opportunity of working from home.

# Conclusion

The project successfully developed a regression model to predict employee burnout using features like mental fatigue score, work-from-home status, and workload. Key steps included handling missing values, encoding categorical data, studying feature correlations, and applying advanced techniques such as grid search cross-validation and polynomial features. The model's performance was evaluated using the R² metric, demonstrating its potential to help organizations proactively address employee burnout and promote well-being.





