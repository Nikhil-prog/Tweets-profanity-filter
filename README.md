# Degree-of-Profanity

### Problem: 
Given a set of words that indicates racial slurs.
Write a python program to indicate the degree of profanity 
for each sentence in a file that contains the tweets(statments).
### Assumption:
- The file only contains the tweets and each sentence ends with a full stop('.').
- The use of full stop is not use as any other symbol.
- The use of full stop is only to end a sentence.
- Any tweet can have any length and can also be adjust in multiple line.
- The set of racial slur words contained in a txt file with space seprated and/or newline.
- The New tweet(or new sentence of a tweet) ALWAYS starts with a Space.
### Corner case Handling:
- The Handling of racial slurs is not Case sensitive(lower or upper or mixture can be detected)
- It can handle the both case of full stop attached with end word or there is space between them
(A beautiful flower. or A beautiful flower . )
### Output:
Each line is printed along with it's degree of profanity.
e.g  "sentence" >> Degree of profanity
