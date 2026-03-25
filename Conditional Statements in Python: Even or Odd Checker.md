# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
~~~
a = int(input("Enter a number: "))

if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
~~~

## Output
Enter a number: 10
EVEN
## Result
The Python program was successfully implemented using conditional statements (if...else) and the modulo operator (%). The program accurately identifies whether a user-provided integer is even or odd by checking if the remainder is zero when divided by 2.

