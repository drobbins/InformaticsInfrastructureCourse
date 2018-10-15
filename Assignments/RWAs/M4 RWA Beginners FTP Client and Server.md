[Back to M4 Real World Assignment Menu](m4-real-world-assignment-menu)

## Outcomes
After successfully completing this assignment, you will be able to:

1. Develop basic network software that completes the following operations: (SLO 2)
    * Making a TCP connection between a server process and a client process, each running on the **same** computer
    * Making a TCP connection between a server process and a client process, each running on **different** computers
    * Sending multiple bytes of information from a server process to a client process over the network by way of multiple read and write operations
2. Use the **netcat** software to masquerade as the **client** and **server** programs. (SLO 2)

## Instructions

In this assignment, you will develop two programs, a server program and a client program, based on the Java source code provided by the instructor. You shall modify those two programs so the server will act as a simple ftp server, and the client will act as a simple ftp client to transfer a text file. Both programs shall be written in Java, with only one file per program (i.e, one client file and one server file).

1. Download the TCPClient.java and TCPServer.java files.
2. Rename the two files FTPClient.java and FTPServer.java, respectively.
3. Name the two classes FTPClient and FTPServer that are stored in those two files.
4. Compile the two programs, and run them according to the directions in the textbook to confirm that each works correctly.
5. Read and follow the [Design and Implementation Constraints](#design-and-implementation-constraints) described in the section below.
6. In your server program, change the algorithm so it reads the contents of a text file **line by line** from standard in and directly sends the text **line by line** to the client that connects to the server. When the file is completely sent, have the server send the client a line containing only ZZZZ (four capital Zs). Then have the server wait for input from the client (i.e., readLine). When the client closes its connection, it will cause the input from the client to be null. Close the server connection and terminate the program normally.
7. In your client program, change the algorithm so the client contacts the server and reads a series of lines sent by the server, printing each line to standard out as it is received, until a line containing only ZZZZ (four capital Zs) is read from the server. (Do NOT print this ZZZZ line to standard out.) Then have the client terminate the program normally.
8. Neither program shall prompt the user for any information. All program interaction with the user shall happen by way of the command line and command-line redirection as shown in the section below on Running and Testing Your Program.
9. When testing your client and server programs, note that the only things they know about each other are the TCP network connection and the steps for exchanging the file data (i.e., our beginner's FTP protocol).
3. Submit your program files to the appropriate Real World Assignment.

In addition to completing the above instructions:

* Edit this page as you find additional information that you feel may be useful to future students.
* Feel free to add guidance to the instructions, insofar as you do not modify the basic requirements.

### Design and Implementation Constraints

*   Complete the entries in the comment block at the top of each file.
*   Keep your implementation simple and easy to understand.
*   Modularize your source code using only static methods in addition to the main function.
*   Create no other classes other than FTPClient and FTPServer.
*   Create no Java packages.
*   Use variable names and abbreviations commonly found in the dictionary.
*   Declare all variables at the top of a block.
*   Add no other functionality to the two programs other than what is requested in this assignment.

### Running and Testing Your Client and Server Programs

First start the server program in a command shell on one computer as shown below:

```
% java FTPServer  
Usage: java FTPSERVER <port number>

% java FTPServer 6789

% java FTPServer 6789 < sourceFile.txt
```

Then start the client program in a command shell on the same computer (later try it on another computer) as shown below, where the IP address entered on the command line is the address of the computer where the server program is running:

```
% java FTPClient  
Usage: java FTPCLIENT <IP address of server> <port number of server>

% java FTPClient 111.222.333.444 6789

% java FTPClient 111.222.333.444 6789 > targetFile.txt
```

After both programs terminate, check that the contents of the target file exactly match the contents of the source file.

### Using the Netcat Software

Netcat is "a featured networking utility which reads and writes data across network connections, using the TCP/IP protocol." (Source: Gnu Netcat)

Netcat is a standard installed software for Linux. For Mac and Windows, search on the web for a public domain version. Note that virus checkers don't like netcat, although it is not dangerous in itself. It is just dangerous for someone who may try to use it for malicious reasons. You will find out why after you see what it can do. :-)

Netcat uses a command line interface with basic features that are easy to learn. Just check out the netcat manual page on your computer or look on the Web. (You will discover that netcat is really a network "Swiss army knife".)

Test A: Start up the FTPServer and then communicate with it using netcat to masquerade as the FTPClient to accept a text file transfer.

Test B: Start up netcat in listener mode to masquerade as the FTPServer. Enter data into netcat that conforms to the simple FTP protocol so that the FTPClient thinks it is communicating with the FTPServer to obtain a text file.

## Assessment

| Item                          | Points |
|:------------------------------|-------:|
| Client Program Completeness   |      45|
| Server Program Completeness   |      45|
| Timing & Mechanics            |      10|
| **Total**                     |     100|
