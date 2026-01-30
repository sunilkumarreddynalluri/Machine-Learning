# Machine-Learning

<h1>Machine Learning – Regression</h1>

<h2>What is Machine Learning?</h2>
<p>
Machine Learning is a subset of Artificial Intelligence that enables systems to learn from data
and improve performance without being explicitly programmed.
</p>

<h2>What is Regression?</h2>
<p>
Regression is a <b>supervised machine learning algorithm</b> used to predict
<b>continuous numerical values</b>.
</p>

<p>
Examples:
</p>
<ul>
  <li>Predicting house prices</li>
  <li>Predicting salary based on experience</li>
  <li>Predicting temperature</li>
</ul>

<h2>Types of Regression</h2>
<ul>
  <li>Simple Linear Regression</li>
  <li>Multiple Linear Regression</li>
  <li>Polynomial Regression</li>
</ul>

<h2>Simple Linear Regression</h2>
<p>
Simple Linear Regression uses:
</p>
<ul>
  <li><b>One independent variable (X)</b></li>
  <li><b>One dependent variable (Y)</b></li>
</ul>

<p>
<b>X</b> → Independent variable (input) <br>
<b>Y</b> → Dependent variable (output)
</p>

<h3>Equation</h3>
<p>
Y = mX + c
</p>
<ul>
  <li><b>m</b> → slope</li>
  <li><b>c</b> → intercept</li>
</ul>

<h2>Dataset</h2>
<p>
A dataset contains rows and columns.
</p>
<ul>
  <li>Rows → observations</li>
  <li>Columns → features</li>
</ul>

<h2>Train-Test Split</h2>
<p>
Once the data is created, it is divided into:
</p>
<ul>
  <li><b>Training Data</b> – used to train the model</li>
  <li><b>Testing Data</b> – used to test the model</li>
</ul>

<h2>Example</h2>
<pre>
X (Experience) → [1, 2, 3, 4, 5]
Y (Salary)     → [10k, 20k, 30k, 40k, 50k]
</pre>

<h2>Advantages of Regression</h2>
<ul>
  <li>Easy to understand</li>
  <li>Works well for linear relationships</li>
  <li>Used for prediction</li>
</ul>

<h2>Applications</h2>
<ul>
  <li>Finance</li>
  <li>Healthcare</li>
  <li>Weather forecasting</li>
  <li>Business analytics</li>
</ul>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8"/>
<title>ML REGRESSION</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
<main>

<h1>Machine Learning – Regression</h1>

<h2>Concept</h2>
<p>
Regression is a supervised learning technique used to predict continuous values.
</p>

<h2>Important Terms</h2>
<ul>
<li><b>y</b> – actual values (answers from textbook)</li>
<li><b>ȳ</b> – predicted values from the model</li>
</ul>

<h2>Loss Function</h2>
<p>
Loss function measures the error between actual and predicted values.
</p>

<h2>Optimizer</h2>
<p>
Optimizers reduce loss and improve accuracy.
</p>

<h3>Gradient Descent</h3>
<ul>
<li>Cost function forms a U-shaped curve</li>
<li>Minimum point gives minimum error</li>
<li>Update coefficient and intercept iteratively</li>
</ul>

<h2>Steps in Gradient Descent</h2>
<ol>
<li>Initialize slope and intercept</li>
<li>Calculate cost function</li>
<li>Choose learning rate (step size)</li>
<li>Update slope and intercept</li>
<li>Repeat until minimum loss</li>
</ol>

<h2>Code Explanation</h2>
<pre>
# y = actual values (ans from text book)
# y_bar = predicted values by Model

# Optimizer: Gradient Descent
# Curve looks like U shape
# Minimum point = minimum error
# Update coefficient and intercept
# Cost function + step size
</pre>

</main>
</body>
</html>

