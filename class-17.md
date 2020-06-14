# TCP

- The Transmission Control Protocol (TCP) is widely used by application layer protocols in the Internet Protocol Suite. TCP creates a two way communication between two hosts and provides reliable, ordered, and error checked byte streams between the applications. TCP data transfers manage network congestion and use flow control to limit the rate a sender transfers data to guarantee reliable delivery. Each IP packet between the hosts carries a single TCP Segment. A TCP segment is made up of header and data sections.

### TCP HEADER
The TCP Header is used at each end to control the type of interaction being sent. It contains the following information:
-  a 16 bit source port
- a 16 bit destination port
- a 32 bit sequence number that sets the initial sequence number and manages the accumulated sequence number
- if ACK is set it contains a 32 bit acknowledgement number that is the next sequence number that the sender is - expecting. It is used for acknowledging the bytes it has so far received
- a 4 bit data offset specifies the size of the tcp header in 32 bit words.
- 9 flag bits
- NS - an experimental feature for a nonce sum - a nonce is a random cryptographic number used to prevent people - from lying about who they are (authentication)
- CWR - used to acknowledge that a TCP segment with the ECE flag has been received, and the Window has been - reduced to alleviate congestion
- ECE - if SYN is 1 it indicates that the peer is ECN capable, other otherwise its used to indicate that there is - network congestion.
- URG - indicates that the Urgent pointer filed is significant
- ACK - indicates that the ACK field is significant - all packets after the initial SYN should have this flag set
- PSH - used to ask to push the buffered data to the receiving application.
- RST - used to reset the connection
- SYN - sent only on the first packet sent from each end to synchronize the sequence numbers
- FIN - indicates the last package from a sender, and is used in closing a connection
- a 16 bit window size
- a 16 bit checksum used for error checking the header
- if URG is set it contains a 16 bit urgent Pointer
- a variable 0 to 320 bit (divisible by 32) options section
