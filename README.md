# Unsupervised Learning
## Project: Density-Based-Clustering-Demo

### Install

This project requires **Python 3.6** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
ipython notebook DBSCAN Notebook.ipynb
```  
or
```bash
jupyter notebook DBSCAN Notebook.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Density Based Clustering Demo

It is a density-based clustering algorithm: given a set of points in some space, it groups together points that are closely packed together (points with many nearby neighbors), marking as outliers points that lie alone in low-density regions (whose nearest neighbors are too far away).

![png](https://github.com/shashank136/Density-Based-Clustering-Demo/blob/master/images/dbcluster.png)

### Observation for the used dataset

#### For Eps = 1.3 and min_samples = 10

![png](https://github.com/shashank136/Density-Based-Clustering-Demo/blob/master/images/dbcluster1.png)

#### Relation between Eps and the min_samples

![png](https://github.com/shashank136/Density-Based-Clustering-Demo/blob/master/images/dbcluster2.png)
