# proj3-anagrams
Vocabularly anagrams game for primary school English language learners (ELL)


## Overview

A simple anagram game designed for English-language learning students in 
elementary and middle school.  
Students are presented with a list of vocabulary words (taken from a text file) 
and an anagram.  The anagram is a jumble of some number of vocabulary words, randomly chosen.  Students attempt to type vocabularly words that can be created from the  
jumble.  When a matching word is typed, it is added to a list of solved words. 

The vocabulary word list is fixed for one invocation of the server, so multiple
students connected to the same server will see the same vocabulary list but may 
have different anagrams.

## Authors 

Initial version by M Young; to be revised by CIS 322 students. 

## Status

flask_vocab.py and the template vocab.html are a 'skeleton' version 
of the anagram game for a CIS 322 project.  They uses conventional  
interaction through a form, interacting only when the user submits the form. 
Your assignment is to replace the interaction with AJAX interaction on each 
keystroke. 

## Minijax? 

flask_minijax.py and templates/minijax.html are a tiny example of using JQuery 
with flask for an Ajax application.  They should not be included in the
version of the project you turn in. 


## To run automated tests 
* `nosetests`

There are currently nose tests for vocab.py, letterbag.py, and jumble.py. 




//to run vocab
make run

//to run minimax
env/bin/activate
python3 flask_minijax.py
