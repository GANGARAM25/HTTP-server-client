# HTTP-server-client
An HTTP Server-Client using TCP protocol which allows different users to communicate over a network.

# Run the Myhttp file 
1. Compile and create executable file as gcc Myhttp.c -o Myhttp
2. Why running the code provide a port let say 20000 in the command line ./Myhttp 20000
3. Now this server will be runing.
4. Add some example files which browser can ask for from the files_to_send folder.

# Compile Mybrowser.c file
1. Compile and create executable file as gcc Mybrowser.c -o Mybrowser
2. After running the file.
3. Now ask for any file from browser side firslty check whether the file is present on http side.
4. For asking the files from the server side we can do GET
5. // GET http://127.0.0.1/abc.txt:20000
6. For uploading any file from teh browser to the server side we can do as follow:
7. // PUT http://127.0.0.1/:20000 abc.txt


# NOTE:
All the ativities log will be saved on the http side in Activitylog.txt file.

