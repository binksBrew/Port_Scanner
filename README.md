# Port_Scanner

A simple Python-based port scanner that checks for open ports on a target machine. This project demonstrates basic network programming concepts using Python's `socket` module.

## Features

- Scans a range of ports on a target IP address
- Identifies open ports
- Provides a simple and clear output

## Installation

To use this port scanner, you need Python 3 installed on your system. Clone this repository and navigate to the project directory:

```bash
git clone https://github.com/binksBrew/Port_Scanner.git

python3 scanner.py <ip>
(Replace <ip> with the actual IP address you want to scan.)

Example:

python3 scanner.py 192.168.1.1

Output:

--------------------------------------------------
Scanner target: 192.168.1.1
Time started: 2024-07-16 12:34:56.789012
--------------------------------------------------
Port 53 is open
Port 80 is open
