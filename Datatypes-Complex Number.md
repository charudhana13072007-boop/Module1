# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
~~~

a = int(input("Enter the real part: "))


b = int(input("Enter the imaginary part: "))


x = complex(a, b)


print("Complex number:", x)


print("Real part:", x.real)


print("Imaginary part:", x.imag)
~~~
## Output
Enter the real part: 5
Enter the imaginary part: 3
Complex number: (5+3j)
Real part: 5.0
Imaginary part: 3.0

## Result
he program successfully demonstrates how to create and manipulate complex data types in Python.The complex(a, b) constructor builds a number in the form $a + bj$.Even if you input integers, the .real and .imag attributes return floating-point values (e.g., 5.0), which is the standard behavior for the complex class in Python.
