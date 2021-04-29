# CMPE279
### Phat Truong
### SJSU Student ID : 008397987

### General Info
* Assignment 1 - Extend the server code to use privilege separation.
* Assignment 2 - Re-exec the server’s child process after forking
* Removing out the socket option SO_REUSEPORT to fix the issue "setsockopt protocol not available"

### Installation
* Compile both programs
```
clang client.c -o client
clang server.c -o server
```
* Start the server
```
./server
```
* Start the client
```
./client

```

