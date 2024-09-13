# Implementation of a Hotel Booking Cancellation predictive model using machine learning algorithms.

Following are the steps for the implementation.
*Exploratory Data Analysis*,
*Data Pre-Processing*,
*Model Building* and
*Model Comparison*

**Phases Involved in Exploratory Data Analysis**
**Data Collection**
Collecting data is a starting point of exploratory data analysis. Data collection is the process of finding data from different public sites, or one can buy from private organizations and load data into our system. Kaggle and Github are familiar and known sites that provide free data.

**Import Libraries**
After collecting data we have to import the necessary libraries to build machine learning models. Numpy, Pandas, Matploilib, Seaborn are the known libraries used in the machine learning model.

Numpy: NumPy is a Numerical Python Library that helps perform mathematical operations.
Pandas: Panda is an open-source library that helps understand relational or labelled data.
Matplotlib: Matplotlip is a Python visualization library that helps visualize 2D array plots.
Seaborn: Seaborn is a data visualization library built on top of matplotlib.

**Visualising Data by**
*Scatter Plot
A scatter plot represents every data point in the graph format. It shows the relationship of two data means how the values from one column fluctuate according to the corresponding values in another column.

*Pair Plot
Pair plots compare multiple variables at the same time. Pair plots save spaces and compare various variables at the same time.

*Correlation Matrix
A correlation matrix glimpses the correlation between different variables. The correlation between two variables is determined by the correlation coefficient.

**Model Building**
Random Forest Algorithm
Random Forest is a popular supervised machine learning algorithm. The random forest algorithm implements both Classification and Regression problems in ML. The Random Forest is a classifier that includes several decision trees instead of relying on one decision tree, the random forest takes the prediction from each tree, and based on the majority votes of predictions, it predicts the final output. The greater number of trees in the forest leads to higher accuracy and prevents the problem of overfitting.

**Summary**
The given dataset is a supervised classification dataset. It holds booking information for a city hotel and a resort hotel with information such as How and when the booking was made, the length of passengers’ stay with the number of parking slots available, the number of adults, children, and babies. The Logistic regression, K-Nearest Neighbor, Decision Tree, Random Forest algorithms are used to handle this supervised classification model. Among these four machine learning algorithms, Random forest and Decision trees perform well with respect to accuracy.
