# Class 2: Preprocessing, Counts, and Collocations 


### TL:DR
 - Required:
   - Download the Danish and English model for Stanza prior to class
   - Make sure you have joined the Element forum (Matrix)
   - Make sure you have everything set up from [class 1](classroom_materials/class_01/class_01.md)
 - Required if not familiar with these:
   - GitHub:
     - Watch the Youtube series: [Using GitHub with Visual Studio Code](https://www.youtube.com/watch?v=3Tn58KQvWtU&list=PLpPVLI0A0OkLBWbcctmGxxF6VHWSQw1hi)
     - Set up a GitHub with your studygroup and discover/resolve any issues you might have
   - Live Share
     - Watch video: [Live Share with Visual Studio Code](https://www.youtube.com/watch?v=8Ck2QhMxAYg)
     - Set up a live share session with your studygroup and discover/resolve any issues you might have
 - Recommended: 
   - Read the paper on [stanza](https://arxiv.org/abs/2003.07082) (6 pages)
   - Look into regular expressions for example [this 5 minute video](https://www.youtube.com/watch?v=UQQsYXa1EHs) or [this 6 minute read](https://medium.com/better-programming/introduction-to-regex-8c18abdd4f70)


---

## Plan for Class

In this class and the following we will build a `Text` class in Python which contains a which will be able to extract a variety of feautures from text. These include:
- sentence segmentation
- tokenization
- n-grams
- Token frequencies
- Outputting to dataframe
- Lemmatization *using Stanza*
- Part-of-Speech (POS) *tagging using Stanza*
- Named Entity Recognition (NER) *using regular expressions*

The class will also introduce some introduction to the module `os` for navigating your operating system.


## Class Competition
This class (and the following) will also include a small competition for the experienced users or for those who likes a challenge. I will try to make these throughout the classes so that the experienced user have something to work on. These will be development on utility tools. The winner will be decided on by the reminder of the class and the winner in most categories will be crowned as the NLP Champion!

For the first challenge is who can make the best function for visualizing word frequencies. Things you might consider:
Should the plot be interactive?
Should there be multiple plots?
How well does it deal with n-grams?
How should I make the function to make it easy for my fellow students to use?


---

## Download models for Stanza
Before class you should have downloaded the Danish and English model for Stanford's NLP library Stanza. If you don't have stanza installed see [class 1](classroom_materials/class_01/class_01.md).

For a guide on downloading stanza models follow these step for a bit more control (or if you have any issues) see their online [guide](https://stanfordnlp.github.io/stanza/download_models.html):
- Open your python editor of choice
- Run the following:

```Python
import stanza
stanza.download('en')
stanza.download('da')
```

## Github with Visual Studio Code
So instead of spending time in introducing GitHub in class. I recommend everyone check out the Youtube series: [Using GitHub with Visual Studio Code](https://www.youtube.com/watch?v=3Tn58KQvWtU&list=PLpPVLI0A0OkLBWbcctmGxxF6VHWSQw1hi). Note that the last video gives a couple of shorthands for creating and cloning repositories which are very convenient. I recommmend you also try creating a GitHub with your studygroup and spent time resolving any issues. For a *much more* extensive introduction see this [video](https://www.youtube.com/watch?v=RGOj5yH7evk).


As always you are free to use git however you like just so long that you are able to collaborate with your studygroup online. This is important given that future classes might end up taking place online due to Covid-19. 


## Live Share with Visual Studio Code
So instead of spending time in introducing Live Share in class. I recommend everyone check out the video: [Live Share with Visual Studio Code](https://www.youtube.com/watch?v=8Ck2QhMxAYg), which should give you a decent introduction. I recommmend you starting a session with your studygroup and see if you can:

1) See what eachother is working on 
2) Run code
3) See the result of code run by others
4) Open script located in the folder on the sharing parts laptop


As always you are free to not use Live Share just so long that you are able to collaborate with your studygroup online. This is important given that future classes might end up taking place online due to Covid-19.

---

## Materials used in Class



<!---
This class is intended as an introduction to pandas and numpy as well 


* re, os
* pandas, numpy ?
* python classes
-->
