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

### Define a 2d list with some value
```
list = [[2] * 3 for _ in range(2)]
```
result\
```list = [[2, 2 ,2], [2, 2, 2]]```

### Character to ASCI value
```
ord('a')
```
#### ASCI value to Character
```
chr(65)
```
### Make list of characters from string
```
charactersList = list(s)
```
#### To split by something
```
wordList = s.plit(" ") //splitting by space
```
#### To join them back
```
joinedString = "".join(charactersList)
```
### Frequency on numbers in an array
```
frequency = Counter(nums)
```
### all method / Check if all are true in a array
```
all(count % 2 == 0 for count in frequency.values())
```