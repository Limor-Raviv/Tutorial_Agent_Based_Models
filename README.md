# Tutorial_Agent_Based_Models
A Short Tutorial on Agent Based Modeling in Python

Authors: Limor Raviv and Bill Thompson
*Updated: 23.11.2017*

## Summary

This repository contains three Jupyter notebooks offering a short tutorial for agent-based modeling using Python.
They offer anyone with no prior Python knowledge the ability to incrementally construct a simple simulation of sounds change in a population of agents with different personalities (stubborn or flexible). We will try to answer questions like: Has one of the variants spread to the entire community? Does this depend on the community's size and inital structure? How many stubborn people must be present to prevent (or faciliate?) convergence? etc.

This choice of model and questions reflect our perosnal theoretical interests: the cultural evolution of language through interaction in populations. However, we hope that the tutorials can also be of use to those who wish to build simulations of completely different topics by modifying the basic parameters of the model. 

We aim for simplicity in design: agents are represented as simple Python lists whose elements represent their properties; populations are represented as lists of agents; evolution is implemented by looping over members of the population and modifying their properties. It is our hope that these implementation principles can be applied to a broad range of phenomena.
In addition, any part of the code can be changed to introduce new features and constraints. 

Please let us know if you have any comments, suggestions or questions regarding this notebook!          
    

## Technical Requirements

To only view the tutorial in the browser, just click on each notebook. 
For a more interactive experience in which you can fiddle with the code and run the simulations yourself, you can download the tutorial by clicking the green "Clone or Download" button at the top right of this page. 

You'll need [Python](https://www.python.org/downloads/) and [Jupyter](http://jupyter.org) installed to run the notebooks yourself. We recommend using the [Anaconda](https://anaconda.org/anaconda/python) distribution of Python, which already includes everything you need including Jupyter. We wrote the tutorial using Python 2.7, so it's probably beter to use Python 2.7 to run the notebooks unless you understand the differences between Python versions 2.7 and 3.x.


## Notebooks
If you already know Python, jumpy straight to Part Two. 

### Part One:

[notebook here](https://github.com/Limor-Raviv/Tutorial_Agent_Based_Models/blob/master/Part%201%20-%20Python%20Basics%20for%20Agent%20Based%20Modelling.ipynb)

Part one lays out the Python basics. We hope that even somebody who hasn't used any programming language before could follow this notebook, but it is designed to be readble in an afternoon by someone who understands how programming works generally (e.g. can code in another language, like R or Matlab), but doesn't have much experience with  Python. 
You'll need to be reasonably comfortable with the material in this notebook to begin building the models in the following sections. 

### Part Two:

[notebook here](https://github.com/Limor-Raviv/Tutorial_Agent_Based_Models/blob/master/Part%202%20-%20A%20Simple%20Agent%20Based%20Model%20in%20Python.ipynb)

Part two uses the knowledge from part one to build a model of communicating agents with different biases (vowel preferences, personality) step by step.
By the end of the notebook you'll be running multiple simulations on different conditions, and plot your results to see trends in interactions patterns.

### Part Three:

[notebook here](https://github.com/Limor-Raviv/Tutorial_Agent_Based_Models/blob/master/Part%203%20-%20A%20slightly%20More%20Complex%20Agent%20Based%20Model.ipynb)

Part three expands on the functions introduced in part two and introduces new features for building a sligfhtly more complex and ecologically valid model of communicating agents.

Hope you'll find this tutorial useful, and we'd love to hear from you!

Contact Us: biltho@mpi.nl // limor.raviv@mpi.nl

 
