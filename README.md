<h1> Decision-Tree-Implementation</h1>
<h3> Building a Decision Tree classifier from scratch :-) </h3> <br>
The decision tree has been built from scratch .The PDF files contain the actual tree implementation.Printing steps for every split in the decision tree for the iris data.
At last there is a comparision done using the inbuilt sklearn Decision tree and comparing it with our model on the same dataset.


## About the Dataset
The "Iris" dataset as been used in the implementation. Originally published at [UCI Machine Learning Repository: Iris Data Set](https://archive.ics.uci.edu/ml/datasets/Iris), this small dataset from 1936 is often used for testing out machine learning algorithms and visualizations. 
Each row of the table represents an iris flower, including its species and dimensions of its botanical parts, sepal and petal, in centimeters.

You can load it within your notebook from `sklearn.datasets` using the following snippet:
```python
from sklearn import datasets
iris = datasets.load_iris()
```
Checkout more such datasets at [scikit-learn.org](https://scikit-learn.org/stable/datasets/index.html#toy-datasets)


## Python environment   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ayanava-99/Decision-Tree-Implementation/blob/master/Decision%20Tree%20Implementation.ipynb)
Give it a try, no need of installations!


## Notes
If you still insist to run it on your PC, well the `requirements.txt` file should list all Python libraries that the notebook
depends on, please install them on a virtual env using:
Anaconda:
```
$ conda create --name newenv --file requirements.txt
```
Python3
```
$ pip3 install -r requirements.txt
```

