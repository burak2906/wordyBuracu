# wordyBuracu
a wordle game in c

the program starts with the make command to run the program, then to run the executable created use ./main
then you will have to guess a word of 5 letters in no more than 6 attempts

there is already a predefined list of words, from which a random one is chosen, so if you choose an invalid word that does not appear in the list, it will not be set as an attempt!

a guess will look something like this:
Input a 5-letter word and press enter: state
Your hint: GY---
Word to find: s----
Try not to use: a, t, e

this means that I tried the word state, it is not the one I was looking for, but I found a green and a yellow letter
G(green) - the letter was found in the right position
Y(yellow) - the letter is in the word but in a different position

when the word is guessed you will be able to enter the ranking depending on how many attempts you had to guess the word
