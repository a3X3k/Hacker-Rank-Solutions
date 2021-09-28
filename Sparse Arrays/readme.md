```py
n = int(input())

a = []

for i in range(n):
    
    a.append(input())
    
m = int(input())

b = []

for i in range(m):
    
    b.append(input())

for i in b:
    
    x = a.count(i)
    
    print(x)
```
