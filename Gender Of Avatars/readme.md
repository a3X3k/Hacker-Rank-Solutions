```py
n = input()

gender = 0

for i in n:
    
    if n.count(i) == 1:
        
        gender += 1
        
if gender % 2 == 0:
    
    print("CHAT WITH HER!")

else:
    
    print("IGNORE HIM!")
```
