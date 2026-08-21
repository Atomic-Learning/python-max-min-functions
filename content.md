The built-in function `max()`{.python} and `min()`{.python} returns the largest and smallest of the arguments passed to them.

# `max()`{.python} and `min()`{.python} on Scalars

>

When passed a set of individual numerical arguments, `max()`{.python} returns the largest and `min()`{.python} returns the smallest.

```py-cell
print(max(1, -2, 3))
print(min(1, -2, 3))
```

# `max()`{.python} and `min()`{.python} on Iterables

When passed an iterable (such as a list) of numerical values , `max()`{.python} returns the largest item and `min()`{.python} returns the smallest item.

```py-cell
values = [1, 2, -3, 4]
print(max(values))
print(min(values))
```
