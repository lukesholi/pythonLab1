Lab – 1
Title

Study of Basic Data Types, Input Function, Type Function and Type Casting in Python

Objective

To understand basic data types in Python

To study the use of input() function

To understand type() function and its working

To learn the need of type casting in a program

To write a simple program using functions to calculate the area of a rectangle

Theory
1. Basic Data Types in Python

Data types specify the type of data a variable can store. Common basic data types are:

int – stores integer values (e.g., 10, -5)

float – stores decimal values (e.g., 3.14, 2.5)

str – stores string or text values (e.g., "Hello")

bool – stores Boolean values (True or False)

Example:

a = 10
b = 3.5
c = "Python"
d = True

2. Type Function (Implementation)

The type() function is used to find the data type of a variable.

Example:

x = 10
print(type(x))


Output:

<class 'int'>

3. Input Function

The input() function is used to take input from the user.
By default, the input value is stored as string.

Example:

name = input("Enter your name: ")

4. Working of Type Function

The type() function checks the memory type of the variable and returns its class type.

Example:

x = input("Enter a number: ")
print(type(x))


Output:

<class 'str'>


This shows that input values are treated as strings.

5. Need of Type Casting in Program

Type casting is required to convert one data type into another.
Since input() returns string, we must convert it into int or float to perform calculations.

Example:

x = int(input("Enter a number: "))

6. Function Syntax

A function is a block of reusable code.

Syntax:

def function_name(parameters):
    statements
    return value

Program: Area of a Rectangle
Algorithm

Start

Define a function to calculate area

Take length and breadth as input

Convert input values into float

Calculate area = length × breadth

Display the result

Stop

Source Code
def rectangle_area(length, breadth):
    return length * breadth

l = float(input("Enter length: "))
b = float(input("Enter breadth: "))

area = rectangle_area(l, b)
print("Area of rectangle =", area)

Discussion

In this lab, basic Python data types were studied along with input handling and type identification.
The importance of type casting was observed while performing arithmetic operations.
A simple function-based program helped in understanding function syntax and reusability.

Conclusion

This lab helped to understand fundamental Python concepts such as data types, input function, type function, and type casting.
Using functions made the program structured and easy to understand. These concepts are essential for building more complex programs.
