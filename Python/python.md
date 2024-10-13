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