## Numbers in python

- Number and float constructor (int() and float())

## 1. Number and float constructors:
built in **int()** and **float()** functions are used to create a new number or convert an existing from another data type to number 

```python
print(int(True)) # Output : 0
print(int(False))# Output : 1
print(int(None))# Output : error in conversion
print(int([1,2,3])) # Output : error in conversion
print(int({"1":1})) # Output : error in conversion
print(int("1")) # Output : 1
```