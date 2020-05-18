# Machine-Learning
Linear Regression:
<hr>
<h1> Introduction to Linear Regression</h1>
In simple regression, we predict scores on one variable from the scores on a second variable.
The variable we are predicting is called Criterion, and is referred to as Y.<br>
The variable we are basing our prediction on is called the predictor variable and is referred to as X.<br><br>
When there is only one predictor variable the prediction method is called simple regression.
In simple linear regression, the topic of this section, the predictions of Y when plotted as a function of X from a straight line.<br>

As we know formula  of a line as : <Strong >Y = mx + c</strong><br>
<h3>Steps to procced</h3>
  1) find the mean of X and Y<br>
  2) find the slope(m) using the formula: <strong> m=summation of (x-X')*(y-Y')/summation of(x-x')**2</Strong><br>
  3) Now find the intersept(C) by putting the mean_X and mean_y in the line equation.<br>
  
  <h3>What is R-square?</h3>
  R-squared value is a statistical measure of how close the data are to be fitted regression line.
  It is also known as co-efficient of determination or the coefficient of multiple determination.<br>
  Higher the R-squared value, more efficient is the line of regression.<br>
  <Strong>Formula: R**2 = (summation(Yp - Y')**2)\(summation(Y - Y')**2)</strong>
  
<hr>
<br>
Decision Tree Regression<br>
<hr>
<h1>Classification</h1>
It is the process of dividing the datasets into different categories or groups by adding label.<br>
Note: It adds the data point to a particular labelled group on the basis of some condition.<br>


<h4>Types of Classification</h4>
<h5>1) Decision Tree<br>
    2) Random Forest<br>
    3) Naive Bayes<br>
    4) KNN</h5>
 
<h2>Decision Tree</h2>
It is a graphical representation of all the possible solution to a decision based on certain conditions.
In order to built a decision tree which use Decision tree algorithm, we use CART (Classification & Regression Tree).

<h5>How does Tree decide where to split </h5>
<strong>1) Gini:</strong>
The measure of impurity used in buk=ilding decision tree in CART is Gini index.
<strong>2) Information Gain</strong>
The information gain is the decrease in entropy after a dataset is split on the basis of an attribute. constructing a decision tree is all about finding attributes that returns the highest information gain. 
