#!/bin/bash

echo "Enter an email address:"
read email

# Regex for email validation
pattern="^[a-zA-Z0-9._%+-]\+@[a-zA-Z0-9.-]\+\.[a-zA-Z]\{2,4\}$"

if [[ $email =~ ^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,4}$ ]]; then
    echo "Valid email address"
else
    echo "Invalid email address"
fi

