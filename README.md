# SoftwareSystems_1

NumClass Library:

a directory that exposes the user to several functions for classifying numbers , The functions will be defined in the file:

NumClass.h When returning an int for a Boolean query:
0 is false
1 is true
 
The file contain the signatures:

*   will return if a number is Armstrong number
An Armstrong number is an n-digit number that is equal to the sum of the nth powers of its digits.
For Example: 407 = 43 + 03 + 73 = 64 + 0 + 343 = 407

* int isArmstrong (int)
/ * will return if a number is a palindrome * /

* int isPalindrome (int)
/ * will return if a number is prime * /

* int isPrime (int)

* Strong number is a special number whose sum of the factorial of digits is equal to the original
number.

- For Example: 145 is strong number
1! + 4! + 5! = 145
*  int isStrong (int)


 # The implementations of the functions  written in 3 different files:
1. The first basicClassification.c file that contain the implementations of the isStrong, isPrime functions

2. advancedClassificationLoop.c that contain the implementations of isPalindrome, isArmstrong functions that will be implemented
Using loops

3. advancedClassificationRecursion.c that contain the functions of the isPalindrome, isArmstrong functions which
Will be realized with the help of recursion




# Main plan :
program that will receive from the user 2 positive integers you must print to the screen 4 lines which
Will contain all the first numbers, Armstrong numbers, strong numbers and the Flanders which are between the two numbers
Received) including the numbers themselves (.
Do not print any additional output other than what you requested. You must be fully compliant with the input and output samples
That you will receive.

