# Project-1

## A. [22,27,16,2,18,6] -> Insertion Sort

### Write all the iterations of the data given above according to the given algorithm 

```
1.  [22,27,16,2,18,6]

```
```
2.  [22,16,27,2,18,6] -> [16,22,27,2,18,6]
``` 

```
3.  [16,22,2,27,18,6] -> [16,2,22,27,18,6] ->  
    [2,16,22,27,18,6]
```
```
4.  [2,16,22,18,27,6] -> [2,16,18,22,27,6] 
```
```
5.  [2,16,18,22,6,27] -> [2,16,18,6,22,27]
    [2,16,6,18,22,27] -> [2,6,16,18,22,27]     
```

### Write it's Big-O.
###### O(n²) 
<br>

### Time Complexity:
#### Average case: When the value is at the middle,
###### O(n²)

#### Worst case: When the value is at the end, 
###### O(n²)

#### Best case: When the value is at the beginning.
###### O(n)
<br>

### Write the time complexity of the value {18} after sorting the set.
##### Average case (O(n²)) <br> <br> <br>

## B. According to Insertion Sort write the first 4 iterations of the set [7,3,5,8,2,9,4,15,6].

```
1.  [3,7,5,8,2,9,4,15,6]
```
```
2.  [3,5,7,8,2,9,4,15,6]
```
```
3.  [3,5,7,8,2,9,4,15,6]
```
```
4.  [2,3,5,7,8,9,4,15,6]
```