# m1-lsi2-ml-project

## Overview

m1-lsi2-ml-project is a project that aims to use Deep Learning techniques, for Machine Learning Module - M1 @ EFREI.

From a file containing 1 gb of tweets, create a model to predict positivity (or negativity).

It is written in Python and uses Jupyter Notebook.
  
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)

## Installation

Clone the Repository:
Open a terminal or command prompt and use the git clone command to clone the repository.

```
git clone https://github.com/clementnunes/devops-tp2
```

Navigate to the Project Directory:
Change your current directory to the one where the project has been cloned.

```
cd repository
```

## Usage
Use the Notebook [main.ipynb](https://gitlab.com/veekz/m1-lsi2-ml-project/-/blob/master/main.ipynb)
The Notebook can be accessed from [here](https://gitlab.com/veekz/m1-lsi2-ml-project/-/blob/master/main.ipynb)


## Features
The project is written in Python and uses some libraries for Machine Learning such as : 
- Pandas for data operations and analysis
- NumPy for math operations
- Natural Language Toolkit for word transformation
- Torch to improve performance
- Matplotlib for data visualization
- Seaborn for data visualization
- Scikit-Learn for ML

Note: The data set on the repository is an extract of the original one. You can get a bigger one [here](https://gitlab.com/veekz/m1-lsi2-ml-project).

First step is loading and cleaning data (remove non-consistent tweets)

Then we can show Data Distribution.

When data are words, we must operate on them :
- Cleaning (removing stopwords, decontract abbreviations, remove elements such as URL...)
- N-grams and Tokenization 

Then we can show word cloud of unigrams, bigrams and trigrams and Frequency Histogram.

Clustering Algorithm : K-means 

Training and evaluation of the model.

Then we draw the confusion matrixes and we conclude with F1 and accuracy of the model.


## Contact

**Clement Nunes**\
**clement.nunes@efrei.net**
