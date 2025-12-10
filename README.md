# Happy Numbers
This is a python project that determines whether a number is happy by repeatedly summing the squares of its digits until it reaches 1 or enters a cycle.

For example, 19 is a happy number. Here's why:

- 1² + 9² = 82
- 8² + 2² = 68
- 6² + 8² = 100
- 1² + 0² + 0² = 1

As you can see, we eventually reached 1, which makes 19 a "happy" number. This project involves creating a program that can accurately determine whether any given positive integer is a happy number or not.

## Instructions
1. `is_happy(n: int) -> bool`: Implements the logic to determine if a number is happy. It uses a set to track previously seen numbers to detect cycles. If it reaches 1, it returns True; if it encounters a number it has seen before, it returns False.
2. The main block includes assertions to test the function with known happy and unhappy numbers, ensuring that the implementation is correct.
3. To run the program, simply execute the `run.py` file, and it will validate the function against the provided test cases.

## Example Usage
```python
if __name__ == "__main__":
    assert is_happy(19) is True
    assert is_happy(45) is False
    assert is_happy(7) is True
    assert is_happy(4) is False
```
This will confirm that the function correctly identifies happy and unhappy numbers.



