# Project-2
## [16,21,11,8,12,22] -> Merge Sort

### Write all the iterations of the data given above according to the given algorithm 
```
                [16,21,11,8,12,22]
                /                 \
            [16,21,11]         [8,12,22]
            /         \         /     \
         [16,21]     [11]     [8,12]  [22]
         /    \        |      /  \      |
        [16] [21]    [11]    [8] [12]  [22]
          \    /       |      \   /      |
          [16,21]     [11]    [8,12]   [22]
              \      /          \      /
             [11,16,21]         [8,12,22]
                \                /
                [8,11,12,16,21,22]
```

### Write it's Big-O.
#### - O(nlogn)