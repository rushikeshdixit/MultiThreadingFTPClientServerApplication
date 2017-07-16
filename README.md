# MultiThreadingFTPClientServerApplication

/*README*/


1.  Make a directory named download and specify its path in client.java for receiveFile() method.
2.  Specify path in createUserDirectory() method where the username directory will be created.
3.  In controlConnection.java in checkUser() method specify the path where the directory is created.
4.  In DataConnection.java in receiveFile() and sendFile() method specify the same workspace path given earlier.
5.  Run the server
6.  Run multiple clients
7.  Specify the address as 127.0.0.1 in all clients to connect to server
8.  Enter any username and password with space in between specified in the Credentials.txt file
9.  Follow the menu
10. For uploading a file specify the whole path with filename and its extension.
11. For downloading a file specify only the filename and its extension.

/*SCENARIOS*/

1. Uploading a large file and downloading a file by two different clients.

2. Download a file from client1, uploading the two different files from
   client2 on different instances.

3. Uploading one large file and a small file at the same time.
