# Boolean Algebra Short-Circuiting in Python

Short-circuiting in Python, also known as lazy evaluation, is a feature of logical operators (`and`, `or`, `not`), allowing further evaluation to be skipped as soon as the outcome is determined.

This behavior is efficient and is used frequently in Python to optimize code. For example:

### Examples:
- **With `and`:** If the first condition evaluates to `False`, Python does not evaluate the second condition, because the result of the `and` operation will still be `False`.
- **With `or`:** If the first condition evaluates to `True`, Python skips evaluating the second condition since the result of `or` must already be `True`.

```python
x = 10
y = 0

# Short-circuiting with `and`
if y != 0 and x/y > 1:
    print("Condition met")
else:
    print("Short-circuiting occurred")

# Short-circuiting with `or`
result = y != 0 or x/y > 1
print("Evaluation avoided unnecessary division:", result)
```

### Key Use Cases:
- Avoiding unnecessary computation  
- Ensuring safe evaluation of conditions (e.g., avoiding division by zero)
- Writing cleaner and more efficient code

For a detailed explanation, visit the article below:

**[Boolean Algebra Short-Circuiting in Python - Medium](https://medium.com/@anikasadia2723/boolean-algebra-short-circuiting-in-python-9963c6b20201)**

---

Feel free to dive deeper into the article by reading my comprehensive guide linked above.
