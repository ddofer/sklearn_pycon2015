# Practical Machine Learning with SciKit-Learn Tutorial

*Dan Ofer*

- email:
- github: [ddofer](https://github.com/ddofer)

This repository will contain files and other info associated with my scikit-learn workshop at the Hebrew University.


## Installation Notes
This tutorial requires the following packages:

- Python version 2.6-2.7 or 3.3-3.4
- `numpy` version 1.5 or later: http://www.numpy.org/
- `scipy` version 0.10 or later: http://www.scipy.org/
- `matplotlib` version 1.3 or later: http://matplotlib.org/
- `scikit-learn` version 0.14 or later: http://scikit-learn.org
- `ipython` version 2.0 or later, with notebook support: http://ipython.org
- `seaborn` version 0.5 or later

The easiest way to get these is to use the [conda](https://store.continuum.io/) environment manager.
I suggest downloading and installing [miniconda](http://conda.pydata.org/miniconda.html).

Once this is installed, the following command will install all required packages in your Python environment:
```
$ conda install numpy scipy matplotlib scikit-learn ipython-notebook seaborn pandas
```

Alternatively, you can download and install the (very large) Anaconda software distribution, found at https://store.continuum.io/.

## Downloading the Tutorial Materials
I would recommend using iPython (Included as part of Anaconda) and git, not only for this tutorial.  Once git is installed, you can clone the
material in this tutorial by using the git address shown above:

    git clone git://github.com/ddofer/sklearn_pycon2015.git

If you can't or don't want to install git, there is a link to download
the contents of this repository as a zip file.  I may make changes to
the repository however.


## Notebook Listing
You can [view the tutorial materials](http://nbviewer.ipython.org/github/ddofer/sklearn_pycon2015/blob/master/notebooks/Index.ipynb) using the excellent nbviewer service.

Note, that you cannot modify or run the contents within nbviewer.
To modify them, first download the tutorial repository, change to the notebooks directory, and run ``ipython notebook``.
You should see the list in the ipython notebook launch page in your web browser.
For more information on the IPython notebook, see http://ipython.org/notebook.html

Note also that some of the code in these notebooks will not work outside the
directory structure of this tutorial, so it is important to clone the full
repository if possible (using GitHub).
