# Schema Fitting Demo

Open this file in a text editor, highlight the text to be categorized, and use the below Talon command to see the schema fitting in action.

## Command to Use

`model fit schema`

## Description

This command categorizes responses into key-value pairs by inferring the appropriate schema from the provided text. The result is output in a JSON format, unless another format is specified or inferred.

## Text to Fit Schema

Response 1 - The website is down.
Response 2 - Users are experiencing issues with login.
Response 3 - The payment gateway is not working.

## Example Output

```json
{
  "Response 1": "The website is down.",
  "Response 2": "Users are experiencing issues with login.",
  "Response 3": "The payment gateway is not working."
}
```
