#!/bin/bash

# Simple Interest Calculation Script

# Prompt the user to enter the principal amount
echo "Enter the principal amount:"
read principal

# Prompt the user to enter the rate of interest
echo "Enter the rate of interest (in %):"
read rate

# Prompt the user to enter the time period (in years)
echo "Enter the time period (in years):"
read time

# Calculate the simple interest
simple_interest=$(echo "scale=2; ($principal * $rate * $time) / 100" | bc)

# Display the result
echo "The Simple Interest is: $simple_interest"
