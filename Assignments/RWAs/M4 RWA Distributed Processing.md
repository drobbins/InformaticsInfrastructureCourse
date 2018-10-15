[Back to M4 Real World Assignment Menu](m4-real-world-assignment-menu)

## Outcomes
After successfully completing this assignment, you will be able to:

1. Write distributed processing algorithms for sorting. (SLO 2)
3. Write professional reports analyzing information technology functions. (SLO 1)

## Instructions

In this assignment, you shall develop two programs in Java or Python, a client program and a server program. You can either devise your own distributed algorithm to implement or use the one described below. Your algorithm may use either TCP or UDP for communication between the client and server.

1. Write and test two programs implementing the [A Distributed Sorting Algorithm](#a-distributed-sorting-algorithm), following [Design and Implementation Constraints](#design-and-implementation-constraints).
2. Prepare a README.txt file, conforming to the standards in [Format of your README.txt File](#format-of-your-readme.txt-file).
3. Submit your program and README.txt files to the appropriate Real World Assignment.

In addition to completing the above instructions:

* Edit this page as you find additional information that you feel may be useful to future students.
* Feel free to add guidance to the instructions, insofar as you do not modify the basic requirements.

### A Distributed Sorting Algorithm

The client program shall create an array of **10 to 10,000** randomly-generated positive integers. (The highest randomly-generated number shall be 20,000.) The actual number of integers in the array shall be based on an integer value submitted on the command line (along with the IP addresses and port numbers). The client shall then contact three servers to help in sorting the integers, send an approximately equal number of integers to each server, receive the sorted integers back from the servers, merge the results, and print the sorted integers to standard out. The client shall print two spaces between each integer. The server program shall contain the implementation of a sorting algorithm of your choice.

Except for the command line input for both programs and the printing of integers by the client, the two programs shall have no other keyboard or screen interaction with the user

### Format of your README.txt File

Put the numbers and the field names shown below into your readme.txt file along with your specific information for that field.

1.  STUDENT NAME:     Your first and last name
2.  SOURCE CODE FILES:     A list of the names of all of your Java source code files
3.  BUILD DIRECTIONS:     Directions on how to compile your programs on the command line
4.  RUN DIRECTIONS:     Directions on how to run your program from the command line along with examples for both the client and server
5.  PROGRAM DESCRIPTION:     A one-to-two paragraph description about what your client and server programs do
6.  OPERATIONAL STATUS:     The operational status of your client and server programs (i.e., what works and what doesn't work based on the requirements for the assignment)

### Design and Implementation Constraints

*   Name your two primary source code files Client.java (or Client.py) and Server.java (or Server.py). Also use these same names (without the file extension) for the client and server classes. These should be the only classes containing a main method. (You may also implement other classes as needed, with one class per file)
*   At the top of each file, place a completed comment block as described in previous programming assignments.
*   Keep your implementation simple and easy to understand.
*   Modularize your source code, both within a file and among files.
*   Create no threads other than your main Java program.
*   Use only variable names and abbreviations commonly found in the dictionary.
*   Declare all variables at the top of a block.
*   Add no other functionality to your two programs other than what is requested in this assignment.
*   Have no user-defined packages in the Java source code that you submit on Canvas.

## Assessment

| Item                          | Points |
|:------------------------------|-------:|
| Lab Completion                |      45|
| Report Content                |      45|
| Timing & Mechanics            |      10|
| **Total**                     |     100|
