Jupyter Notebooks
===

### Dependencies for Jupyter notebooks
- Python 3
- numpy
- pandas
- matplotlib
- Jupyter

My most common imports are in a startup file on my retina Macbook Pro so that plots and numpy will just work out of the box, since there is scarcely a Jupyter notebook in which I do not use numpy or make a plot. You can read more about IPython startup files [here](https://ipython.org/ipython-doc/1/config/overview.html#startup-files).

`~/.ipython/profile_default/startup`

My IPython startup file:

```Python
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
%config InlineBackend.figure_format = 'retina'
%matplotlib inline
```
