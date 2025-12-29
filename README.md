# ChatTCP

TCP sockets based chat program

# Example

## Server

```
$ ./chattcp 
Welcome to ChatTCP!

Server[0] Client[1]

Enter your choice [0/1]: 0
Enter port number: 8004
Starting server...
You: Hiii
Reply: Byyee
You: EXIT
Exiting...
Server closed!
```

## Client

```
$ ./chattcp 
Welcome to ChatTCP!

Server[0] Client[1]

Enter your choice [0/1]: 1
Enter port number: 8004
Reply: Hiii
You: Byyee
Reply: EXIT
Server requested close
Client closed!
```
