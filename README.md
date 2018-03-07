# Tutorial_Agent_Based_Models
A Short Tutorial on Agent Based Modeling in Python

Authors: Limor Raviv and Bill Thompson

*Updated: 07.03.2018*

## Summary

This repository contains three Jupyter notebooks offering a short tutorial on agent-based modeling using Python.
They are intended to offer anyone with little or no prior experience with Python the ability to incrementally construct a simple simulation of sound change in a population of agents with different personalities (stubborn or flexible learners). We will try to answer questions like: Has one of the variants spread to the entire community? Does this depend on the community's size and initial structure? How many stubborn people must be present to prevent (or facilitate?) convergence? etc.

This choice of model and questions reflect our personal theoretical interests: the cultural evolution of language through interaction in populations. However, we hope that the tutorials can also be of use to those who wish to build simulations of completely different topics, by modifying the basic parameters of the model. 

We aim for simplicity in design: agents are represented as simple Python lists whose elements represent their properties; populations are represented as lists of agents; evolution is implemented by looping over members of the population and modifying their properties. It is our hope that these implementational principles can be applied to a broad range of phenomena. In addition, any part of the code can be changed to introduce new features and constraints. 

Please let us know if you have any comments, suggestions or questions regarding this notebook!          
    

## Technical Requirements

To view the tutorial in the browser, just click on each notebook. For a more interactive experience in which you can fiddle with the code and run the simulations yourself, you can download the tutorial by clicking the green "Clone or Download" button at the top right of this page, and open it as a Jupyter Notebook. 

You'll need [Python](https://www.python.org/downloads/) and [Jupyter](http://jupyter.org) installed to run the notebooks yourself. We recommend using the [Anaconda](https://anaconda.org/anaconda/python) distribution of Python, which already includes everything you need including Jupyter. If you need any help with the installation process, you can check out these two tutorials: for installing Anaconda on [Windows](https://medium.com/@GalarnykMichael/install-python-on-windows-anaconda-c63c7c3d1444) or on a [Mac](https://medium.com/@GalarnykMichael/install-python-on-mac-anaconda-ccd9f2014072). We wrote the tutorial using Python 2.7, so it's probably better to use Python 2.7 to run the notebooks unless you understand the differences between Python versions 2.7 and 3.x.

For instructions on how to open and use jupyter notebooks, see [this page](http://jupyter.readthedocs.io/en/latest/running.html).  


## Notebooks
If you already know Python, jump straight to Part Two. 

### Part One:

[notebook here](https://github.com/Limor-Raviv/Tutorial_Agent_Based_Models/blob/master/Part%201%20-%20Python%20Basics%20for%20Agent%20Based%20Modelling.ipynb)

Part one lays out the Python basics. We hope that this notebook can be a good starting point even with no prior experience of programming, but it is designed to be readable in an afternoon by someone who understands how programming works in general (e.g. can code in another language, like R or Matlab), but doesn't have much experience with Python. 

You'll need to be reasonably comfortable with the material in this notebook to begin building the models in the following sections. 

To open the jupyter notebook, 

### Part Two:

[notebook here](https://github.com/Limor-Raviv/Tutorial_Agent_Based_Models/blob/master/Part%202%20-%20A%20Simple%20Agent%20Based%20Model%20in%20Python.ipynb)

Part two uses the knowledge from part one to build a model of communicating agents with different biases (vowel preferences, personality) step by step.

By the end of the notebook you'll be running multiple simulations on different conditions, and plot your results to see trends in interactions patterns.

### Part Three:

[notebook here](https://github.com/Limor-Raviv/Tutorial_Agent_Based_Models/blob/master/Part%203%20-%20A%20slightly%20More%20Complex%20Agent%20Based%20Model.ipynb)

Part three expands on the functions introduced in part two and introduces new features for building a slightly more complex and ecologically valid model of communicating agents.


We hope you'll find this tutorial useful, and we'd love to hear from you!

Contact Us: biltho@mpi.nl // limor.raviv@mpi.nl

 
