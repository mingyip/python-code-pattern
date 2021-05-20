# python-code-pattern


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
