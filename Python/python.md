### To memoize function calls
```
@functools.lru_cache(maxsize=None)
```
Example
```
@functools.lru_cache(maxsize=None)
def findSomething(self, i: int, j: int, s: str, p: str):
    function implementation
```

### To extent a list with n value m times
```
list.extend(n, m)
```
before\
```list = [a, b]```\
after\
```list = [a, b, n, n]```