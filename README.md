# Modelling Radioactive Decay Using Python 3
### Written by Inigo Val

### Why is programming important in Physics?

In this new era of technology, the computer is as important a part of a Physicist's tool box as a pencil and paper. Here are some reasons why:

* Physics is fundamentally data driven. We require data from experiments to drive our theoretical models and confirm or reject their hypotheses. In the past, measurements have been taken by hand (such as looking at photographic film and estimating the intensity of a star). However, this is vastly inefficient compared with an automated system using computers. For example, a new field called Astrostatics has recently emerged which directly tackles handling very large amounts of data (millions of measurements) by using the power of programming techniques such as machine learning.

![](images/lofar.jpg)
*The LOFAR radio telescope array uses machine learning to search for pulsars (collapsed neutron stars rotating at high speed)*

* There are many parts of Physics where creating a real life experiment is simply not feasible. For example, in Astrophysics we are trying to understand the mechanism by which black holes [accrete](https://en.wikipedia.org/wiki/Accretion_(astrophysics)) matter. This is quite hard to observe in detail as there are no black holes particularly close to us (thankfully!). The most popular way of testing new theories is therefore creating a simulation on a computer where we can encode our current laws of Physics and see how the system evolves in different scenarios.

![](images/black_hole_accretion.jpg)
*A black hole accreting mass from a star much like our own*

* The further you progress in Physics, the less 'neat' the solutions become. Often there is not one solution to a problem, but a _family_ of solutions from which we choose ones that fit based on some constraints. You may have experienced this already if you have studied differential equations in Maths. In real life situations, a computer is usually much better at finding a solution that fits if the constraints are complicated.


### What will I get out of doing this lab?

* Gain a basic understanding of the Python programming language and use of some scientific packages such as NumPy. This will greatly help you pick up any other programming language of your choice in the future.

* Have a taste of what an computing lab at university will feel like.

### Prerequisites

In this lab, we will be using the programming language Python 3 to create a model simulating the radioactive decay of a number of particles over time.

In order to complete this lab you should be comfortable with exponential decay and half lives. You must have come across vectors and matrices before (although no in depth knowledge is required). __No previous programming knowledge is required__. This excercise aims to be self contained so you should be able to jump right in without any prior reading. You are however encouraged to use google as you go through the excercises to help you understand/find syntax. 

We will mainly be using the [NumPy](http://www.numpy.org/) _package_ which provides a powerful framework for numerical computations in Python.

All excercises _without_ asterisks should be completed; tasks _with_ asterisks are extensions and are usually more exploratory these can be omitted until you have finished all other tasks.

### Starting the lab

* [Clone the repository](https://help.github.com/en/articles/cloning-a-repository). Make sure to do this in an empty folder.

* [Install Python 3](https://realpython.com/installing-python/). 

* [Install Jupyter Notebooks using Anaconda](https://jupyter.readthedocs.io/en/latest/install.html) (uses up a lot of space but is easier) or use Google to install it without (it is a simple process but depends on your operating system so I cannot provide a universal link). I would suggest Googling 'how to install jupyter notebooks on windows/mac/linux' if you have issues.

* Install NumPy. If you used Anaconda to install Jupyter Notebooks, this will have been done automatically. If not, I would again suggest using Google as it is slightly different depending on your operating system.

Copyright (c) 2019 Inigo Val Slijepcevic
