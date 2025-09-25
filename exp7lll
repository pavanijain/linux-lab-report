#!/bin/bash

if [ $# -eq 0 ]; then
    echo "Usage: $0 filename"
    exit 1
fi

filename=$1

if [ ! -f "$filename" ]; then
    echo "File does not exist."
    exit 1
fi

count=$(grep -i "^[aeiou]" "$filename" | wc -l)
echo "Number of lines starting with a vowel: $count"

