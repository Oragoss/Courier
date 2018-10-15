# Courier
Simple UDP Game Server

#To run the linux version:
- g++ -o server server.cpp
- g++ -o client client.cpp
- Then run client.exe in the terminal with a message parameter (i.e. ./client "Hi!")

#To run the windows version:
- Build the solution
- Run Client.exe from powershell with a message parameter (i.e. .\Client "Hi!")

#TODO:
1. Make server response to clients
2. (BIG) Make simple FPS game that sends messages to server and recieves response
3. Add TCP connection bindings for things like Player Join/Disconnect