# Shell Script Generation Demo

Open this file in a text editor, highlight the text to be converted to a shell script, and use the below Talon command to see the shell script in action.

## Commands to Use

`model shell` or `model shell <describe action>`

## Description

This command generates a shell script that performs the requested actions, outputting only the necessary commands without comments or explanations. By default, it generates bash scripts unless otherwise specified. You can also use this command directly in the terminal by saying `model shell` followed by describing the action you'd like to perform, e.g. `model shell list all files`. The command will generate the corresponding shell command, allowing you to review and confirm it before copying or pasting it into your terminal. It will not be executed automatically.

## Text to Convert

Create a shell script that backs up a directory called "project_files" to a remote server, compresses it, and logs the operation.

## Example Output

```bash
#!/bin/bash
tar -czf project_files_backup_$(date +%Y%m%d).tar.gz project_files && scp project_files_backup_$(date +%Y%m%d).tar.gz user@remote_server:/path/to/backup/ && echo "Backup completed on $(date)" >> backup_log.txt
```
