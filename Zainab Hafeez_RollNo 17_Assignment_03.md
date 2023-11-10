### Assignment-03 (Strings)
- Change the notebook name with your name and Roll Number.
- Try this as your own, no chatgpt (it's for your learning)
- after completing the assignment, submit this book on google class room.

Create a string variable with your name and print it.



```python
My_Name= "Zainab Hafeez"
print (My_Name)
```

    Zainab Hafeez
    

Define a multiline string that includes line breaks and print it.



```python
string = '''
I am Zainab and currently pursuing my MPhil in GIS and RS.
I think Python is much easier than any other programming language.
I hope I will do much better than expected in this subject.
'''
print(string)
```

    
    I am Zainab and currently pursuing my MPhil in GIS and RS.
    I think Python is much easier than any other programming language.
    I hope I will do much better than expected in this subject.
    
    

Access the first character of a string.



```python
string = "GIS"
first_character = string[0]
print(first_character)
```

    G
    

Access the last character of a string.



```python
string = "GIS"
last_character = string[-1]
print(last_character)
```

    S
    

Access the second to the fifth character of a string.


```python
string = "EasyPython"
character = string[1:5]
print(character)
```

    asyP
    

Attempt to change a character within an existing string and explain the result.



```python
string = "Python is very easy"
new_string = string[:10] + 's' + string[14:]
print(new_string)
```

    Python is s easy
    


Slice a string to obtain the first 3 characters.



```python
string = "Python"
first_three_characters = string[:3]
print(first_three_characters)

```

    Pyt
    

Slice a string to obtain the last 4 characters.



```python
string ="Python"
last_four_characters = string[-4:]
print(last_four_characters)
```

    thon
    

Slice a string to get every second character.



```python
string = "Easy_Python"
every_second_character = string[::2]
print(every_second_character)
```

    Es_yhn
    

Reverse a string using slicing.


```python
string = "Easy_Python"
reversed_string = string[::-1]
print(reversed_string)

```

    nohtyP_ysaE
    

Create two string variables and concatenate them.




```python
string1 = "Easy"
string2 = "Python"
concatenated_string = string1 + string2
print(concatenated_string)
```

    EasyPython
    

Concatenate a string with a number (convert the number to a string first).


```python
string = "The number is: "
number = 17
result_string = string + str(number)
print(result_string)
```

    The number is: 17
    

Generate a string that repeats "abc" 10 times.




```python
repeated_str="abc" * 10
print(repeated_str)
```

    abcabcabcabcabcabcabcabcabcabc
    

Create a string containing a repeating pattern of your choice.


```python
repeated_str="zainab" * 4
print(repeated_str)
```

    zainabzainabzainabzainab
    

Convert a string to lowercase using the lower() method.



```python
string = "PYTHON"
lowercase_string =string.lower()
print(lowercase_string)
```

    python
    


Convert a string to uppercase using the upper() method.



```python
string = "Python"
uppercase_string =string.upper()
print(uppercase_string)
```

    PYTHON
    

Remove leading and trailing whitespace from a string using the strip() method.



```python
string = "Python is a programming language"
stripped_string = string.strip()
print(stripped_string)
```

    Python is a programming language
    

Check if a string starts with a specific prefix using the startswith() method.


### 1st Condition


```python
string = "Easy Python"
prefix = "Easy"
start = string.startswith(prefix)
print(start)
```

    True
    

### 2nd Condition


```python
string = "Easy Python"
prefix = "Python"
start = string.startswith(prefix)
print(start)
```

    False
    

Split a string into a list of words using the split() method.



```python
string = "Python is very easy"
split_string = string.split()
print(split_string)
```

    ['Python', 'is', 'very', 'easy']
    

Join a list of words into a single string using the join() method.


```python
words = ["Python" , "is" , "very" , "easy"]
join_string = " ".join(words)
print(join_string)
```

    Python is very easy
    
