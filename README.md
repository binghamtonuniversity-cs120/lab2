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

* Work with a basic C program
* Use conditional a looping statements in C


## Part A: Printing Stars

To write c code you use a text editor, just like any other programming language. Open a text file (you can create a new text file using gedit by opening gedit from the command line):
```shell
gedit lab2.c
```

A basic c program looks like:
```c
#include <stdio.h>
int main(){
    printf("Hello World!");
}
```
Go ahead and add the above code to your text file, then save it. Keep track of where the file was saved so you can navigate to its location on the command line.

For the above program, you should compile with `gcc`. If you are in the same folder as your file, you can use the command:
```shell
gcc lab2.c -o lab2
```
You can then run your program with:
```shell
./lab2
```
Now alter your program to make a 4 level pyramid with asterisks. Your output should look like:
```shell
   *
  * *
 * * *
* * * *
```
Once you have everything printing out properly, move on to Part B.

## Part B: Printing values

Alter your program to make the pattern like a pyramid with a number that represents the level repeating in the appropriate row. For example:
```shell
   1
  2 2
 3 3 3
4 4 4 4
```
## Part C: Submission

Ask your TA to demo. The TA will ask you to show your answers, and may ask you to explain how you got an answer. After the TA marks you as having completed the lab, you may leave.
