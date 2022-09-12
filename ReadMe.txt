1. open 5 seperate terminals in their directory
2. accordingly run these commands 
in 1st
   gcc -o server server.c
   ./server <server port>
in 2nd 
   gcc -o node node.c
    ./node <server ip> <server port> <node port1>
in 3rd
     ./node <server ip> <server port> <node port2>
in 4th 
      ./node <server ip> <server port> <node port3>
in 5th
   gcc -o client client.c
       ./client <server ip> <server port>
    then, when it asks you the file to download,
type either "TestFile1 or TestFile2 or TestFile3".

** (Port number should be > 1023, port numbers 0 to 1023 are reserved)
IP address can used by using command "ifconfig" (in our case, we used 127.0.0.1) **


The content in the TestFiles can be seen in the testfiles given in mainfolder.
