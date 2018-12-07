# Getting Started with Natural Language Toolkit (NLTK)
## An interactive tutorial for beginners


## CS410 Text Information Systems, Technology Review, Fall 2018

Click here to start docker container at [mybinder](https://mybinder.org/v2/gh/jfmoran2/CS410_Public_TechReview/master)

### Authors
John Moran - jfmoran2: Division of Labor, 50% share: jointly reviewed existing tutorials for NLTK, Stopwords and Tokenizers: jointly worked on text and coding, Stemming and Lemmatization: text and coding, Parts of Speech Tagging: text and coding.

Graham Chester - grahamc2: Division of Labor, 50% share: jointly reviewed existing tutorials for NLTK, Downloading NLTK Data: text and coding, Basic NLTK Operations section: text and coding,  Stopwords and Tokenizers: jointly worked on text and coding.


## Functionality Overview
NLTK is a platform for writing Python programs for natural language processing (NLP) applications. This is a tutorial on some of the basic NLTK functionality and is meant as an introduction for beginners. 


## Installation

### Option 1: Cloud

There are two options for installation. The first is not actually an installation, no files or data will be written to your local machine. This Jupyter notebook can be started directly from [mybinder](https://mybinder.org/v2/gh/jfmoran2/CS410_Public_TechReview/master). It will take several minutes to start as it copies across file from this github [repo](https://github.com/jfmoran2/CS410_Public_TechReview), then builds and starts a docker container with the Python required libraries, but in the meantime you can browse the notebook itself.

### Option 2: Local Machine

The easiest way to install the prerequisites, if they are not already on your Windows, Mac or Linux machine, is to download and install Anaconda (Python version 3) from [here](https://www.anaconda.com/download), and then "conda install nltk", or refer to the official [NLTK website](http://www.nltk.org/install.html)

If you have an existing Python 3.5 or above installation and don't wish to install Anaconda, you can do the following, but you may need to be careful with versions:

```Python
pip install matplotlib jupyter nltk
```

Next, clone or download the GitHub repo from [here](https://github.com/jfmoran2/CS410_Public_TechReview). This contains the Jupyter notebook, NLTK_Tutorial.ipynb.

At a terminal/command line window you then type 'jupyter notebook' in the directory that contains the notebook. This will start the notebook server at port 8888 on your local machine and open a browser window. If you have any problems check this [quickstart guide](https://jupyter.readthedocs.io/en/latest/content-quickstart.html)

## Usage

Clicking on NLTK_PUBLIC_Tutorial.ipynb in the Jupyter notebook file browser window will open this notebook, and putting your cursor in a cell clicking on ">| Run" will run the cell. 