####Basic Print Syntax
```python3
print(*objects, sep=' ', end='\n', file=sys.stdout, flush=False)
```
##### Example 1
```python3
print("Hello World!")
>>> Hello World!
``` 

##### Example 2
```python3
#Default separator is a space

print("Hello", "World")
>>> Hello World 
```

##### Example 3
```python3
print("Hello", "World", sep='|')
>>> Hello|World
```

##### Example 4
```python3
# Default end parameter is "\n"
x = [1, 2, 3]
for num in x:
    print(num)
>>> 1
    2
    3
```

##### Example 5
```python3
x = [1, 2, 3]
for num in x:
    print(num, end='|')
>>> 1|2|3
```

##### Example 6
```python3
print('Python', 3, 'Rocks', end='*')
print('I love Python')
>>> Python 3 Rocks*I love Python 
```