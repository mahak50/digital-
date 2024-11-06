#!/bin/bash
# Loop to continuously display current time
while true; do
 clear
 current_time=$(date +"%H:%M:%S")
 echo "Current Time: $current_time"
 sleep 1
done
```
