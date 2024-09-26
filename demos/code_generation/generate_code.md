# Code Generation Demo

Open this file in a text editor, highlight the text describing the process to be coded, and use the below Talon command to see the code generation in action.

## Command to Use

`model generate code`

## Description

This command generates code based on the provided plaintext description of a process. It outputs code in the specified language, without any natural language explanations.

## Text to Generate Code

Create a Python function that takes a list of numbers and returns the sum of all even numbers in the list.

## Example Output

```python
def sum_even_numbers(numbers):
    return sum(num for num in numbers if num % 2 == 0)
```
