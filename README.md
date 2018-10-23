# Mix-Match
#Coding challenge 
PROBLEM STATEMENT:
The problem is to model the interaction behaviour of an
android dialler - yes, where you have all the 26 characters
reachable on 12 keys - Look at the picture in case you have
not seen the android dialler. Model the keyboard in
software(no GUI required) to capture interaction with the
keyboard and output best matches and possible
suggestions.


Generate the dictionary - Your dictionary consists of all
possible 3 letter words that you can create from the 26
characters such that the resultant 3 letters have at-least
one vowel and has no duplicate characters. Eg words -
ARE, ASD, ERF, EAR, BAY, etc….
Generating the dictionary is part of the challenge and you
have model storage using an RDBMS and save the
dictionary in the RDBMS (open source - postgres, mysql,
etc).
Execution
The program should accept any 3 digits(duplicates allowed) string and generate a best match
and possible combinations. The best match is the string with the max number of vowels
followed by an ascending order in case of equality.

Sample Execution Logs
Case 1: 223 Best match -> ABE, matches -> ABD, ABE, ABF, ACD, ACE, ACF, BCE, BAD, BAE, BAF,
CAD, CAE, CAF, CBE
Case 2: 222 Best match -> ABC, matches -> ACB, CAB, CBA, BCA, BAC
Case 3: 779, best match -> None, matches -> None
