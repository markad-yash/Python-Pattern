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
num = 4
for i in range(num):
    for j in range(i):
        print(end=' ')
    for j in range(num-i):
        print('*',end= ' ')
    print()
```
Output:
```
* * * * 
 * * * 
  * *
   *
```

7.
```python
n=4
for row in range(n):
    for col in range(n):
        if row==col:
            print('*',end=' ')
        else:
            print(' ',end=' ')
    print()
```
Output:
```
*       
  *     
    *
      *
```

8.
```python
n = 4
for i in range(n):
    for j in range(n-i-1):
        print(' ',end=' ')
    for j in range(1):
        print('*',end=' ')
    print()
```
Output:
```
      * 
    * 
  *
*
```


9.



10.
```python
n= 7
for row in range(n):
    for col in range(n-2):
        if (col ==0 or col==4) or ((row==0 or row == 3) and (col>0 and col<n-3)):
            print('*',end=' ')
        else:
            print(' ',end=' ')
    print()

```
Output:
```
* * * * * 
*       * 
*       *
* * * * *
*       *
*       *
*       *
```


11.
```python
n = 7
for i in range(n):
    for j in range(n-2):
        if i == 0 or j ==0 or j ==(n-3) or i == (n//2) or i == n-1 or (j!=n-3 and i ==0):
            print('*',end=' ')
        else:
            print(' ',end=' ')
    print()
```
Output:
```
* * * * * 
*       * 
*       *
* * * * *
*       *
*       *
* * * * *
```

12.
```python
n = 6
for i in range(n):
    for j in range(n-1):
        if i==0 or j==(n-2) or i == (n-1):
            print('*',end=' ')
    print()

```
Output:
```
* * * * * 
* 
*
*
*
* * * * *
```
```python
n = 5
for i in range(n):
    for j in range(n):
        if i==0 or j==0 or i == (n-1) or j ==(n-1):
            print('*',end=' ')
        else:
            print(' ',end=' ')
    print()
        
```
Output:
```
* * * * * 
*       * 
*       *
*       *
* * * * *
```
13.
```python
n = 7
for i in range(n):
    for j in range(n-1):
        if i==0 or i==n//2 or j ==0 or i == n-1:
            print('*',end=' ')
    print()
```
Output:
```
* * * * * * 
* 
*
* * * * * *
*
*
* * * * * *
```

13.
```python
n = 7
for i in range(n):
    for j in range(n-1):
        if i==0 or i==n//2 or j ==0:
            print('*',end=' ')
    print()
```
Output:
```
* * * * * * 
* 
*
* * * * * *
*
*
* 
```
15.
```python
n = 9
for i in range(n):
    for j in range(n-1):
        if i==0 or j ==0 or i==(n-1) or (i ==n//2 and j >2) or (j ==n-2 and i>=n//2) :
            print('*',end=' ')
        else:
            print(' ',end=' ')
    print()
```
Output:
```
* * * * * * * * 
*
*
*
*     * * * * *
*             *
*             *
*             *
* * * * * * * *
```
15.
```python

n = 7
for i in range(n):
    for j in range(n-1):
        if i ==n//2 or j ==0 or j ==n-2:
            print('*',end=' ')
        else:
            print(' ',end= ' ')
    print()

```
Output:
```
*         * 
*         * 
*         *
* * * * * *
*         *
*         *
*         *
```
15.
```python
n = 8 
for i in range(n):
    for j in range(n-1):
        if i==0 or i ==n-1 or j ==(n-2)//2:
            print('*',end=' ')
        else:
            print(' ',end=' ')
    print()
```
Output:
```
* * * * * * * 
      *       
      *
      *
      *
      *
      *
* * * * * * *
```
15.
```python
n = 7
for i in range(n):
    for j in range(n-1):
        if i ==0 or j ==n//2 or (j==0 and i > (n-3)) or (i==n-1 and j<=n//2) :
            print('*',end=' ')
        else:
            print(' ',end=' ')
    print()

```
Output:
```
* * * * * * 
      *     
      *
      *
      *
*     *
* * * *
```
15.
```python
n =9
for i in range(n):
    for j in range(n-1):
        if j==0 or i == n-1:
           print('*',end=' ')
    print()

```
Output:
```
* 
* 
*
*
*
*
*
*
* * * * * * * *
```
15.
```python
n = 7
for i in range(n):
    for j in range(n-1):
        if j ==0 or (i ==0 and j <=(n-3)) or (j ==(n-2) and i < n//2) or i ==n//2:    
            print('*',end=' ')
        else:
            print(' ',end = ' ')
    print()

```
Output:
```
* * * * * * 
*         * 
*         *
* * * * * *
*
*
*
```
15.
```python
n = 7
for i in range(n):
    for j in range(n-1):
        if i ==0 or j ==n-2 or i == n//2 or (i<=n//2 and j ==0):    
            print('*',end=' ')
        else:
            print(' ',end = ' ')
    print()
```
Output:
```
* * * * * * 
*         * 
*         *
* * * * * *
          *
          *
          *
```
15.
```python
n = 7
for i in range(n):
    for j in range(n-1):
        if i ==0 or i ==n//2 or i ==n-1 or (j ==0 and i <n//2) or (j ==n-2 and i >n//2):    
            print('*',end=' ')
        else:
            print(' ',end = ' ')
    print()


```
Output:
```
* * * * * * 
*
*
* * * * * *
          *
          *
* * * * * *
```
15.
```python

```
Output:
```

```
15.
```python

n = 7
for i in range(n):
    for j in range(n-1):
        if i==j or (i+j ==n-2):   
            print('*',end=' ')
        else:
            print(' ',end=' ')
    print()
```
Output:
```
*         * 
  *     *   
    * *
    * *
  *     *
*         *
```
15.
```python
n = 7
for i in range(n):
    for j in range(n-1):
        if i==0 or i==n-1 or (i+j ==n-1):   
            print('*',end=' ')
        else:
            print(' ',end=' ')
    print()

```
Output:
```
* * * * * * 
          * 
        *
      *
    *
  *
* * * * * *
```
16.
```python
n = 7
for i in range(n):
    for j in range(i):
        print(' ',end=' ')
    for j in range(n):
        print('*',end=' ')
    print()

```
Output:
```
* * * * * * * 
  * * * * * * * 
    * * * * * * *
      * * * * * * *
        * * * * * * *
          * * * * * * *
            * * * * * * *
 ```
   
   
17.
```python
n = 7
for i in range(n):
    for j in range(n-i):
        print(' ',end=' ')
    for j in range(n):
        print('*',end=' ')
    print()
```
Output:
```
              * * * * * * * 
            * * * * * * * 
          * * * * * * *
        * * * * * * *
      * * * * * * *
    * * * * * * *
  * * * * * * *
```
