# finding-donors-supervised-learning
Project 6: Finding Donors for CharityML (Supervised Learning)

Introduction to Machine Learning with TensorFlow Nanodegree on Udacity.com

### Problem to solve

Construct a model that accurately predicts whether an individual makes more than $50,000. Employ several supervised algorithms of subiective choice to accurately model individuals' income using data collected 
from the 1994 U.S. Census. Choose the best candidate algorithm from preliminary results and further optimize this algorithm 
to best model the data. 

This sort of task can arise in a non-profit setting, where organizations survive on donations. Understanding an individual's 
income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to 
begin with. While it can be difficult to determine an individual's general income bracket directly from public sources, 
it is possible to infer this value from other publically available features.

This project is designed to get acquainted with the many supervised learning algorithms available in sklearn, 
and to also provide for a method of evaluating just how each model works and performs on a certain type of data. 

Things answered after completing this project:

- How to identify when preprocessing is needed, and how to apply it.
- How to establish a benchmark for a solution to the problem.
- What each of several supervised learning algorithms accomplishes given a specific dataset.
- How to investigate whether a candidate solution model is adequate for the problem.

### Install

This project requires **Python 3.x** and the following Python libraries/modules installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [platform](https://docs.python.org/2/library/platform.html)
- [time](https://docs.python.org/3/library/time.html)
- [seaborn](https://seaborn.pydata.org)
- [IPython.display](https://ipython.org/ipython-doc/3/api/generated/IPython.display.html)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Code

Code is provided in the `finding_donors.ipynb` notebook file. 
You will also be required to use the included `visuals.py` Python file and the `census.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for students to manipulate. 
If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

### Data

The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. 
This dataset is a modified version of the dataset published in the paper *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* by Ron Kohavi. 
You may find this paper [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), with the original dataset hosted on [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).
