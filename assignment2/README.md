# CMPE-279

Assignment 1

Tested on Google Cloud VM

Steps to execute:
1) Upload the client.c and server.c to the Google Cloud VM
2) Compile and run the server
```
gcc server.c -o server
sudo ./server
```
3) Open another terminal to the Cloud VM
3) Compile and run the client
```
gcc client.c -o client
./client
```

Output:

Server

```
execve=0x0x7f04c7172a00
waiting for child to complete...
Child process created....
Hello from client
Hello message sent
```

Client

```
Hello message sent
Hello from server
```