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
