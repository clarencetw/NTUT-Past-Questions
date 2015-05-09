# BCNM Quiz
## Problem 1 - Simple questions
1. What is the difference between promiscuous and non-promiscuous mode while capturing packets?
2. What is the key information required for packet forwarding and how?
3. What is the key information required for a layer 2 switch to operate (i.e., the one it relied on doing frame switching/forwarding)?
4. What does a switch do when it found no matched-entry for a frame's destination in the MAC table?

## Problem 2 - TCP-related questions
1. What is the meaning of self-synchronization (clocking) behavior of a TCP connection? Why the TCP protocol cannot relies on self-synchronization effect for TCP congestion control?
2. If the in-order accepts policy is applied by a TCP receiver, which Retransmission timer policy may make the TCP performance better? Why?
3. What is the main purpose of Time-Wait state in TCP state machine? How long the TCP may stay in this state?
4. Why the slow start mechanism is not conservative one, in terms of congestion control?
5. Assume that Windows OS sets the RTO = 3sec. for a TCP segment in its first transmission and applies Karn's algorithm for time out (lost) event. A lost segment (while no corresponding ACK received) will be retransmitted for the maximum of 5 times and be aborted if lost again. What is the max time spent on processing the same segment in worst case?

## Problem 3 - Application-related questions
1. What is the meaning of a "socket" in Internet Application? (You may answer it from any aspect.)
2. Generally, a FTP client will close its data connection with the FTP server right after it finished file transferring. Why is that?
3. What is the transport-layer protocol used for SIP (Session Initiation Protocol) in VoIP? What is Session Description Protocol (SDP)?
4. A FTP client issues a command "PORT 112.124.100.101.45.220" to a FTP server. What is the port number implied? What is the effect of that command?

## Problem 4 - TCP buffer (TCB)-related question
Give the visualization of TCP buffers below. Explain the meaning of "Retransmission queue", "Reorder buffer", "ACKs in-flight", and "Data in-flight".

## Problem 5 - MIME question
Apply Radix-64 transfer encoding rule to encode the following message: "2015 BCNM"

## **Bonus Problem**
Explain how the IPv4-based Internet works as detail as possible