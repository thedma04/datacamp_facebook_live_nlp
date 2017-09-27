
# Frequencies of words in novels: a Data Science pipeline

with DataCamp's very own Hugo Bowne-Anderson

## Description


In this live code-along session, you'll learn how to build a Data Science pipeline to plot frequency histograms of words in *Moby Dick*, among many other novels.
We won't give you the novels: you'll learn to scrape them from the website [Project Gutenberg](https://www.gutenberg.org/) using the Python package `requests` and how
to extract the novels from this web data using `BeautifulSoup`. Then you'll dive in to analyzing the novels using the Natural Language ToolKit (`nltk`).
In the process you'll learn about important aspects of Natural Language Processing (NLP) such as tokenization and stopwords.
You'll come out being able to visualize word frequency histograms of any novel that you can find on Project Gutenberg.
The NLP skills you develop, however, will be applicable to much of the data that Data Scientists encounter as the vast proportion of the world's data is unstructured data and includes a great deal of text.

## Prerequisites

Not a lot. It would help if you knew programming fundamentals and the basics of the Python programming language (e.g., variables, for loops) and had a bit of experience with Jupyter Notebooks.
However, I have always found that the most important and beneficial prerequisite is a will to learn new things so if you have this quality, you'll definitely get something out of this code-along session.


## Getting set up computationally

To get set up for this live coding session, clone this repository. You can do so by executing the following in your terminal:

```
git clone https://github.com/datacamp/datacamp_facebook_live_nlp
```

Alternatively, you can download the zip file of the repository at the top of the main page of the repository. If you prefer not to use git or don't have experience with it, this a goo option.

If you do not already have the [Anaconda distribution](https://www.anaconda.com/download/) of Python, go get it (n.b., you can also do this w/out Anaconda using `pip` to install the required packages, however Anaconda is great for Data Science and I encourage you to use it).

Navigate to the relevant directory `datacamp_facebook_live_nlp` and install required packages in a new conda environment:

```
conda env create -f environment.yml
```

This will create a new environment called fb_live_nlp. To activate the environment, execute

```
source activate fb_live_nlp
```

Then open the notebook `NLP_FB_live_coding.ipynb` and we're ready to get coding. Enjoy.


### Code
The code in this repository is released under the [MIT license](LICENSE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT). All text remains the Intellectual Property of DataCamp. If you wish to reuse, adapt or remix, get in touch with me at hugo at datacamp com to request permission.