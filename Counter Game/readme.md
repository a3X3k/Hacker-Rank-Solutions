```py
def Is_Power(n):

    if n == 1:
        
        return True
     
    elif n%2 != 0 or n == 0:
        
        return False

    return Is_Power(n/2)


def Find_Power(n):
 
    while (n & n - 1):
    
        n = n & n - 1
 
    return n


def Counter_Game(n):
    
    i = 0
    
    while(n > 1):
        
        if Is_Power(n):  
            
            n = n/2
        
        else:
            
            n = n - Find_Power(n)
            
        i += 1
    
    if i%2 != 0:
        
        return "Louise"
    
    else:
        
        return "Richard"
    

if __name__ == '__main__':

    t = int(input().strip())

    for i in range(t):
        
        n = int(input().strip())

        print(Counter_Game(n))
```
