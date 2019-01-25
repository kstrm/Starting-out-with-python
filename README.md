# Getting going with Python and Jupyter notebooks

## Scientific python

Using Python with packages such as Numpy, Scipy, Pandas, Matplotlib, etc. (i.e., Scientific Python) is a powerful and easy way to perform scientific calculations and data analysis. Furthermore, coupling scientific Python with Jupyter notebooks makes for a fantastic way to both (1) perform calculation and (2) communicate your results and methods in an effective format. The merging of computations and communication with the Python + Jupyter notebook paring makes the combo and excellent choice for research, homework, and playing around with numbers and functions. The purpose of this repository is to help get students up and running with the basics of using Python and Jupyter notebooks for science calculations.

## Running python

**In the cloud**
* [CoCalc][1] (formerly SageMathCloud) is a good free resource for collaborative coding in python and many other languages. Using Python and/or Jupyter notebooks on CoCalc is a perfect place to start.

**On your local computer**
* Continuum Analytics “Anaconda” distribution: https://www.continuum.io/downloads
* To use, you can run/execute python commands with the terminal, an [ipython terminal][2], the [Spyder IDE][3] (a Matlab like environment), or my favorite (for short computations and data analysis) - [Jupyter notebooks][4] and [JupyterLab][5]. The examples in this repository are Jupyter notebooks.
* If you are looking for a text editor, I suggest taking a look at [Atom][6].

## The examples

Above are a few Jupyter notebooks with examples that highlight basic commands in Numpy, Scipy, and Matplotlib for simple procedures such as:
* indexing, arrays, and loops
* ways to approximate a derivative
* solving functions
* plotting

You can view the files simply by clicking on the file link in the directory above. To run the notebooks, you will either need to use a cloud-based computing service (such as CoCalc, see below), or you will need to install a python distribution on your computer (below you will find information on how to install python on your local machine). If you will be using python regularly, then I strongly suggest you install it on your local machine.

Note, to view the interactive plots in the example "03c Derivatives-Boken.ipynb", you will need to view it through the [nbviewer][7] at Jupyter.org. You can do so by [clicking here][8], or by clicking on the file of interest, copying the url from your browser, and then pasting it into the [nbviewer][9].

## Other Helpful Links

**Plotting**
* Basic… start here: [Matplotlib][10]. For more examples see [Chapter 4][11] Robert Johansson's Numerical Python.
* Interactive plotting: [Bokeh][12]
* Plotting Pandas dataframes: [link][13]

**Tutorials**
* [Python Tutorial for Absolute Beginners][14]
* [Jupyter Notebook Tutorial: The Definitive Guide][15]
* [Advanced Jupyter Notebooks: A Tutorial](https://www.dataquest.io/blog/advanced-jupyter-notebooks-tutorial/)
* Scientific Python Lectures ([All lectures][16]). Key lectures:
	* [Numpy][17]
	* [Scipy][18]
	* [Plotting][19]
* [Scipy Lecture Notes: One document to learn numerics, science, and data with Python][20]
* [Pandas Tutorial: DataFrames in Python][21]
* [Basic features of SageMathCloud][22] (note.. the video is long ≈ 1 hr)
* [Python Weekly][23] - a weekly email newsletter "featuring curated news, articles, new releases, jobs etc related to Python." 

[1]:	https://cocalc.com
[2]:	http://ipython.org/
[3]:	https://www.spyder-ide.org/
[4]:	http://jupyter.org/
[5]:	https://jupyterlab.readthedocs.io/en/stable/
[6]:	https://atom.io/
[7]:	http://nbviewer.jupyter.org/
[8]:	http://nbviewer.jupyter.org/github/kstrm/Starting-out-with-python/blob/master/03c%20Derivatives-Boken.ipynb
[9]:	http://nbviewer.jupyter.org/
[10]:	https://github.com/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb
[11]:	https://github.com/jrjohansson/numerical-python-book-code/blob/master/ch04-code-listing.ipynb
[12]:	http://bokeh.pydata.org/en/latest/
[13]:	http://pandas.pydata.org/pandas-docs/stable/visualization.html
[14]:	http://stackabuse.com/python-tutorial-for-absolute-beginners/
[15]:	https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook#gs.A793bLk
[16]:	https://github.com/jrjohansson/scientific-python-lectures
[17]:	http://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-2-Numpy.ipynb
[18]:	http://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-3-Scipy.ipynb
[19]:	https://github.com/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb
[20]:	http://www.scipy-lectures.org
[21]:	https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python#gs.D1109lg
[22]:	https://www.youtube.com/watch?v=_ff2HdME8MI
[23]:	https://www.pythonweekly.com