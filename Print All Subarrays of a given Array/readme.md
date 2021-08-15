```py
n = int(input())
    
for i in range(n):
        
    m = int(input())
    
    arr = list(map(int, input().split()))
          
    for a in range(len(arr)):
            
        index = a
            
        while(index < len(arr)):
            
            for b in range(a,index+1):
                
                print(arr[b], end = " ")
            
            print()
                
            index += 1
```
