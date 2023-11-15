```python
"Fizz" * (i % 3 == 0)
```

This expression utilizes the fact that in Python, multiplying a string by an integer results in the repetition of that string. Here's how it works:

- When `i` is divisible by 3 (`i % 3` equals 0), the expression evaluates to `"Fizz" * True`, and since `True` is equivalent to the integer `1`, it effectively becomes `"Fizz" * 1`. This means the string `"Fizz"` is repeated once.

- When `i` is not divisible by 3 (`i % 3` is nonzero), the expression evaluates to `"Fizz" * False`, and since `False` is equivalent to the integer `0`, it becomes `"Fizz" * 0`. In this case, the result is an empty string (`""`).
