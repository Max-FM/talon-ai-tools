# Syntax Fixing Demo

Open this file in a text editor, highlight the code block to be fixed, and use the below Talon command to see the fixes in action.

## Command to Use

`model fix syntax`

## Code to Fix

```python

def calulate_sum num1 num2)
total = num1 + num2
  print "The sum is: " total
  return total
 for i in range(10
print i
 if i % 2 == 0
print "Even number: ", i
   else "Odd number: ", i

```

## Example output

```python

def calculate_sum(num1, num2):
    total = num1 + num2
    print("The sum is:", total)
    return total

for i in range(10):
    print(i)
    if i % 2 == 0:
        print("Even number:", i)
    else:
        print("Odd number:", i)

```
