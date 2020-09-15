Class 2: Introduction
============

## Videos 
[Intro to video lectures + Basic Text Processing and Edit Distance](https://www.youtube.com/playlist?list=PLSI4up6RakkjcdTwW6i_JAJuU5xmfX5tU)
(Playlist duration: 1 hours, 33 minutes) 

## Reading 
J+M 3rd Chapter 2 ["Regular Expressions, Text Normalization, Edit Distance", pages 1-25](https://web.stanford.edu/~jurafsky/slp3/2.pdf) 

[Think Like a Computer Scientist: 1.11. Formal and Natural Languages](https://runestone.academy/runestone/books/published/thinkcspy/GeneralIntro/FormalandNaturalLanguages.html) 

[Exploring the Linguistics Behind Regular Expressions](https://www.freecodecamp.org/news/exploring-the-linguistics-behind-regular-expressions-596fab41146/#:~:text=The%20difference%20between%20regular%20expressions,over%20time%20without%20human%20premeditation.)


## Study group exercises

### Reading questions

1. What are three examples of formal languages? 

2. Do you think studying formal language theory has a role in the study of cognitive science and/or linguistics? Why or why not? 

3. Why do you think natural languages are so different from formal languages? What would change if we all started using formal languages to communicate in everyday life? 

4. Why are Regexes *not* equivalent to regular grammars in the Chomsky Hierarchy? 

Note: Please post your answers in the week37 Slack channel by Wednesday 8am.

### Comprehension questions 
*From J+M 3rd Chapter 2 ["Regular Expressions, Text Normalization, Edit Distance"](https://web.stanford.edu/~jurafsky/slp3/2.pdf)*

2.1 Write regular expressions for the following languages.
* 1. 	the set of all alphabetic strings;

* 2.	the set of all lower case alphabetic strings ending in a b;

* 3. 	the set of all strings from the alphabet a,b such that each a is immediately preceded by and immediately followed by a b;

2.3 Implement an ELIZA-like program, using substitutions such as those described
on page 9. You might want to choose a different domain than a Rogerian psychologist, although keep in mind that you would need a domain in which your
program can legitimately engage in a lot of simple repetition.

2.5 Figure out whether *drive* is closer to *brief* or to *divers* and what the edit distance is to each. You may use any version of distance that you like.

2.6 Now implement a minimum edit distance algorithm and use your hand-computed
results to check your code.

2.7 Augment the minimum edit distance algorithm to output an alignment; you
will need to store pointers and add a stage to compute the backtrace.

Note: Please message your answers on Slack (your study group + Rebekah + Kenneth) by Wednesday 8am. 

