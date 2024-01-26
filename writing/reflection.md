# Data Types

## Aidan Dyga

## Program Output

### What is the output from running the following commands?

- `python demonstrate-variable-limitations.py`

```python
The value of a feasible number is 115792089237316195423570985008687907853269984665640564039457584007913129639936

The value of another feasible number is 179769313486231590772930519078902473361797697894230657273430081157732675805500963132708477322407536021120113879871393357658789768814416622492847430639474124377767893424865485276302219601246094119453082952085005768838150682342462881473913110540827237163350510684586298239947245938479716304835356329624224137216
```

- `python compare-variables.py`

```python
1.0 is not the same as 1.1
1.0 is the same as 1.0
.33333 + .33333 + .33333 is not equal to 1
.33333333333 + .33333333333 + .3333333333 is not equal to 1
The value of 1/3 is 0.3333333333333333
0.3333333333333333 + 0.3333333333333333 + 0.3333333333333333 is equal to 1
1/3 + 1/3 + 1/3 is equal 1
```

## Program Questions

### Why is it not feasible to perform the computation `2**2**100`?

It is not feasible to perform the computation `2**2**100` because it results in a number so large that it would take python a really really really long time for it to compute. Because this number would be astronomically large, it is not feasible to perform the computation.

### What is the value of `1/3` according to the Python language? Why?

According to the python programming language, the value of `1/3` is 0.3333333333333333. This is because 0.3333333333333333 is the decimal representation of 1/3 according to python. The computer has limited approximation, thus resulting in this decimal value.

### Why is the value of `.33333 + .33333 + .33333 == 1` equal to `False`?

The value of `.33333 + .33333 + .33333 == 1` is equal to False because the decimal places of the values added together is not close enough for python to recognize it as one. Because of the limited precision of numbers that python can compute, this value results as being equal to False. Overall, I would be interested in exploring more about this topic in the future in order to hopefully become more familiar with python and floating point numbers.
