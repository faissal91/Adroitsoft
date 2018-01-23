# Supervised learning

This algorithm consist of a target / outcome variable (or dependent variable) which is to be predicted from a given set of predictors (independent variables). Using these set of variables, we generate a function that map inputs to desired outputs. The training process continues until the model achieves a desired level of accuracy on the training data. Examples of Supervised Learning: Regression, Decision Tree, Random Forest,

### Classifications - 
Popularly known as predictive analysis | identifying which set of category a new observation belongs. Supervised learning model as the classifier already has a classified examples 

*Algorithm* - Decision Tree :

Decision tree is a graph to represent choices and their results in form of a tree. The nodes in the graph represent an event or choice and the edges of the graph represent the decision rules or conditions. It is mostly used in Machine Learning and Data Mining applications using R.

Generally, a model is created with observed data also called training data. Then a set of validation data is used to verify and improve the model. R has packages which are used to create and visualize decision trees. For new set of predictor variable, we use this model to arrive at a decision on the category (yes/No, spam/not spam) of the data.

Illustration with diabetes data -   

Import the data in R studio 
 

Do the sampling and divide the data into aspected ration (70 % and 30 %)
 

Install the package for decision tree rpart
 

Build the model with training data and based on the Outcome column you need to build the model 
 

Review the model 

 

Visualize the built model 

 
 
Identify which is the most important or significant variable for decision tree 
 

It indicates that glucose is most significant factor to evaluate who  has diabetes or not. 
Glucose >154.5 then will check age and age >=53.5 then person has a high risk of diabetes and if age <53.5 then will check the body mass index which shows that person is pretty much healthier person. 

Test the model through  testing  data and validate how good it has been fit 

 

Print the table to compare with the original outcome parameter 
 
Print confusion matrix  to  see the accuracy of the model 
 

Clearly  this model has a accuracy of 71% which is not good enough for using in production.
This data can be used for other classification algorithms like Random Forest to find if that gives better accuracy.


