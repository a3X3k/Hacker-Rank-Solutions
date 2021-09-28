```py
n = int(input())

arr = list(map(int,input().split()))

temp = []

s = 0

for i in arr:
    
    if i not in temp:
        
        x = arr.count(i)
        
        x = x//2
        
        s += x
        
        temp.append(i)
        
print(s)
```
