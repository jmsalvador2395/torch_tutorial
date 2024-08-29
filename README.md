# Overview
This repository is a short tutorial on [PyTorch](https://pytorch.org/).
This tutorial contains 4 jupyter notebooks

1. A review/intro to the [NumPy](https://numpy.org/) library.
2. An intro to [torch tensors](https://pytorch.org/docs/stable/generated/torch.tensor.html) and how they relate to [numpy arrays](https://numpy.org/doc/stable/reference/generated/numpy.array.html)
3. An implementation of the SVM classifier using NumPy
4. The SVM classifier ported to PyTorch

# Installation
1. (Optional but recommended) Create and activate a virtual environment. This project was created using python `3.11.8` but anything `>=3.6` is probably fine for this tutorial. Refer to the following for different ways to create virtual environments
    * [virtualenv](https://virtualenv.pypa.io/en/latest/user_guide.html)
    * [venv](https://docs.python.org/3/library/venv.html)
    * [anaconda](https://anaconda.org/anaconda/python)
    * [miniconda](https://docs.anaconda.com/miniconda/)
    * [pyenv](https://github.com/pyenv/pyenv)
2. Open a terminal and change to the project directory
3. Run `pip install -r requirements.txt`. This installs the python dependencies. You can open `requirements.txt` in a text editor to view which ones
4. Run your `.ipynb` files using either of the 2 methods. There may be easier ways but these are what I know of.
    * Set up your [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html) server, connect, and then run your file.
    * Run them directly in [VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).