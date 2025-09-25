#!/bin/bash
if [ $# -eq 0 ]
then 
	echo "UsGE: $0 FILENAME"
	exit 1

fi

file=$1

if [ -e "$file" ]
then
	echo "Lines: $(wc -1 < $file)"
	echo "Words: $(wc -w < $file)"
	echo "characters: $(wc -m < $file)"
else
	echo "File not found" 
fi
