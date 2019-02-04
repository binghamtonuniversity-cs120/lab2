#### CS 120 - Spring 2019
# Lab 2 - Working with C
## Due Date: In Lab

### Provided Files
* _Files_
    * N/A

**You must demo to the TA by the end of your lab.**

### Guidelines

Although this is an individual lab assignment, it is permissible to consult with classmates to ask general questions and to get help. You may also research online for additional resources; however, you must be able to explain how you got your answers to the TA to complete the lab.


_In this lab, you will learn to:_

* Work with a C program
* Print the binary representation of a number


## Part A: Counting Bits


In Part A you are going to examine binary.

First you will write a function that counts the number of 1’s in the binary representation of an integer passed as a parameter to a function called countOnes(). You should return the number of 1s in the function’s parameter as an unsigned int.

## Part B: Printing Bits

Next you will write a looping binary interpreter that prints the binary representation of a decimal value.

Write a function that uses bit shifting to store the binary representation of an integer in an array passed as a parameter. You will be given the size of the array and should make sure you fill out all elements in the array.

To generate the array of values, you will need to use a bit mask and bitwise right shift.
* For example, 8 would store the following value in your array
    * 0000 0000 0000 0000 0000 0000 0000 1000
* You should call your function with the following test values:
    * 2
    * 255
    * -1
    * INT_MAX
    * INT_MIN
        * The driver code includes the library <limits.h> at the top of the main source code file so you can use the global constant INT_MAX and INT_MIN
   * You can use the following website to check your results: http://www.binaryhexconverter.com/binary-to-decimal-converter

## Part C: Submission

Ask your TA to demo. The TA will ask you to show your answers, and may ask you to explain how you got an answer. After the TA marks you as having completed the lab, you may leave.
