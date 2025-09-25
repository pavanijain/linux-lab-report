#!/bin/bash

echo "Enter the value of N:"
read N

a=0
b=1
count=0

echo "Fibonacci sequence up to $N terms:"

while [ $count -lt $N ]
do
    echo -n "$a "
    fib=$((a + b))
    a=$b
    b=$fib
    count=$((count + 1))
done

echo

