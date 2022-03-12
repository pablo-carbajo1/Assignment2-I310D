# Assignment2-I310D

In this assignment, I explored the concept of bias through querying the Perspective API released by Google Jigsaw. I examined a dataset of internet comments and their scores that calculate how toxic they are from 0 to 1 (0 being not toxic at all and 1 being severely toxic). 

For this assignment, my hypothesis was: Are comments that use grawlixs (using symbols to replace letters in a swear wotd) and comments where swear words are mispelled do they have a lower toxicity score than comments where the swear words are properly spelled. 

I had three examples to verify my hypothesis and I believe that the model isn't as developed because it can't detect that a word is a swear word if it includes a symbol or if it's misspelled. It can still detect the comment being toxic but not with the same level of accuracy.  

For all three examples the toxicity score was lower for the comments that were either misspelled or had symbols instead of letters inside the words. The results were: 0.989 vs. 0.949, 0.969 vs. 0.921, and 0.968 vs. 0.949. We can see that the model can classify them as toxic but not as toxic as the comments where the swear words are correctly spelled. 

I believe that the model that gives the comments a score isn't as developed or can't detect a swear word that is misspelled or includes a swear word as well as if it were correctly spelled. Inside the model's database they should include different variations of swear words to classify them properly. This is an issue because a computer can only read letter by letter and if it makes sense, but a normal human can read these swear words normally and understand what they are saying. 
