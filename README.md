# Solid-Right-Angled-Triangle

Input: 4 

Output:

*

* *
  
* * *

* * * *

Question: Solid Right Angled Triangle

Given an integer number (N) as input, write a program to print the right-angled triangular pattern of N lines using an asterisk(*) character.

Input: The first line of input will contain a positive integer.

Output: The output should be N lines with an asterisk() character printing in a right-angled triangular pattern. Note: There is a space after each asterisk() character.

Example: If the given number is 4, the output should be:

Approach:
To solve this problem, we will follow these steps:

Read the input number (N).

Create a loop that runs from 1 to N.
In each iteration of the loop, print the asterisk(*) character with a space, repeated the same number of times as the current iteration.

Step-by-Step Explanation:

Step 1: Read the input number

First, we need to read the input number (N) which represents the number of lines in the right-angled triangle pattern. We can use the input() function to read the input and int() to convert it into an integer.

Step 2: Create a loop to print the pattern

Now, we will create a loop that runs from 1 to the input number (N). In each iteration of the loop, we will print the asterisk(*) character with a space, repeated the same number of times as the current iteration.

In this loop, we use the counter variable to keep track of the current iteration. We start with counter = 1 and increment it by 1 in each iteration using counter = (counter + 1). The loop continues until counter is greater than the input number (N).

Inside the loop, we print the asterisk() character with a space, repeated the same number of times as the current iteration using `print(" " * counter)`.
