# client-server-model
A basic client server model messaging application written in C++

Access to view code is available upon request, this is to maintain compliance with University at Buffalo's Academic Integrity Policy.

### Server Commands
- AUTHOR - prints information about the author and UB's academic integrity policy.
- IP - prints the IP of the server machine.
- PORT - prints the port the server is using.
- LIST - prints a list of all currently logged in clients.
- STATISTICS - prints a list of all clients along with statistics associated with each client.
- BLOCKED client-ip - prints a list of all clients blocked by client-ip
  
  
### Client Commands
- AUTHOR - prints information about the author and UB's academic integrity policy.
- IP - prints the IP of the client machine.
- PORT - prints the port the client is using.
- LIST - prints a list of all currently logged in clients.
- LOGIN - (server-ip, server-port) - logs into the server at server-ip using server-port
- REFRESH - gets an updated list of currently logged in clients from the server
- SEND (client-ip, message) - send a message to the client at client-ip
- BROADCAST (message) - send a message to all logged in clients
- BLOCK (client-ip) - blocks all messages and broadcasts from the client at client-ip
- UNBLOCK (client-ip) - unblocks a client at client-ip
- LOGOUT - logout from the server, the application does not exit and you can log back in
- EXIT - logout from the server, and exit the application
