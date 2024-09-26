# Clean Code Demo

Open this file in a text editor, highlight the code to be cleaned, and use the below Talon command to see the cleaned code in action.

## Command to Use

`model clean code`

## Description

This command reduces duplication and improves the clarity of the provided code, making it more idiomatic and easier to read, without changing its behavior or functionality.

## Code to Clean

``` python

def print_user_info(user):
    print("Name:", user['name'])
    print("Age:", user['age'])
    print("Email:", user['email'])

def print_admin_info(admin):
    print("Name:", admin['name'])
    print("Age:", admin['age'])
    print("Email:", admin['email'])

```

## Example Output

``` python

def print_user_info(user):
    print_user_details(user)

def print_admin_info(admin):
    print_user_details(admin)

def print_user_details(user):
    print("Name:", user['name'])
    print("Age:", user['age'])
    print("Email:", user['email'])

```
