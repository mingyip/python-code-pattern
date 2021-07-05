# python-code-pattern

## array

### sum

```python
sum([1, 2, 3, 4]) # 10
sum([1, 2, 3, 4], 5) # 15
# sum([[1,2],[3,4]]) # unsupported operand type(s) for +: 'int' and 'list'
sum([[1,2],[3,4]], []) # [1, 2, 3, 4]
sum([[1,2],[3,4]], [0]) # [0, 1, 2, 3, 4]
```


## String
```
s = 'geeksforgeeks'
print(s.islower())
print(s.lower())
print(s.isupper())
print(s.upper())
```

## queue

### Use array
```
queue = []
queue.append('a')
str = queue.pop(0)
```

### Use collections.deque
```
from collections import deque
q = deque()
q.append('a')
q.popleft()
```
