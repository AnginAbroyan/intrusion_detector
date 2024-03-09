# Detector of intrusion which sends email as an alert


This Python script monitors the fail2ban log file for banned IP addresses and sends an email notification if any banned IPs are found. It uses the `schedule` library to run the monitoring job periodically.

## Features

- Monitors the fail2ban log file for banned IP addresses.
- Sends an email notification with the list of banned IPs.
- Uses a scheduler to run the monitoring job periodically.

## Requirements

- Python 3.x
- `schedule` library (`pip install schedule`)
- `termcolor` library (`pip install termcolor`)

## Usage

1. Make sure you have Python 3.x installed on your system.
2. Install the required libraries using `pip`:

   ```bash
   pip install schedule termcolor
