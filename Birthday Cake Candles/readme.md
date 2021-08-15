```py
def birthdayCakeCandles(candles):
    
    n = max(candles)
    count = 0
    
    for i in candles:
        if i == n:
            count+=1
    
    return count
    
if __name__ == '__main__':

    candles_count = int(input().strip())

    candles = list(map(int, input().rstrip().split()))

    result = birthdayCakeCandles(candles)

    fptr.write(str(result) + '\n')

    fptr.close()
```
