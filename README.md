# Statistical Data Analysis in Python

Intermediate Tutorial, PyTennessee 2014, 23 February 2014

**Christopher Fonnesbeck** - *Vanderbilt University School of Medicine*

This tutorial will introduce the use of Python for statistical data analysis, using data stored as Pandas `DataFrame` objects. Much of the work involved in analyzing data resides in importing, cleaning and transforming data in preparation for analysis. Therefore, the first half of the tutorial is comprised of an overview of basic and intermediate Pandas usage that will show how to effectively manipulate datasets in memory. This includes tasks like indexing, alignment, join/merge methods, date/time types, and handling of missing data. In the second half, participants will be introduced to methods for statistical data modeling using some of the advanced functions in Numpy, Scipy and Pandas. This will include fitting your data to probability distributions, estimating relationships among variables using linear and non-linear models, and a brief introduction to bootstrapping and kernel density estimation. Each section of the tutorial will involve hands-on manipulation and analysis of sample datasets, to be provided to attendees in advance.

### [Data Wrangling with Pandas](http://nbviewer.ipython.org/github/fonnesbeck/pytenn2014_tutorial/blob/master/Part%201.%20Data%20Wrangling%20with%20Pandas.ipynb) (60 min)

* Introduction to NumPy arrays
* Series and DataFrame objects
* Indexing, data selection and subsetting
* Hierarchical indexing
* Reading and writing files
* Date/time types
* String conversion
* Missing data
* Data summarization
* Indexing, selection and subsetting
* Reshaping DataFrame objects
* Pivoting
* Data aggregation and GroupBy operations
* Merging and joining DataFrame objects

### [Statistical Data Modeling](http://nbviewer.ipython.org/github/fonnesbeck/pytenn2014_tutorial/blob/master/Part%202.%20Statistical%20Data%20Modeling.ipynb) (50 min)

* Fitting data to probability distributions
* Kernel density estimation
* Ordinary least squares regression
* Logistic regression
* Bootstrapping

## Software Requirements

To follow along interactively with the tutorial, you should have the following Python packages installed:

* [NumPy](https://github.com/numpy/numpy)
* [SciPy](https://github.com/scipy/scipy)
* [Matplotlib](https://github.com/matplotlib/matplotlib)
* [statsmodels](https://github.com/statsmodels/statsmodels/) (optional)

These can most easily be installed via `conda` on the [Anaconda Python distribution](http://docs.continuum.io/anaconda/), or with the [Scipy Superpack](http://fonnesbeck.github.io/ScipySuperpack/) on OS X 10.9 (Mavericks).