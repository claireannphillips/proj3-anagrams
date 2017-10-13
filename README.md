# proj3-anagrams
Vocabularly anagrams game for primary school English language learners (ELL)


## Overview

Name: Claire Phillips, cphillip@uoregon.edu

Point of project:A simple anagram game designed for English-language learning students in elementary and middle school.
Students are presented with a list of vocabulary words (taken from a text file) and an anagram. The anagram is a jumble of some number of vocabulary words, randomly chosen. Students attempt to type vocabularly words that can be created from the
jumble. When a matching word is typed, it is added to a list of solved words.

The vocabulary word list is fixed for one invocation of the server, so multiple students connected to the same server will see the same vocabulary list but may have different anagrams.


Instructions:
In the terminal git clone the repository and then cd into the project3 file.
Once in the project3 file, type make start which will install all of the 
neccessary files and then will tell you which port you need to type localhost
into to view the page. Type in the port which should be 8000 and then you can
play the game. Once done type make stop to kill the server. 


How to play the game: 

With the jumbled words create 3 words and if they match you will see them below
and once you get 3 yo uwill be redirected to a congratulations page.


List of dependencies: Python and bash
