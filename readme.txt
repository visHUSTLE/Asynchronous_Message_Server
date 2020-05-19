

CSE 5306 

Lab # 1 Summer – 2019
Asynchronous Message Server


IDE Used - Sublime Text Editor

How to Run ?

On cmd type cd "respective folder where the files have been stored"

First run the Server socket on cmd.  
Command : python socket_server.py --> Server will connect to the localhost.( Which shows server Process
works correctly)

Now open another cmd and run 
Command: python socket_client.py --> GUI will ask for the USERNAME, After entering username client will be 
connected with the same name.( Which shows Client Process works correctly)
														
On the GUI,
Entry : Destination Client = Username(Either A, B or C)
        
Entry : Message : Message to be sent 

On the server GUI, you will observe the following:

From 1to1 the display will be 'From' with the sender's username.
You can see the unparsed HTTP message received from a client to the screen.
After the message has been successfully sent to the server, then
disconnecting from the server.

The GUI also provides a button called 'Quit' to kill the process.



References:
#socket connection reference : https://www.journaldev.com/15906/python-socket-programming-server-client
#https://github.com/YashAvlani009/Sockets-and-Thread-Management
#https://www.geeksforgeeks.org/socket-programming-multi-threading-python/
 
