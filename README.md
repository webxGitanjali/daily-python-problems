# daily-python-problems
# New python problems everyday

Problem  1: Statement -
You're given a string s which is a word (no spaces). Write a program to check:
If the length of the word is even, print "EVEN LENGTH".
If the length is odd, print "ODD LENGTH".

Code:

    s = input("Enter a word: ")

    if len(s) % 2 == 0:
        print("EVEN LENGTH")
    else:
        print("ODD LENGTH")

Problem 2: Statement -
You’re given a string. Write a program to check if the first and last characters of the string are the same.
If they match, print "MATCH".
Otherwise, print "NO MATCH".

Code:

    word = input("Enter a word: ")

    if word[0] == word[-1]:
        print("MATCH")
    else:
        print("NO MATCH")

Problem 3: Statement -
Write a program that takes a lowercase word as input and counts how many vowels (a, e, i, o, u) it contains.
Then print the number of vowels in the word.

Code:
    
    word = input("Enter a word: ")
    vowel_count = (
        word.count('a') +
        word.count('e') +
        word.count('i') +
        word.count('o') +
        word.count('u')
    )

    print(vowel_count)

Problem 4: Statemet - 
print the elements of the following list using a loop.
list - [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

Code:

    num = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
    index = 0
    while index < len(num):
        print(num[index])
        index += 1

Problem 5: Statement - 
print the multiplication table of a number n

Code:

    n = int(input("Enter n : "))
    i = 1
    while i<=10:
        print(n*i)
        i += 1

Problem 6: Statement -
search for a number x in this tuple using loop:
Tuple - (1, 4, 9, 16, 25, 36, 49, 64, 81, 100)

Code:

    tup = (1, 4, 9, 16, 25, 36, 49, 64, 81, 100)
    x = int(input("Entr number: "))
    index = 0
    while index < len(tup):
        if (tup[index] == x):
            print("found at index",index)
            break
        index += 1

Problem 7: You have a fixed amount of money in your wallet and you spend it on various activities during the week. In this task, you’ll calculate:

The total money spent.
The remaining balance in your wallet after subtracting those expenses.
Data Values
• Initial wallet balance: $100
• Groceries expense: $30
• Entertainment expense: $20

Expected Output
If the total money spent is 50 and the remaining balance is 50 , then the output should be:

code:

    initial_wallet_balance = 100
    Groceries_expense = 30
    Entertainment_expense = 20

    total_money_spent = Groceries_expense + Entertainment_expense
    remaining_balance = initial_wallet_balance - total_money_spent

    print(total_money_spent)
    print(remaining_balance)


Problem 9: You are given a dictionary:

student = {
    "name": "Aarav",
    "age": 20,
    "course": "Python"
}


Task:
Write a program to:

Check 
1) if the key "age" exists in the dictionary.

2) If it exists, print its value.

3) Otherwise, print "Key not found".

        student  = {
            "name" : "Array",
            "age" : 20,
            "course" : "Python"
        }

        if "age" in student:
            print("age key is in student and it is", student["age"])
        else:
            print("does not exists")














