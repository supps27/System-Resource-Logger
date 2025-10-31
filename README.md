# System-logger
Python script for continuous CPU, memory, and disk utilization logging with timestamped JSON output — ideal for performance analysis and system diagnostics.


# 🖥️ System Resource Logger

A simple Python-based logger that records real-time system resource usage — CPU, memory, and disk utilization — and stores them as JSON logs for later analysis.

---

## ⚙️ Features
- Logs **CPU, Memory, and Disk usage** every few seconds  
- Saves data with **timestamps** in a JSON file  
- Easily extendable for automation, alerts, or visualization  
- Lightweight and dependency-free (only `psutil` required)

---

## 🧠 How It Works
The script continuously:
1. Fetches system metrics using the `psutil` library  
2. Creates a JSON entry with timestamp and usage data  
3. Appends it to a log file (`Cpu log data.json`) every 5 seconds  

You can later parse this file for trend analysis or visualization.

---

## 🚀 Getting Started

### 1. Clone this repo
```bash
git clone https://github.com/supps-27/System-Resource-Logger.git
cd System-Resource-Logger

