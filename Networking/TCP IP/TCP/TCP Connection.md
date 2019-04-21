# TCP Connection

A TCP connection is established with a three-way handshake.

 1. SYN: The active open is performed by the client sending a SYN to the server. The client sets the segment's squence number to a random value A.
 2. SYN-ACK: In repsonse, the server replies with a SYN-ACK. The acknowlegment number is set to one more than the received sequence number i.e. A+1, and the sequence number that the server chooses for the packet is another random number, B.
 3. ACK: Finally, the client sends an ACK back to the server. The sequenc

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTEyOTI4NzgyNV19
-->