+++
title = "Software"
author = ["Daniel Fleischer"]
lastmod = 2020-09-18T15:19:29+03:00
draft = false
weight = 2001
noauthor = true
nocomment = true
nodate = true
nopaging = true
noread = true
[menu.main]
  weight = 2001
  identifier = "software"
+++

We choose python as the main language. Make sure you have the latest python, e.g. `3.8`.

Familiarize yourself with the python package manager `pip3`; install the following packages:

`numpy`
: vectors and arrays structures and many mathematical functions.

`pandas`
: Data frames structures.

`matplotlib`
: Plotting library.

`sklearn`
: Machine learning algorithms as well as many helpful functions dealing with data.

`jupyterlab`
: Notebooks environment for development and experimentation.


## Jupyter Lab {#jupyter-lab}

Jupyterlab is a very useful environment for development and experimentation. It has many advantages:

1.  Can work with multiple languages, not just python - R, julia, spark, etc.
2.  Based on `ipython`; i.e. code completion, functions documentation, magic commands.
3.  Can combine code, documentation (markdown), latex and visual plots.
4.  Has many plugins to extend functionality.
5.  Open source and free.

However it does have some disadvantages:

1.  Notebooks are saved as `*.ipynb` which are hard-to-read `json` files.
2.  When using `git`, diffs are hard to understand, unless using the plugin `nbidme`.
3.  Editing abilities are limited compared to a full fledge IDE, such as PyCharm or even dedicated code editors.
