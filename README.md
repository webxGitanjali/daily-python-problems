# daily-python-problems
New python problems everyday

Problem  1: Statement - 
You're given a string s which is a word (no spaces). Write a program to check:
If the length of the word is even, print "EVEN LENGTH".
If the length is odd, print "ODD LENGTH".

Code: Answer -

    s = input("Enter a word: ")

    if len(s) % 2 == 0:
        print("EVEN LENGTH")
    else:
        print("ODD LENGTH")

Problem 2: Statement -
You’re given a string. Write a program to check if the first and last characters of the string are the same.
If they match, print "MATCH".
Otherwise, print "NO MATCH".

Code: Answer -

    word = input("Enter a word: ")

    if word[0] == word[-1]:
        print("MATCH")
    else:
        print("NO MATCH")

Problem 3: Statement -
Write a program that takes a lowercase word as input and counts how many vowels (a, e, i, o, u) it contains.
Then print the number of vowels in the word.

Code: Answer - 
    
    word = input("Enter a word: ")
    vowel_count = (
        word.count('a') +
        word.count('e') +
        word.count('i') +
        word.count('o') +
        word.count('u')
    )

    print(vowel_count)






