#### Ranveer Singh
### General Subjective Questions

##### 1. Explain the linear regression algorithm in detail. (4 marks)
Answer : A linear regression is, where number of the independent variable is 1 and there is a linear relationship between the independent variable and dependent variable. (respectively x and y)
y  = a + bx
y : Dependent varilable
x : Independent Varilable
a : y intercept of the line
b : slop of line


##### 2. Explain the Anscombe’s quartet in detail. (3 marks)
Answer : Anscombe's Quartet study shows us that graphing data prior to analysis is good practice.It showed four datasets that have nearly identical simple statistical properties, yet appear very different when graphed.

##### 3. What is Pearson’s R? (3 marks)
Answer : The Pearson Corelation Coficient also calles Pearson r, measure of linear correlation between two sets of data.It is the ratio between the covariance of two variables and the product of their standard deviations.
ρx/y = cov(X,Y)/ρx ρy

##### 4. What is scaling? Why is scaling performed? What is the difference between normalized scaling and standardized scaling? (3 marks)
Answer : Scaling is a data Pre-Processing step, which is applied to independent variables to normalize the data within a particular range,
Scaling is perfomed to contains features highly varying in magnitudes, units and range.Normalized Scaling brings all data to 0 or 1, whereas standardized scaling brings data in their normalized form.


##### 5. You might have observed that sometimes the value of VIF is infinite. Why does this happen? (3 marks)
Answer : If there is perfect correlation, then VIF = infinity. This shows a perfect correlation between two independent variables. In the case of perfect correlation, we get R^2 =1, which lead to 1/(1-R^2) infinity. To solve this problem we need to drop one of the variables from the dataset which is causing this perfect multicollinearity.

##### 6. What is a Q-Q plot? Explain the use and importance of a Q-Q plot in linear regression. (3 marks)
Answer : Quantile-Quantile (Q-Q) plot, is a graphical tool to help us assess if a set of data plausibly came from some theoretical distribution such as a Normal, exponential or Uniform distribution. If the two distributions being compared are similar, the points in the Q–Q plot will approximately lie on the line y = x. If the distributions are linearly related, the points in the Q–Q plot will approximately lie on a line, but not necessarily on the line y = x.
