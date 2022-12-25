# PREDICTION-OF-GPA-USING-MACHINE-LEARNING-ALGORITHM
⦁	DATA PREPROCESSING

When it comes to creating a Machine Learning model, data preprocessing is the first step marking the initiation of the process. Typically, real-world data is incomplete, inconsistent, inaccurate (contains errors or outliers), and often lacks specific attribute values/trends. This is where data preprocessing enters the scenario – it helps to clean, format, and organize the raw data, thereby making it ready-to-go for Machine Learning models.

1) IMPORT ALL THE CRUCIAL LIBRARIES
Since Python is the most extensively used and also the most preferred library by Data Scientists around the world, we’ll show you how to import Python libraries for data preprocessing in Machine Learning. 
The predefined Python libraries can perform specific data preprocessing jobs. Importing all the crucial libraries is the second step in data preprocessing in machine learning. The three core Python libraries used for this data preprocessing in Machine Learning are:
⦁	NumPy – For scientific calculation in Python and inserting any type of mathematical operation in the code, we have imported this library. 
⦁	Pandas – For data manipulation and analysis we have imported this library.

df= pd.read_csv(‘Dataset.csv’)
In this line of code, “df” denotes the name of the variable wherein we have stored the dataset. The function contains the name of the dataset as well. Once we execute this code, the dataset will be successfully imported. 
During the dataset importing process, there’s another essential thing we have done– extracting dependent and independent variables. For every Machine Learning model, it is necessary to separate the independent variables (matrix of features) and dependent variables in a dataset. 
In our data set:
dependent variables= CGPA
Independent variables=GPA of courses start with course code 1,2,3 and 4

2) SELECTION OF MACHINE LEARNING ALGORITHM 
We had implemented our models on 2 Algorithms. 
⦁	Linear Regression 
⦁	Polynomial Regression

REGRESSION
Regression analysis is a statistical technique for determining the relationship between a single dependent (criterion) variable and one or more independent (predictor) variables. The analysis yields a predicted value for the criterion resulting from a linear combination of the predictors. 

LINEAR REGRESSION
We had chosen a Linear Regression Algorithm to predict the GPA of both models. Linear regression is easier to use, simpler to interpret, and we obtain more statistics that help us to assess the model. It is one of the most commonly used predictive modeling techniques.It is represented by an equation 𝑌 = 𝑎 + 𝑏𝑋 + 𝑒, where a is the intercept, b is the slope of the line and e is the error term. This equation can be used to predict the value of a target variable based on a given predictor variable(s).

POLYNOMIAL REGRESSION
Polynomial provides the best approximation of the relationship between the dependent and independent variable. That’s why we had chosen a Polynomial Algorithm to predict the GPA of both models. It is used to study the isotopes of the sediments, study the rise of different diseases within any population, study the generation of any synthesis etc. Polynomial Regression is generally used when the points in the data are not captured by the Linear Regression Model and the Linear Regression fails in describing the best result clearly. A Broad range of functions can be fit under it. Polynomial basically fits a wide range of curvature
 
R SQUARED VALUE
R-Squared (R² or the coefficient of determination) is a statistical measure in a regression model that determines the proportion of variance in the dependent variable that can be explained by the independent variable. In other words, r-squared shows how well the data fit the regression model (the goodness of fit). A higher R-squared value will indicate a more useful beta figure. For example, if a stock or fund has an R-squared value of close to 100%, but has a beta below 1, it is most likely offering higher risk-adjusted returns.

MEAN SQUARED ERROR
The mean squared error (MSE) tells you how close a regression line is to a set of points. It does this by taking the distances from the points to the regression line (these distances are the “errors”) and squaring them. The squaring is necessary to remove any negative signs. The smaller the mean squared error, the closer you are to finding the line of best fit. Depending on your data, it may be impossible to get a very small value for the mean squared error.

