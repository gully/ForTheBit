`ForTheBit` Jupyter Notebooks
===


## Contents

### Chapter 1: Data retrieval from fitbit API
1. Preliminaries and API with `curl`
2. Request All Intraday Data
3. Merge Daily JSON into pandas `DataFrames`
4. Get Exercise Logs
5. Add Exercise Flags to Intraday TimeSeries
6. Get Weight Logs (with fitbit Aria)
7. Make Weight Timeseries

### *(pending)* Chapter 2: Exploratory analysis and plotting
### *(pending)* Chapter 3: Advanced data science and analytics
### *(pending)* Chapter 4: Cross-matching with external data sources
### *(pending)* Chapter 5: Comparison with other people




## Dependencies for Jupyter notebooks
You will need these python packages to run the Jupyter Notebooks

- Python 3
- numpy
- pandas
- matplotlib
- Jupyter

My most common imports are in a startup file on my retina Macbook Pro so that plots and numpy will just work out of the box since there is scarcely a Jupyter notebook in which I do not use numpy or make a plot. You can read more about IPython startup files [here](https://ipython.org/ipython-doc/1/config/overview.html#startup-files).

`~/.ipython/profile_default/startup`

My IPython startup file:

```Python
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
%config InlineBackend.figure_format = 'retina'
%matplotlib inline
```
