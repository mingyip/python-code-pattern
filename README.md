# python-code-pattern

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
