# Classification-with-Logistic-Regression
1.Choose a binary classification dataset.

2.Train/test split and standardize features.

3.Fit a Logistic Regression model.

4.Evaluate with confusion matrix, precision, recall, ROC-AUC.

5.Tune threshold and explain sigmoid function.


#  Objective: Build a binary classifier using logistic regression.
#  Tools: Scikit-learn, Pandas, Matplotlib

# Explanation
The sigmoid function maps any real-valued input (z) into a probability between 0 and 1.
Logistic regression uses sigmoid to convert linear output into a classification probability.

Formula:
𝜎
(
𝑧
)
=
1
1
+
𝑒
−
𝑧
σ(z)= 
1+e 
−z
 
1


𝜎
(
𝑧
)
σ(z) is the sigmoid output (a probability),

𝑧
z is any real number (often a linear combination of input features in logistic regression),

𝑒
e is Euler’s number (≈ 2.718).
​
