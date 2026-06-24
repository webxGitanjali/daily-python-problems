# daily-python-problems
<br>
# New python problems everyday

<br>

Problem  1: Statement -
<br>
You're given a string s which is a word (no spaces). Write a program to check:
<br>
If the length of the word is even, print "EVEN LENGTH".
<br>
If the length is odd, print "ODD LENGTH".
<br>
Code:

    s = input("Enter a word: ")

    if len(s) % 2 == 0:
        print("EVEN LENGTH")
    else:
        print("ODD LENGTH")

Problem 2: Statement -
<br>
You’re given a string. Write a program to check if the first and last characters of the string are the same.
<br>
If they match, print "MATCH".
<br>
Otherwise, print "NO MATCH".
<br>

Code:
<br>

    word = input("Enter a word: ")

    if word[0] == word[-1]:
        print("MATCH")
    else:
        print("NO MATCH")

Problem 3: Statement -
<br>
Write a program that takes a lowercase word as input and counts how many vowels (a, e, i, o, u) it contains.
<br>
Then print the number of vowels in the word.
<br>

Code:
<br>
    
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
<br>
print the elements of the following list using a loop.
<br>
list - [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
<br>

Code:

    num = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
    index = 0
    while index < len(num):
        print(num[index])
        index += 1

Problem 5: Statement - 
<br>
print the multiplication table of a number n
<br>

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

Problem 10: Declare a variable "temperature" and initialize it with a value of 25.5 (in Celsius) and print it in Celsius and Kelvin (add 273 to the temperature in Celsius).

    temperature = 25.5

    print("Celsius - ",temperature)
    print("Kelvin - ",temperature + 273)

Problem 11: Write a program to find the area and perimeter of square whose side length is 4.5. On the first line, print square's area and on the second line, its perimeter.
Note: Area of a Square = side × side and, Perimeter = 4 x side

    side_of_square = 4.5

    Area_of_square = side_of_square *side_of_square

    Perimeter_of_square = 4 * side_of_square

    print(Area_of_square)
    print(Perimeter_of_square)

Write a program to check whether a number given as user input is positive, negative, or zero.

    n = int(input())

    if n < 0:
        print("Negative")
    elif n == 0:
        print("Zero")
    else:
        print("Positive")

Problem 12: Grades of Student
Write a program to print the grade of a student based on the marks he/she has obtained.

Grading Rules

Grade A → Marks > 90
Grade B → Marks > 70
Grade C → Marks ≥ 40
Grade F → Marks < 40

    Marks = int(input())

    if Marks > 90:
        print('A')
    elif Marks > 70 and Marks <= 90:
        print('B')
    elif Marks >= 40 and Marks <= 70:
        print('C')
    elif Marks < 40:
        print('F')
    else:
        print("Thank you")














