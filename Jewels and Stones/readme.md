```py
n = int(input())

for j in range(n):
    
    a,b = input().split()

    count = 0

    for i in b:
    
        if i in a:
        
            count += 1
        
    print(count)
```
