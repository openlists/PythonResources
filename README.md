# PythonResources

Open resources for learning and working with the Python programming language.

## Table of Contents

- [Overview](#overview)
- [Standard Python](#standard-python)
- [Scientific Python](#scientific-python)
- [Exercises](#exercises)
- [Topics](#topics)

## Overview

Python is a vast and very popular general-purpose programming language, with lot's of different materials available for lots of different use cases. This list is focused on curating materials focused on learning the basis of the Python programming language, and general numerical and scientific computing for the purposes of using Python in science.

The Python programming language is managed by the [Python Software Foundation](https://www.python.org/psf-landing/), which hosts their own [documentation page](https://docs.python.org/3/), as well as their own guide on [getting started with Python](https://www.python.org/about/gettingstarted/).

In terms of **version**, Python is now firmly on Python3, and we recommend using the more recent 3.X stable release of Python. Note that Python 2 is [effectively retired](https://python3statement.org), and there are many useful updates that make Python3 [worth updating to](https://github.com/arogozhnikov/python3_with_pleasure).

In terms of **ditributions and/or platforms** to manage Python, there are many, but a pretty typical approach is to use the [anaconda distribution](https://www.anaconda.com/distribution/) to get and manage Python, and to use the [Jupyter](https://jupyter.org) ecosystem, including their notebooks, for interactive computing.

For more generalized lists of Python resources, there are some other relevant lists:
- the [awesome python list](https://github.com/vinta/awesome-python) of everything Python
- the [awesome jupyter list](https://github.com/markusschanta/awesome-jupyter) of everything Jupyter

## Standard Python

The following are openly courses, resources and/or tutorials to learn standard library Python. 

### COGS18

COGS18: Introduction to Python is a class for beginners to learn the Python programming language, aimed at students in the cognitive science, psychology, and neuroscience to learn relevant programming skills. COGS18 was originally developed in the Cognitive Science department of UC San Diego by Tom Donoghue.

[Homepage](https://cogs18.github.io/intro/) -
[Github](https://github.com/COGS18)

### Software Carpentry

Software Carpenty creates lessons aimed at scientists, and  has a couple available lessons on the Python programming language. 

[Homepage](https://software-carpentry.org/) -
[Python Lesson 1](http://swcarpentry.github.io/python-novice-inflammation/) -
[Python Lesson 2](http://swcarpentry.github.io/python-novice-gapminder/)

### Codeacademy

Codeacademy has an online tutorial for Python, with an online interactive interpreter to try out some code. 

You may need to sign-up for codeacedemy, but you can do many of the lessons for free.

[Homepage](https://www.codecademy.com/)

### Whirlwind Tour of Python

Whirlwind tour of Python, by Jake VanderPlas, is a quick introduction to the Python programming language, aimed at people who already have a general sense of programming and want to learn the Python syntax. 

[Homepage](https://www.oreilly.com/library/view/a-whirlwind-tour/9781492037859/) -
[Textbook](http://www.oreilly.com/programming/free/files/a-whirlwind-tour-of-python.pdf)
[Github](https://github.com/jakevdp/WhirlwindTourOfPython)

### Python Tips: Intermediate Python

Intermediate Python is a collection of materials for learning Python intermediate-level tips and tricks, for after you've learned the basics. 

[Homepage](https://book.pythontips.com/en/latest/) - 
[Github](https://github.com/yasoob/intermediatePython)

## Scientific Python

By scientific python, it's just meant the tools and communities in Python that focus on scientific & data applications. Generally, this is clustered around the [scipy](https://www.scipy.org/about.html) ecosystem. 

The core scientific computing tools in Python include:
- [numpy](https://numpy.org) for numerical computing, and data array management
- [pandas](https://pandas.pydata.org) for managing and analyzing heterogenous data
- [matplotlib](https://matplotlib.org) for plotting and all kinds of visualizations
- [scipy](https://www.scipy.org/scipylib/index.html) for general scientific computing
- [scikit-learn](https://scikit-learn.org/stable) for machine learning

Each of the above tools have their own documentation, user guides and tutorials for learning their respective tools and applications. 

### Scipy Lectures

The scipy organization has a course for learning the scipy ecosystem.

[Homepage](https://scipy-lectures.org/) - 
[Github](https://github.com/scipy-lectures/scipy-lecture-notes)

### Python Data Science Handbook

The Python Data Science Handbook, by Jake VanderPlas, is an openly available resource for learning data science in Python. 

[Homepage](https://jakevdp.github.io/PythonDataScienceHandbook/)
[Textbook](http://shop.oreilly.com/product/0636920034919.do)
[Github](https://github.com/jakevdp/PythonDataScienceHandbook)

### From Python to Numpy

From Python to Numpy, by Nicolas Rougier, is an in depth introduction to numpy, focused on migrating from standard Python approaches to leveraging numpy, through vectorization. 

[Homepage](https://www.labri.fr/perso/nrougier/from-python-to-numpy/) - 
[Github](https://github.com/rougier/from-python-to-numpy)

### IPython Cookbook

The IPython Cookbook is an openly available collection of numerical computing examples and workflows, in Jupyter notebooks.

[Homepage](https://ipython-books.github.io) - 
[Github](https://github.com/ipython-books/cookbook-2nd)

### Data Science in Practice

Data Science in Practice is a course taught and developed at UC San Diego (as COGS108) with openly available materials for doing data science with Python.

[Github](https://github.com/COGS108)

## Exercises

The following are resources of exercises, or similar, that you can work through for practice with Python. 

The following are exercises related to standard Python:
- [Pytudes](https://github.com/norvig/pytudes) is a collection of practice problems
- [Python Koans](https://github.com/gregmalcolm/python_koans) is a collection of problems to learn Python

The following are exercises or collections related to numerical or scientific computing with Python:
- A collection of [algorithms](https://github.com/TheAlgorithms/Python)
- A collection of [100 numpy exercises](https://github.com/rougier/numpy-100)
- The [100 days of algorithms](https://github.com/coells/100days) challenge
- [Project Euler](https://projecteuler.net/) is a collection of math problems
  
## Topics

The following are some posts on particular topics in the Python language:
- A post on working with [lists](https://jeffknupp.com/blog/2018/12/13/how-to-do-just-about-anything-with-python-lists//)
- An explainer for [list comprehensions](https://www.datacamp.com/community/tutorials/python-list-comprehension)
- An overview & explainer of [Python Decorators](https://pabloariasal.github.io/python-decorators-from-the-ground-up/)
- An explainer of [@staticmethod & @classmethod](http://stackabuse.com/pythons-classmethod-and-staticmethod-explained/)
