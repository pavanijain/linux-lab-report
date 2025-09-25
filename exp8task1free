#!/bin/bash

logfile="memory_log.txt"
echo "Logging memory usage to $logfile (press Ctrl+C to stop)"

while true
do
    free -m >> "$logfile"
    echo "-----" >> "$logfile"
    sleep 5
done

