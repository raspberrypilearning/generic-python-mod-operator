The modulo or 'mod' operator divides one number by another and returns the remainder. The symbol of this operator is `%`.

```python
remainder = 5 % 2
print(remainder)

>> 1
```

The calculation `5 / 2` is performed, and the remainder is returned. In this case, 2 goes into 5 twice, with 1 left over as the remainder. Hence, the result is 1.

You can use mod to check whether a number is a multiple of another number. If it is, the remainder will be 0, like in this example:

```python
test_number = 50
if test_number % 5 == 0:
    print("This is a multiple of 5")
```
