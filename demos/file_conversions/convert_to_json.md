# JSON Conversion Demo

Open this file in a text editor, highlight the text to be converted, and use the below Talon command to see the conversion in action.

## Command to Use

`model convert to jason`

## Description

This command converts the provided data into a JSON format, serializing key-value pairs and arrays as needed for proper structure in JSON.

## Text to Convert

User details are as follows:
Full Name: Sarah Connor
User ID: SC2023
Preferences:
- Theme: Dark mode
- Notifications: Enabled for email only
Login History: 5 recent logins

## Example Output

```json
{
  "user_details": {
    "full_name": "Sarah Connor",
    "user_id": "SC2023",
    "preferences": {
      "theme": "Dark mode",
      "notifications": "Enabled for email only"
    },
    "login_history": "5 recent logins"
  }
}
```
