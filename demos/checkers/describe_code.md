# Code Description Demo

Open this file in a text editor, highlight the code to be described, and use the below Talon command to see the explanation in action.

## Command to Use

`model describe code`

## Description

This command explains what the provided code does at a high level in natural language, avoiding specifics of the syntax and focusing on the overall functionality.

## Code to Describe

```python

def process_data(data):
    filtered_data = [d for d in data if d['status'] == 'active']
    sorted_data = sorted(filtered_data, key=lambda x: x['date'])
    return sorted_data

```

## Example Output

The code defines a function that takes a collection of data as input. It filters this data to include only the items that have an 'active' status. Then, it sorts the filtered data based on a date attribute. Finally, it returns the sorted list of active items.
