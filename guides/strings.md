## Manipulating Strings:

- String constructor (str())
- String Concatenation ("+" operator )
- String length (len() function)
- Split strings (split())
- Finding index of a character (index())
- Search for a specific word (find())
- Replacing characters (replace())
- Transformation Of Cases (lower(), upper(), title())
- Counting Occurences (count)
- Removing Spaces (rstrip() and lstrip())

## 1.  String Constructor :
Pass characters to built in str() function to make a string. You can convert data from any form to string as 
```python
print(str(False))
# Output : False
```
this will convert False into a printable string

## 2. String Concatenation :
Use **+** operator to concatenate strings

```python
print("Python"+" "+"is"," ","beautiful")
# Output : Python is beautiful
```
## 3. String length :
You can find length of a string using build in **len()** function as follows:

```python
string = "Hello world"
print(len(string))
# Output: 11
```
## 4. Split strings :
**split()** is a string  method in python used for spliting strings into list (arrays) 
``` python 
string = "Hello world";
print(string.split(" "))
# Output : ['Hello', 'world']
```
or either you can also split a string into list of characters (array of characters) as 

```python
string = "Hello world";
print(list(string))
# Output : ['H', 'e', 'l', 'l', 'o', ' ', 'w', 'o', 'r', 'l', 'd']
```
you can iterate over an array using iteration techniques

## 5. Finding index of a character :
For finding index of a character. you can use builtin **index()** function . It takes an argument string containing character whose index is required.

```python
string = "Hello world";
print(string.index("l"))
# Output: 2 
```
## 6. Search for a word in string :
You can search for a word in string using **find()** method . It returns starting index of that word from where the word starts
```python
string = "Hello world pakistan"
print(string.find("pakistan"))
# Output : 12
```
## 7. Replacing a character in string :
You can replace character in string using **replace()** method as .

```python
string = "Hello world"
print(string.replace("e", "A"))
# Output : HAllo world
```
 
## 8. Transformation of cases :
You can use string methods **lower()** , **upper()** and **title()** to transform strings into lowercase , uppercase and titlecase.

``` python
string = "hello world"
print(string.upper()) # converts into uppercase 
print(string.lower()) # converts into lowercase
print(string.title()) # convets into titlecase
# Output: HELLO WORLD   hello world Hello World
```

## Counting Occurences:
You can also count how many times a word is repeated in string by using **count()** method in string

``` python
string = "Hello world hello World"
print(string.count("World"))
```
## Removing spaces:
There are three string methods for removing spaces in python from a string
- rstrip()  removes spaces from end  
- lstrip()  removes spaces from start 
- strip()   removes from both start and ends 

```python
string = "            Hello world hello World           "
print(string.rstrip()) # removes spaces from end 
print(string.lstrip()) # removes spaces from start
print(string.strip()) # removes from both sides
print(string.replace(" ", "")) # removes all spaces 
```
## Practice Questions:
1. **Find out wheather a site is secured or not**
``` python
# Find out wheather a site is secured or not
url = "https://nostarch.com"

arr = url.split(":");
protocol = arr[0]

if(protocol == "https"):
    print("Secured")
else: print("unsecured")
# Output : Secured
```
2. **Convert a string to uppercase and lowercase :**
``` python
string = "hello world"
print(string.upper())
print(string.lower())
print(string.title())
# Output: HELLO WORLD   hello world Hello World
```

3. **Find the length of string :**
```python
string = "hello world";
print(len(string))
# Output : 11
```
4. **Remove spaces from middle of string:**

```python 
string = "          jhjd fjhgjdf gdhg jfdhjkg hjfk gjkfdgjfdjghfjghf                  ";
print("Original string :", string)
print("New string : ",string.replace(" ",""))
# Output : jhjdfjhgjdfgdhgjfdhjkghjfkgjkfdgjfdjghfjghf
```
5. **Replace a word in string :**

```python
string = "I love javascript";
print(string.replace("javascript", "Python"))
# Output : I love Python
```
6. **Check if a string starts and ends with required words :**

```python
string = "Python is my favourite language";
print(string.startswith("Python"));
print(string.endswith("Language"))
# Output : True False
```

7. **Find the index of the first occurrence of a word in a string :**
```python
string = "Learn Python, Love Python"
print(string.find("Python"))
# Output : 6
```
8. **Count the number of times a word appears in a string :**
```python
string = "I love python python"
print(string.count("Python"))
# Output: 0
```
9. **Check if a string contains only contains digits :**
```python
string = '12345';
print(string.isdigit())
# Output : True
```
10. **Check if a string contains only alphabets :**

```python
string = "Python 3878937"
print(string.isalpha())
# Output : "False
```
11. **Check if the string is a python identifier (reserved word) :**
```python
string = "def"
print(string.isidentifier())
# Output : True
```
12. **Join each character of array into string:**
```python
string = ["Python", "is", "awesome"]
print(" ".join(string)) 
# Output : Python is awesome
```
13. 