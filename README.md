# System Health Monitor (Python)
Simple Python script to monitor CPU, disk usage, and system health

## What it does
Checks system metrics such as:
- CPU usage
- Disk utilization
- System uptime
Outputs a simple health report.

## How to run
### Create a virtual environment
python -m venv myenv
### Activate on Linux/macOS
source myenv/bin/activate
### Activate on Windows (cmd)
myenv\Scripts\activate.bat
### Install dependencies inside the environment
pip install psutil
### Run Script
python system_health_monitor.py
### Deactivate when done
deactivate

