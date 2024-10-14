# Heaps in python 3
### Make heap from an list
```
heapq.heapify(list) or heapify(list)
```
### To push value in the heap
```
heappush(list, value)
```
### To pop value from the heap
```
heappop(list, value)
```
### To push and pop value together
```
heappushpop(list, value)
```
### To pop minimum then push
```
heapreplace(list, value)
```
### We can use tuple as value, first element will be the priority
```
heappush(list, (priorityValue, someOtherValue))
```
#### Fox max heap we can mulitply values with -1 and use min heap
```
heappush(list, -value)
```