# Python-Pattern
we will discuss about python code for pattern 


1. Triangle
```python
for i in range(6):
    for j in range(i):
        print("*",end=" ")
    print()
```
or
```python
for i in range(6):
    print(i*'* ')
```
Output:
```
* 
* *
* * *
* * * *
* * * * *
```
2. Square 
```python
for row in range(5):
    for column in range(5):
        print("*",end=" ")
    print()
```
Output:
```
* * * * * 
* * * * * 
* * * * *
* * * * *
* * * * *
```
3.
```python
for i in range(5):
    for j in range(5-i):
        print("*",end=' ')
    print()
```
or
```python
for i in range(5,0,-1):
    print(i*'* ')
```
```python
for i in range(5):
    print((5-i)*'* ')
```
Output:
```
* * * * * 
* * * * 
* * *
* *
*
```

4.
```python
a = 1
for i in range(1,4):
    for j in range(1,a+1):
        print('*',end=' ')
    a = a+2
    print()

```
Output:
```
* 
* * * 
* * * * *
```


5.
```python
num=5
for i in range(num):
    for j in range(num-i-1):
        print(end= ' ')
    for j in range(i+1):
        print('*',end=" ")
    print()


```
Output:
```
   * 
  * * 
 * * *
* * * *
```

6.
```python

```
Output:
```

```

7.
```python

```
Output:
```

```

8.
```python

```
Output:
```

```


9.
```python

```
Output:
```

```


10.
```python

```
Output:
```

```


11.
```python

```
Output:
```

```

12.
```python

```
Output:
```

```
