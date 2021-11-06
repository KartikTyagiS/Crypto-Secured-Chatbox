# Crypto-Secured-Chatbox

This project is made for communicating securely on web and also to transfer data securely over the web.
For brief guide about this project you can go through Project Report and Presentation

Crypto_client & Crypto_server are client and server files. For running them execute the steps given below. input.tx file just contains some data that can be changed accordingly. This file was only for testing purposes.

For compiling the server: 
gcc crypto_server.c -lm -std=c99 -o server

For compiling the client: 
gcc crypto_client.c -lm -std=c99 -o client

For running the server, connecting client to server & simuntaneously testing the encryption & decryption:

./server 127.0.0.1 

./client 127.0.0.1 input.tx
