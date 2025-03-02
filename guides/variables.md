## Variables in python :

- Declaration of contants 
- Declaration of normal variables
- Scoping of variables
- Commments 

## 1. Declaration of constants:
In python , there is no different way of declaring constants as like javascript . constants can be declared and also can be changed overtime as normal variables . One convention is used to declare constants is to declare it in capital case as
```python
CONSTANT = 3
CONSTANT = 4
print(CONSTANT) # Output ; 4
```

## 2. Declaration of variables :
Variable can be declared as :
```python
variable_name = "Muhammad affan"
```
## 3. Scoping of variables:
Scoping is defined as the range of availability of a variable inside the program.

1. When a variable is declared inside a function, it cannot be accessible outside to that function
```python
name = ""
def example():
    name = "User name"

print(name) # error: name is not defined
```
2. When a variable is declared inside the if statement it's availability is dependent on the condition. Whatever condition is true, it changes the variable according to it .
```python
name
name = ""
if(False):
    name = "Muhammad affan"
elif(False):
    name = ""
else:name = "anonymous"

print(name) # Output : anonymous
```
This is the last condition where name has to be changed to anonymous is true therefore the available value of name is **anonymous**

## 3. Comments :
for single line comments:
```python
# commented statement
```
and for multiline comments use triple quotations as
```python
"""multiline comments"""
```