# HanoiGuide

Tower of Hanoi Guide

This Java program provides a solution to the classic Tower of Hanoi problem using recursion. The objective of the Tower of Hanoi is to move a stack of plates from one rod (source) to another (destination), using an auxiliary rod (helper), while adhering to the following rules:

1. Only one plate can be moved at a time.
2. A plate can only be placed on top of a larger plate.
3. All plates must be moved from the source rod to the destination rod in the least number of moves.

The program takes input from the user specifying the number of plates and prints step-by-step instructions for moving the plates from the source rod to the destination rod.

Key Features:
- Recursive solution: The algorithm recursively divides the problem into smaller sub-problems to efficiently solve the puzzle.
- Step-by-step instructions: Outputs each move in the correct sequence to solve the puzzle with the minimum number of moves.
- Flexible input: The number of plates can be set dynamically at runtime via user input.

Example Output ....

For n = 3 

Transfer Plate 1 from S and place in D
Transfer Plate 2 from S and place in H
Transfer Plate 1 from D and place in H
Transfer Plate 3 from S and place in D
Transfer Plate 1 from H and place in S
Transfer Plate 2 from H and place in D
Transfer Plate 1 from S and place in D

For n = 4

Transfer Plate 1 from S and place in H
Transfer Plate 2 from S and place in D
Transfer Plate 1 from H and place in D
Transfer Plate 3 from S and place in H
Transfer Plate 1 from D and place in S
Transfer Plate 2 from D and place in H
Transfer Plate 1 from S and place in H
Transfer Plate 4 from S and place in D
Transfer Plate 1 from H and place in D
Transfer Plate 2 from H and place in S
Transfer Plate 1 from D and place in S
Transfer Plate 3 from H and place in D
Transfer Plate 1 from S and place in H
Transfer Plate 2 from S and place in D
Transfer Plate 1 from H and place in D

Step's required for n plates to be transfered from Source to Destination : (2^n) - 1 

Complexities is as follow's :

Time Complexity: O(2^n)     Exponential due to the recursive nature and the doubling of sub-problems.
Space Complexity: O(n)      Linear space usage due to recursion depth.

THANK YOU...
