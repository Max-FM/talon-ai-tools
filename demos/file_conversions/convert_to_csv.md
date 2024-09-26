# CSV Conversion Demo

Open this file in a text editor, highlight the text to be converted, and use the below Talon command to see the conversion in action.

## Command to Use

`model convert to sheet`

## Description

This command converts the provided data into a CSV format, arranging rows and columns in a comma-separated structure suitable for spreadsheets.

## Text to Convert

Event attendance data:
- Alice, checked-in at 10:00 AM
- Bob, checked-in at 10:05 AM
- Charlie, no check-in recorded
- Dana, checked-in at 10:15 AM

## Example Output

```
Name, Status, Check-in Time
Alice, Checked-in, 10:00 AM
Bob, Checked-in, 10:05 AM
Charlie, No check-in,
Dana, Checked-in, 10:15 AM
```
