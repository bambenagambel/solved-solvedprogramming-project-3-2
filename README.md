Download Link: https://assignmentchef.com/product/solved-solvedprogramming-project-3-2
<br>
Assignment Overview

This assignment will give you more experience on the use of loops In this project, we are going to compute the number of times a given digit D appears in a given number N. For example, the number of times 5 appears in 1550 is 2. The number of times 0 appears in 1550 is 1. The number of times 3 appears in 155 is 0. Etc.

Task

Your task is to implement the following the algorithm. 1- initialize a counter to 0 2- decompose the number N into its corresponding digits by calculating quotients and remainders of dividing it by 10 3- increment the counter each time the digit D appears Example: Given the number N = 1550 and the digit D = 5: Calculated Digit Counter 0 0 5 1 5 2 1 2

Project Description / Specification

1. Prompt the user for the given number and the given digit.

2. The program should have error checking to make sure the user inputs are valid. For example, if a user gives non-integer inputs, notify the user that the inputs are incorrect and prompt again.

4. Decompose the number in a loop and increment the counter within the loop as described in the example above. Deliverables Proj03.py — your source code solution (remember to include your section, the date, project number and comments).

1. Please be sure to use the specified file name, i.e. “proj03.py”

2. Save a copy of your file in your CSE account disk space (H drive on CSE computers). You will electronically submit a copy of the file using the “handin” program: http://secure.cse.msu.edu/handin Helpful hint To check if a string consists of digits only, you can use the “isdigit” method of the “str” type. Test out this method by assigning different string values to a variable, say “A”, and then calling the “digits” method on this variable, as in “A.isdigit()”. Type “help(str.isdigit)” to find more information. An example interaction An example of error handling: