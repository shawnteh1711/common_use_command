# lsof
check file descriptor leaks in program.
Stand fot "list open files"
It can be used to list all of the open files, sockets, and other resources on a system
You will need to know process ID (PID) of the program to use lsof. Can using ps command or top to find PID.
For example, to list the open file descriptors for a program with PID 1234, you could use the following command:
`
lsof -p 1234
`
