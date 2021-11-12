# Data Science Basics and Exercises

## 1. Data Science Project Life Cycle

#### Business Understanding
- Identify business problems and define goals
- Identify data source that can help with answering questions, or need to collect more data?
- Define measurable success metrics, accuracy rate

#### <font color='blue'>Data Acquisition and understanding</font>
- Extract and load the data
- Explore the data: statistics, distributions and correlations, noise and outliers, missing data...
- Process the data to produce a clean, high-quality data set

#### <font color='blue'>Modeling</font>
- Feature engineering
- Model selection
- Model training and evaluation

#### Deployment
- Provide model prediction through appliation API

#### Customer acceptance
- System validateion
- User feedback

<font color='blue'> We focus on Data exploration, data processing, and modeling </font>


## 2. Data science tools and libraries
[__Python__](https://en.wikipedia.org/wiki/Python_(programming_language)) - the programming langualge for data science community
- Since 1991
- Simple to use, easy to understand. scientific community use it to glue many different software components

[__Numpy__](https://numpy.org) - highly efficient numarical array data operation with Python
- Since 1995
- Based on well-optimized C code, highly effifient for verctorized numarical computation
- Brings the computational power of languages like C and Fortran to Python, a language much easier to learn and use https://numpy.org

[__Matplotlib__](https://matplotlib.org) - Visulaization tool for python
- Since 2003
- A plotting library for python and its numerical mathematics extension NumPy
- Provides a MATLAB-like interface for python, being free and open-source
- Anatomy of a figure: https://matplotlib.org/stable/tutorials/introductory/usage.html#parts-of-a-figure
- Gallery and code https://matplotlib.org/stable/gallery/index.html

[__Pandas__](https://pandas.pydata.org) - Data analysis and manipulation tool for python
- Since 2008
- Data manipulation and analysis library for python wiritten in Python, Cython, and C

[__scikit-learn__](https://scikit-learn.org/stable/) - Machine Learning in Python
- Since 2007
- Provides simple API for various classification, regression and clustering algorithms https://scikit-learn.org/stable/

[__Jupyter Notebook__](https://jupyter.org) - interactive development interface and collaboration tool for data scientist
- Since 2015
- The open source web application used by data scientist to create and share documents that contain live code, equations, visualizations, and text

<font color='blue'> At this moment, we will skip SciPy for our data science exercises</font></br>
[__Scipy__](https://scipy.org) - Fundamental algorithms for scientific computing in Python
- Since 2001
- Builds on Numpy, provides comprehensive scientific computation functions.

## 3. Exercises

Follow the data science exercises in the following order:
1. [numpy_exercise](1_numpy_exercise.ipynb)
2. [pandas-exercise](2_pandas-exercise.ipynb)
3. [matplotlib-basic-exercise](3_Matplotlib-basic-exercise.ipynb)
4. [intro-to-machine-learning-with-scikit-learn](4_intro-to-machine-learning-with-scikit-learn.ipynb)
5. [logistic-regression](5_logistic-regression.ipynb)
6. [random-forest](6_random-forest.ipynb)
7. [text-classification](7_text-classification.ipynb)
8. [KMeans-clustering](8_KMeans-clustering.ipynb)
9. [principle-component-analysis](9_principle-component-analysis.ipynb)

## 4. Important topics and concepts

1. Feature engineering for text classification
   1. Bag og words
   2. TfIdf verctorization
   3. Pad sequence
   4. Word Embeding

2. Supervised and unsuperived learning
   1. Linear regression
   2. logistic regression, sigmoid function
   3. Bias vs variance
   4. Underfitting vs Overfitting
   5. Hyper-parameter tuning and Regularization

3. Model evaluation
   1. confusion matrix 
   2. Accuracy, Precision, Recall, F-score

## 5. Reference materials and online courses
1. https://www.coursera.org/learn/machine-learning
2. https://ibm-learning.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/ 
3. https://ibm-learning.udemy.com/course/linear-algebra-course
   




