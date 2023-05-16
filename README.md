# Optimization-Paths
Novel Method For Fibonacci Eval As Binary Expression

This Python script generates Fibonacci numbers, translates them to binary, and interprets the binary numbers as a series of operations (additions and subtractions). It then produces a scatter plot of the results of these operations.
Features

    Fibonacci Number Generator: This script generates the first 2000 Fibonacci numbers using Matrix Exponentiation, an efficient algorithm to calculate large Fibonacci numbers.

    Binary Translator: Each Fibonacci number is then converted to its binary representation.

    Binary Expression Evaluator: The binary numbers are interpreted as a series of operations (additions and subtractions), and these operations are performed to generate a result.

    Plot Generation: The script plots the results of these operations against the index of the Fibonacci number.

Code Structure

    The binary_to_expression function takes a binary number as input and interprets it as a series of operations, performing these operations and returning the result.

    The fib function generates a Fibonacci number. The helper functions multiply and power are used to perform the Matrix Exponentiation.

    The main part of the script generates the first 2000 Fibonacci numbers, converts them to binary, evaluates the binary expressions, and generates a scatter plot of the results.

Usage

Simply run the script to generate the plot. Make sure you have matplotlib installed in your Python environment for the plot to display. You can install it with pip:

sh

pip install matplotlib

Output

The script will display a scatter plot with the index of the Fibonacci number on the x-axis and the result of the binary expression on the y-axis. The title of the plot is "Scatter plot of the results of binary expressions". The x-axis is labeled "Index of Fibonacci number" and the y-axis is labeled "Result of expression".
Notes

This script uses Matrix Exponentiation to calculate Fibonacci numbers, which is a very efficient method for large indices. However, for very large indices, the time and space complexity can still be considerable due to the generation and manipulation of binary strings.
