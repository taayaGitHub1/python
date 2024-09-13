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

python first compiles and interprets it line by line.

function can be declared like in c but it is not standard practice, so the function are defined and made before calling it.
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

for array it can have homogeneous data type. Eg:
its = ["apple", "banana", "cherry",67]
for x in fruits:
  print(x) 

Output
apple 
banana 
cherry 
67

for printing var inside string curly brackets is used{}
fruits = ["apple", "banana", "cherry",67]
for x in fruits:
  print(f"i like {x}") 

-to use iteration in for loop: range is used.
Eg: range(1,10)
starting point=1
ending point=10-1

*Note: Python is case sensitive

-get the data type of var:
num=["12345"]u
for  a in num:
    j=len(a)
    print(type(j))

text inside docstring can be viewed when imported when the mouse is hovered in the function name. to insert docstring triple double quote """ """ or triple single quote is used.

ctrl d: similar selection


__init__.py constructor dundor method inclusion make module , default in PyCharm
, in vscode need to make file by hand.

if __name__== '__main__'  makes script in python, dunder method, magic method

 day Y
-while true is only valid in python there is no thing such as while false here.
-to use do while loop in python we use while condition where the first must be set to be true so it can go inside the loop at least once.
-using same syntax as c in python for do while is not quite common and standardized. 
- snake case : using _ underscore to name making name long like snake.  EG:newton_raphson
- camel case: first word 1st letter small , 2nd word 1st letter capital.EG:newtonRaphson
- rounding off or fixing floating number: 
	method1:round(num,5)[rounds num variable to 5 digit]
	method2:num:.5f
- choice
- To use string we use import 
	stringstring.ascii_lowercase
	'abcdefghijklmnopqrstuvwxyz'
	string.ascii_uppercase
	'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
	string.digits
	'0123456789'
	
-pypi.org has all package.
- ctrl+K+ctrl+O: minimize function and to open again ctrl+k+ctrl+J
- ctrl+J : terminal opens
vps server, cloud server, solutizon architech
-panda is a framework/library of python where on the basis of row and colums the data are kept.
- ctrl+r= search bar
- integer caching where there is a block which has -5 to 256 data and when a variable is declared the variable directly point to the corresponding value in the memory.
