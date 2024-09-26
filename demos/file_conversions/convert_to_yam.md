# YAML Conversion Demo

Open this file in a text editor, highlight the text to be converted, and use the below Talon command to see the conversion in action.

## Command to Use

`model convert to yam`

## Description

This command converts the provided data into YAML format, structuring key-value pairs in the human-readable YAML syntax commonly used for configuration files.

## Text to Convert

Settings for this project:
Name of project: Alpha DevOps
Environment: Staging
Servers: 3 total
Main Database: Postgres 13
Fallback Database: MongoDB 4.4
Scheduled backups: Daily at midnight

## Example Output

```yaml
settings:
  project_name: Alpha DevOps
  environment: Staging
  servers:
    total: 3
  databases:
    main: Postgres 13
    fallback: MongoDB 4.4
  scheduled_backups:
    frequency: Daily
    time: midnight
```
