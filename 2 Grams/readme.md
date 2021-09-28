```py
n = int(input())

s = input()

max = 0

temp = ""

for i in range(n-1):
    
    x = s[i] + s[i+1]
    
    res = [i for i in range(len(s)) if s.startswith(x, i)]
    
    if len(res) > max:
        
        max = len(res)
        
        temp = x
        
print(temp)
```
