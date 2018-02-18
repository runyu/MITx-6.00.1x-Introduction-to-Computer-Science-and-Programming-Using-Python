#### Tuples is immutable, just like string

#### Tuples has convenient method of swapping variables
```
(x, y) = (y, x) 'this is legal command in python'
```

Can be used to return more than one value from a function
```
def quotient_and_remainder(x, y):
    q = x//y
    r = x%y
    return (q, r)

(quot, rem) = quotient_and_remainder(4,5)
'Tuple itself is returned as one single construct'
```
#### Slicing in string and tuple are the same use [] rather than ()

#### List is mutable. And List is []

```
total = 0 
    for i in range(len(L)):
        total += L[i]
    print(total) 
```
```
total = 0
    for i in L:
        total += i
    print(total)
    
'cleaner code for iteration
```
