- The Python range function can be used to produce a sequence of numbers, similar to a tuple.

- For instance, you could use the range function to produce a sequence of the numbers from 0 up to and including 9, like this.

```python
>>> r = range(10)
```

- Just like a normal sequence you could then have a look at the numbers inside the new `r` object.

```python
>>> r[0]
0
>>> r[9]
9
>>> 6 in r
True
>>> 10 in r
False
```

- The range function can take up to three arguments.
- When one argument is provided, the sequence will be from `0` up to the value of the argument.
```python
>>> r = range(10)
>>> list(r)
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
```
- When two arguments are provided, the sequence will be between the first value and the second value.
```python
>>> r = range(5, 10)
>>> list(r)
[5, 6, 7, 8, 9]
```
- When three arguments are provided, the sequence will be between the first and second value, but in steps equal to the third value.
```python
>>> r = range(0, 10, 2)
>>> list(r)
[0, 2, 4, 6, 8]
```
- Negative values can also be supplied for any of the arguments.
```python
>>> r = range(-5, -20, -3)
>>> list(r)
[-5, -8, -11, -14, -17]
```

- As with any sequence in Python, you can use a `for` loop to iterate over the sequence.

```python
for i in range(10):
    print(i)
```

