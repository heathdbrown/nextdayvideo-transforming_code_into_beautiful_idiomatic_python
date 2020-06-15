# Transforming Code into Beautiful, Idiomatic Python #

https://www.youtube.com/watch?v=OSGv2VnC0go

Raymond Hettinger

Learn to take better advantage of Python's best features and improve existing code through a series of code transformations, "When you see this, do that instead."

## Takeaways ##
* Probably one of the best Pycon talks I have seen. Even at 7 years old, it is still relevant.


## Examples from video ##
 
### Looping over a collection with indices ###

'stop doing this'
```
colors = ['blue', 'yellow', 'green', 'red']
for i in range(len(colors)):
    print(f"{i}, -->, {colors[i]}")
```

'start doing this'
```
colors = ['blue', 'yellow', 'green', 'red']
for i, color in enumerate(colors):
    print(f"{i}, -->, {color}")
```


https://youtu.be/OSGv2VnC0go
