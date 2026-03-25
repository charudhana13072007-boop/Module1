
# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
~~~

a = 0 == True


b = False == False

c = True + True


d = False + 9

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
~~~
## Output

a is False
b is True
c: 2
d: 9

## Result

he program demonstrates Boolean Expression Evaluation and Boolean Arithmetic in Python.

Expressions a and b use comparison operators. Since 0 is equivalent to False, the expression 0 == True returns False.

Expressions c and d demonstrate that when booleans are used in arithmetic, True is treated as 1 and False as 0. Thus, 1 + 1 = 2 and 0 + 9 = 9.
