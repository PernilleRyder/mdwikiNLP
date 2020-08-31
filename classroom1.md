# Class 1
This class will focus on setting everything up for the semester, thus is it extremely important you do the setup before class. If there is any issues this will be the class where we have the time to deal with them.

### TL:DR
 - Install/update anaconda
 - Install Visual Studio Code and extensions listed
 - Install git and make a GitHub account

The above are not mandatory, but recommended for following the course


## Anaconda
We will be using the Anaconda Distribution for python. If you haven’t Installed it you can install it using their website. If you have it installed it be sure to update it using the command:

`conda update conda`

If you feel a bit experimental I would personally recommend using homebrew to install anaconda for MacOS users. 

You are not required to use the Anaconda Distribution, only recommended, however if you choose not to please make sure you have the required packages installed and that your python installation is properly set up with your code editor.

## Visual Studio Code
I will be using Visual Studio Code (VS code) as my code editor, I recommend you use it as well, but you are free to use any code editor you want. You can install it from their website. The reasons why I recommend it is due to its integration with GitHub, it wonderful extensions as well as it ability to co-edit code in a google docs style format. If you choose to download this I recommend the following extensions:

|Extension| Usage | 
|---|---|
|Python | (for python integration) |
|Live Share | (for a google doc like collaboration) |
|Markdown All in One | (for editing markdown) |
|Rainbow CSV |				(for convenient CSV editing) |
|Code Spell Checker | (a spell checker for your specific language) |


## Github
We will be using GitHub for version control, please make a GitHub account before class and make sure you have git installed on your machine. If you haven’t used GitHub before I recommend you take some time doing the GitHub QuickStart.


## Class Plan:
1.  setup a virtual environment, but feel free to do it beforehand see setup guide below
2. We will install the required packages, again feel free to do it beforehand see below
3. Look at VS code so everyone is familiar with the setup
4. We will make sure everyone reacquaint themselves with using git for version control (in the context of VS code)
5. If we have the time run example code on Zipf’s Law which will include
    1. General idea of how we process language
    2. Introduction to python script structure
    3. Introduction to the use of VS Code in a workflow
    4. Look into linguistic feature which might be relevant for predicting a bestseller?
        1. Word frequency and inverse word frequency
        2. The use of “the”?


## The NLP virtual env setup guide:
- Open anaconda prompt on windows or terminal on MacOS/Linux 
- Run the following:
  - `conda create -n nlp tensorflow`
  - `conda activate nlp`
  - `pip install numpy pandas jupyter gensim sklearn nltk stanza spacy flair danlp flake8`


## Required Packages:
installed using the command:
`pip install packagename`
where packagename in name of the package
|Package| Usage | 
|---|---|
|**General Python** |  |
|numpy | (Mathematical plugin for vector and matrice manipulation)|
|pandas | (Dataframe for python)|
|jupyter | (for notebook style code editing)|
|**Machine learning**||
|gensim| |
|tensorflow | (version 2 - for Keras)|
|scikit-learn | (installed using sklearn) |
| **Language** ||
|nltk ||
|stanza | (stanford’s NLP Framework)|
|spacy |  (a NLP framework)|
|flair| (Zalando Research’s NLP Framework)|
|danlp |(a Danish NLP Framework built on flair)|
|**Other**||
|flake8 |(a linter for python, i.e. an code spell checker)|