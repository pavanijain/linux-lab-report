#!/bin/bash


sleep 60 &
jobs

pid=$(jobs -p)
echo "PID of job:$pid"

kill $pid
echo "job killed"

