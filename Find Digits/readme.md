```py
n = int(input())

for i in range(n):
    
    m = input()
    
    count = 0
    
    for i in m:
        if i != "0" and int(m)%int(i) == 0:
            count += 1
        
    print(count)
```
