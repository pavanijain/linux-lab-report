#!/bin/bash

read -p "Enter filename: " filename
if [ ! -f "$filename" ]; then
    echo "File does not exist."
    exit 1
fi

read -p "Enter word to count: " word
count=$(grep -o -i "$word" "$filename" | wc -l)
echo "The word '$word' appears $count times in $filename."


