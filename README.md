# Wireshark-Assignment---1--ARP-Capture
Wireshark Assignment - 1- ARP Capture
Assignment -1

FACULTY NAME: RAGHUDATHESH G P      			                 COURSE CODE: 15EC64 
 
COURSE NAME: COMPUTER COMMUNICATION NETWORKS              ACADEMIC YEAR: 2018-2019

The assignment is about an auxiliary protocol, ARP, which is part of the network layer, but it is used as a liaison between the network and the data-link layer. ARP is an auxiliary protocol that maps the IP address of connection to the host or router to the link-layer address of that connection. Do, trace and examine ARP packets.
Start your web browser and clear the browser’s cache memory, but do not access
any website yet.
Assignment:
1.	Open the Wireshark and start capturing. 
2.	Go to your browser and retrieve any file from a website. Wireshark starts capturing packets. 
3.	In the filter field of the Wireshark window type arp (lower case) and click Apply. Stop capturing and save the captured file. 
Part I: ARP request message
From the packet list pane, select the first ARP request packet. From the packet detail
pane, select the Address Resolution Protocol.   Questions:
Using the hexdump and consulting ARP Header format, answer the following question in your report sheet provided.
1. From the hexdump, determine
a. the hardware type.
b. the protocol type.
c. the hardware length.
d. the protocol length.
e. the value of the operation field. What is the meaning of this field?
f. the source hardware address.
g. the source protocol address? 
h. the destination hardware address.
i. the destination protocol address?
2. Using the packet detail pane, verify your answers to the first question.
3. What is the type of the destination hardware address (unicast, multicast, broadcast)? Which hardware interface does the destination address define?
4. Checking the packet byte pane, you will notice that the ARP request is followed by
zero-bytes. How many 0s are there? Explain the reason for the existence of these
0s.  Part II: ARP reply message
From the packet list pane, select the first ARP reply packet. From the packet detail
pane, select the Address Resolution Protocol; the packet’s hexdump will be highlighted
in the packet byte pane. 
Questions:
Using the hexdump and consulting ARP header format, answer the following
question in your report sheet. 
1. Using the hexdump, determine
a. the hardware type.
b. the protocol type.
c. the hardware length.
d. the protocol length.
e. the operation code.
f. the source hardware address.
g. the source protocol address? 
h. the destination hardware address.
i. the destination protocol address.
2. Using the packet detail pane, verify your answers to the first question.
3. What Type of address is the destination hardware address? What network interface
does the address define?

Documents to Provide:
1. ARP header Protocol format and description.
2. A copy of  report sheet that contain answered questions.
3. A printout of the supporting captured information.

Assignment Give Date: 12/02/2019
Assignment Submission Deadline: 22/02/2019

Note:
1.	This assignment maps the CO1 of the course and PO5 of the program.
2.	No student should copy the wireshark packet from other student.
3.	Do adhere to the deadline.
