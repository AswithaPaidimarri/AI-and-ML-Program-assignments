# AI-and-ML-Program-assignments
# -*- coding: utf-8 -*-
"""Day3 Assignment.ipynb

Automatically generated by Colaboratory.

Original file is located at
    https://colab.research.google.com/drive/16FrpCiP1xGQ12FwY60QBRDaXlwcwS6Ul

# **AI and ML Program by letsUpgrade**
# **DAY3 ASSIGNMENT**
# **SUBMITTED BY**
# **NAME:-PAIDIMARRI VENKATA SAI ASWITHA**

# **Question1**
# Write a program to subtract two complex numbers in Python.


a=2+3j
b=3+2j
print(a-b)

# **Question2**
# Write a program to find the fourth root of a number.


num=2
res=num**4
print(res)

# **Question3**
# Write a program to swap two numbers in Python with the help of a temporary variable.


x=input()
y=input()
#swapping
temp=x
x=y
y=temp
print("x=",x,"y=",y)

# **Question4**
# Write a program to swap two numbers in Python without using a temporary variable.


x=5
y=3
#swapping with out using temporary variable
x=x+y
y=x-y
x=x-y
print("x=",x,"y=",y)

# **Question5**
# Write a program to convert Fahrenheit to kelvin and celsius both.


f=float(input())
Kelvin = 273.5 + ((f-32.0) * (5.0/9.0))
Celsius=(f-32) * 5/9
print("Kelvin=",Kelvin)
print("Celsius=",Celsius)

# **Question6**
# Write a program to demonstrate all the available data types in Python. Hint: Use type() function.


a=2
b=3.0
c=2.888888888888888
d=10000000000000
e="Letsupgrade"
f="c"
print(type(a))
print(type(b))
print(type(c))
print(type(d))
print(type(e))
print(type(f))
