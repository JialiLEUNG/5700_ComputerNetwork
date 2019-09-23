# 5700_ComputerNetwork

# project1:
## I.	Java Socket Programming implementation   
There are two java files: Server.java and Client.java.

Assume that you start a server your localHost (127.0.0.1), listening to port number 32000. 


In your terminal (terminal 1), you should type:

java Server.java 32000 <enter> 

and then open a new terminal (terminal 2), and type:

java Client.java 127.0.0.1 32000 <enter>  

In terminal 2, you can type your message and then hit enter:
For example, if you enter "This is my text to be changed by the SERVER <enter>"

Then in terminal 2, you will get:

"Response from server: revres EHT YB DEGNAHC EB OT TXET YM SI SIHt"

 At this point (after receiving one line to be reversed), the server and client should both exit.
 
 
 
 ## UDP Pinger 
Similar to the implementation above

What you need to change is the language (python) and file name (UDPPingerServer.py and UDPPingerClient.py).
You are expected to see similar things like:

python3 UDPPingerClient.py 
PING 0 0.0011069774627685547
PING 1 0.0004291534423828125
PING 2 0.0004029273986816406
Packet is lost. Request timed out
PING 4 0.0006160736083984375
Packet is lost. Request timed out
PING 6 0.0006086826324462891
PING 7 0.0004210472106933594
Packet is lost. Request timed out
PING 9 0.0006341934204101562

