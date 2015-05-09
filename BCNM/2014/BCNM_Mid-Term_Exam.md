# BCNM Mid-term exam
## Problem 1
1. Why does the TCP need the Fast Recvocery mechanism?
2. If the in-order accepts policy is applied by a TCP receiver, which Retransmission timer policy may make the TCP performance better? Why?
3. What does the role played by the NS flag in the TCP header?

## Problem 2
1. Explain the operation of TCP flow control.
2. Consider the following table of TCP congestion window size (i.e., ***cwnd***) as function of round-trip time (RTT) from a TCP sender to a TCP receiver. Given the TCP congestion control behavior: slow start at RTTs: 1-6, 23-26 and congestion avoidance at RTTs: 7-22.
   - Complete the following table by fill out cwnd values.
   - What is the value of **ssthresh** at the 17th transmission round(RTT)?
   - Assuming a segment loss is detected after the 26th round by the receipt off a triple duplicate ACK (dupAck), what will be the values of the *cwnd* and of *ssthresh*?

## Problem 3 
A TCP connection request (SYN) is sent to an FTP server (the target computer). Upon receiving the connection request, the server allocates resources to handle and track the new connection subsequently, and then responds with a "SYN-ACK".

1. If you computer sends many TCP SYNs to the FTP server, however, the source IP address in the packet is "spoofed", meaning that it was replaced with an address that is not in use on the Internet, or that belongs to another computer. What would happen to the server? Explain your answer as detail as possible.
2. In case (1), no SYN-ACK response is received by your computer. If the TCP protocol in the FTP server will retransmit the SYN-ACK 5 times, doubling the time-out value (which is used for retransmission timer) after each retransmission. The initial time-out value is three seconds, so retries are attempted at 6, 12, etc. After the last retransmission, how many seconds are allowed to pass before the computer gives up on receiving a response and deallocated the resources that were reserved earlier for the connection?
3. What is the total elapsed time in seconds that resources are allocated?

## Problem 4
1. Assume that there are N routers in a network and that every router has *m* neighbors, and each route entry needs *x* bytes. Estimate the amount of memory required to store the routing information used by the *distance-vector routing protocol*.
2. Why does the "count-to-infinity" presented in RIP operation?
3. Build the DVT and RT (routing table) for all routers by Distance-Vector (Bellman-Ford) routing algorithm.

## Problem 5
1. Give at least three reasons that IPv6 may deliver packets faster than IPv4 does?
2. What is a "flow" in IPv6? How does the IPv6 protocol deal with those non-congestion controlled packets?
3. Explain the differences between stateless and stateful address autoconfiguration mechanism.
4. What is the meaning of "preferred lifetime" for an IPv6 global unicast address?
5. Give the NIC of a host with 48-bit MAC address of 00-80-c8-34-bb-56. The host activated IPv6 protocol after installing Windows 7 Operating system. Assume it is located inside a NAT region and the IP address of NAT server is 112.142.33.88. List all possible (all kinds of)IPv6 addresses the host may have. Assume your own values if they are required. 