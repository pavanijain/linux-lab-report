#!/bin/bash

# File: monitor_cpu.sh

LOGFILE="cpu_usage.log"

echo "Monitoring top 5 CPU consuming processes..."
echo "Press Ctrl+C to stop."

while true; do
    echo "------ $(date) ------" >> "$LOGFILE"
    ps -eo pid,comm,%cpu --sort=-%cpu | head -6 >> "$LOGFILE"
    echo "" >> "$LOGFILE"
    sleep 10
done

