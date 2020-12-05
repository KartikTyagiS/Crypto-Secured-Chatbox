# Crypto-Secured-Chatbox

In order to compile follow the steps given for each file

Server: 
gcc crypto_server.c -lm -std=c99 -o server

Client: 
gcc crypto_client.c -lm -std=c99 -o client

To run the program follow the steps:

For running the server: 
./server 127.0.0.1

For running the client and testing fo rencryption: 
./client 127.0.0.1 input.tx
