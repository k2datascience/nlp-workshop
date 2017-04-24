# NLP Workshop

Welcome to this repository. I have instructions and resources so you can get up to speed.

1. You will need Python installed on your computer and other data science packages. I use the [Anaconda distribution of Python 3.6](https://www.continuum.io/downloads).

2. If you are comfortable with Git, make sure to clone this repository on your local computer, otherwise you can simply download a zip archive by clicking on the green button on the top right of the page.

3. Make sure you are familiar with Python syntax. There is a [review Jupyter notebook](./intro_to_python.ipynb) in this repository. Make sure you can go into your terminal and run the command `jupyer notebook`. A notebook server should start and you will be able to view, create and save notebooks.

4. We will be using TextBlob. Make sure to run these commands in your terminal / shell.

       $ pip install -U textblob
       $ python -m textblob.download_corpora

5. We will be using the [Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) provided by Kaggle. The associated data files are located in the [data folder](./tweets.csv).

6. You should be able to import the following packges without a problem. If you get an error, `pip install` or `conda install`.

        $ import pandas
        $ import numpy
        $ import textblob

----------

Organized by [K2 Data Science](http://www.k2datascience.com).
