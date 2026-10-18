# shell-log-analyzer

A lightweight Bash script designed to parse and analyze web server log files for automated system monitoring on AWS EC2 instances.

## Features
- Calculates the total number of lines in a log file.
- Detects and counts `404` HTTP error occurrences.
- Provides input validation for specified log files.

## Tech Stack
- **Operating System:** AWS EC2 (Amazon Linux)
- **Scripting:** Bash / Shell Scripting
- **Tools:** `grep`, `wc`, `chmod`
- **Version Control:** Git, GitHub

## Usage Instructions

1. Make the script executable:
   chmod +x log_analyzer.sh

2. Run the script with a log file:
   ./log_analyzer.sh <path_to_log_file>

## Example Output
--- Log Analysis Report ---
Total lines: 4
404 Errors: 2

Project Demo

This video demonstrates the AWS EC2 Shell Log Analyzer running and analyzing log files using Bash scripting on Linux.

Watch Project Demo 🎦
https://drive.google.com/file/d/1n7ikekj3Lf23fcr2CIpkwmpOrmu06sCm/view?usp=drivesdk
