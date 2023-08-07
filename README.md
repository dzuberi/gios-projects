# gios-projects
Repository containing GIOS (Graduate Intro to OS projects)

# Project 1:
GETFILE client and server - created a singlethreaded download client and server using the GETFILE protocol in C. Used the APIs created in the previous part to create a multithreaded client and server using a boss-worker model, a steque datastructure, pthreads, and mutexes

# Project 3:
Created a multithreaded proxy server to get HTTP data and send it to the GETFILE client.
Created a multithreaded cache server which receives download requests from the proxy server, checks its cache, and sends the data using shared memory IPC to the server. Used POSIX semaphores and designed a communication protocol.

# Project 4:
Designed and implemented RPC methods to store, list, fetch, and stat files on a remote server from multiple clients.
Created a distributed file system using these RPC methods.
