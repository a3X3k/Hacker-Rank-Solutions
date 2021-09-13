```py
def pairs(m, arr):
    
    arr = set(arr)
    
    return sum(1 for i in arr if i + m in arr)

n, m = map(int,input().split())

arr = list(map(int,input().split()))

print(pairs(m, arr))
```
