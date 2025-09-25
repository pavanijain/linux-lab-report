#!/bin/bash
echo "Enter filename: "
read file

if [ -e "$file" ]
then 
	echo "file exists. Contents are: "
	cat "$file"
else
	echo "file does not exist."
	echo "Do you want to create it? (y/n)"
	read choice 
	if [ "$choice" = "y" ]; then
	    touch "$file"
	    echo "file $file created."
	fi
fi
