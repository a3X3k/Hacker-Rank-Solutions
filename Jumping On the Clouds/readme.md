```py
def jumpingOnClouds(c):
    
    count=0
    
    n = len(c)-1
    
    i=0
    
    while(i<n):
        
        if i+2 <= n and c[i+2] == 0:
            
            i += 2
            count += 1
        
        elif i+1 <= n and c[i+1] == 0:
            
            i += 1
            count += 1
        
        else:
            
            print(count)
    
    print(count)
    
    
if __name__ == '__main__':

    n = int(input().strip())

    c = list(map(int, input().rstrip().split()))

    jumpingOnClouds(c)
```
