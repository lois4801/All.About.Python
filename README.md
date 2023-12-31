# All.About.Python>> ML libraries
Python Hacks, Data Analysis, Cleaning, Transformation, Wrangling/Munging, Modeling, Data Science, ML

# MY_NOTES:

### What is Data Wrangling?
- Data wrangling, also referred to as data munging, is the process of converting and mapping data from one raw format into another. The purpose of this is to prepare the data in a way that makes it accessible for effective use further down the line. Not all data is created equal, therefore it’s important to organize and transform your data in a way that can be easily accessed by others
- Benefits of Data Wrangling
Although data wrangling is an essential part of preparing your data for use, the process yields many benefits. Benefits include:

Enhances ease of access to data
Faster time to insights
Improved efficiency when it comes to data-driven decision making

### Scikit Learn
- scikit-learn is a free, open-source machine learning library for the Python programming language. It provides a range of supervised and unsupervised learning algorithms in Python. The library is built on top of other widely used libraries such as NumPy, SciPy, and matplotlib 

scikit-learn includes various classification, regression, clustering, and dimensionality reduction algorithms, and it is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy. It also provides tools for model selection, preprocessing, feature extraction, and more 


### Label encoding
- is a technique used in machine learning and data analysis to convert categorical variables into numerical format. It is particularly useful when working with algorithms that require numerical input, as most machine learning models can only operate on numerical data. In this explanation, we’ll explore how label encoding works and how to implement it in Python.

Let’s consider a simple example with a dataset containing information about different types of fruits, where the “Fruit” column has categorical values such as “Apple,” “Orange,” and “Banana.” Label encoding assigns a unique numerical label to each distinct category, transforming the categorical data into numerical representation.

To perform label encoding in Python, we can use the scikit-learn library, which provides a range of preprocessing utilities, including the LabelEncoder class. https://www.mygreatlearning.com/blog/label-encoding-in-python/ 


### Variance Inflation Factor
- The variance inflation factor (VIF) is a measure used to detect multicollinearity in a regression model. Multicollinearity occurs when two or more predictor variables in a regression model are highly correlated, which can lead to unreliable and unstable estimates of the regression coefficients.

VIF quantifies how much the variance of an estimated regression coefficient is inflated due to multicollinearity in the model. A VIF of 1 indicates that there is no correlation between a given predictor variable and the other predictor variables in the model, while a VIF greater than 1 indicates the presence of multicollinearity. As a rule of thumb, VIF values exceeding 4 warrant further investigation, while VIF values exceeding 10 are signs of serious multicollinearity requiring correction.


