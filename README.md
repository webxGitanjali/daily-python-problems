# daily-python-problems
New python problems everyday

Problem  1: Statement
You're given a string s which is a word (no spaces). Write a program to check:

If the length of the word is even, print "EVEN LENGTH".

If the length is odd, print "ODD LENGTH".

Code:

s = input("Enter a word: ")

if len(s) % 2 == 0:
    print("EVEN LENGTH")
else:
    print("ODD LENGTH")

