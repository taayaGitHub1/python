This file will contain everything that I learned at a month session of python language.

Day-C
-Tab contains 4 spaces.
-For function creation def key word is used.
 Eg:def gradecalc(mark):
   ...
   ...
   ...

Day-E
-Docstring: String literals used to document code i.e. using triple single quotes ''' ''' or triple double quotes""" """.
-Curly braces are not used for blocking code instead indentation is used for creating program blocks and flow control.
- Has Implicit Casting/Automatic Type conversion in Python.
- Input syntax:
  var= data_type(input("..."))
  
Day-F
-python first compiles and interprets it line by line.
-function can be declared like in c but it is not standard practice, so the function i defined and made before calling it.
Eg:
def even(number):  # Placeholder function
    pass  # This will be replaced with the actual function definition later

number = int(input("Enter the number to check: "))
even(number)  # Call to the function

# Detailed function definition
def even(number):
    if (number % 2) == 0:
        print("even")
    else:
        print("not even")
-for array it can have homogeneous data type. Eg:
its = ["apple", "banana", "cherry",67]
for x in fruits:
  print(x) 

"Output"
apple 
banana 
cherry 
67

-for printing var inside string curly brackets is used{}
fruits = ["apple", "banana", "cherry",67]
for x in fruits:
  print(f"i like {x}") 
  
-to use iteration in for loop: range is used.
Eg: range(1,10)
starting point=1
ending point=10-1

-Note: Python is case sensitive
-get the data type of var:
num=["12345"]
for  a in num:
    j=len(a)
    print(type(j))


