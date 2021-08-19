```py
amount, balance = list(input().split())

if int(amount) <= int(float(balance)) and int(amount) % 5 == 0:
    
    print('%.2f' % (int(float(balance)) - int(amount) - 0.50))
    
else:
    
    print('%.2f' % int(float(balance)))
```
