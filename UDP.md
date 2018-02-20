### IWL UDP Test Suite
### User Datagram Protocol (UDP)
The UDP Test Suite is used by design engineers, quality assurance engineers and testers to find and fix bugs in their UDP implementation. The tests
help ensure that the UDP implementation is sufficiently robust so that it is not vulnerable to the wide range of attacks in today's Internet. The tests make
use of the Maxwell Pro network emulation environment, so that each test sequence can intelligently impair all aspects of the UDP protocol.

The UDP Test Suite contains unique test cases that take on parameters for greater coverage. The tests ensure UDP compliance through vulnerability
and robustness testing.

Some of the covered areas are highlighted below:
* Change the source and destination addresses to improper or unusual values such as loopback, multicast, interface-local multicast, link-local
multicast, etc.
* Set the "next header" field to a value not assigned by IANA with all of the above mentioned address variations.
* Set the "hop count" to zero with all of the above mentioned address variations.
* Insert a type 0 routing extension header with the next address being one of the above mentioned address variations.
* Insert a type 0 routing extension header with inconsistent information.
* Insert hop-by-hop extension with various router alert option values and without any message.
* Insert hop-by-hop extension with two router alerts with various router alert option values and without any message.
* Insert hop-by-hop extension with a router alert option with an invalid length.
* Adjust payload so checksum is -0 and set checksum field to -0.
* Adjust UDPv4 payload so checksum is -0 and set checksum field to +0.
* Adjust UDPv4 payload so checksum is +1 and set checksum field to +0.
* Adjust UDPv6 payload so checksum is -0 and set checksum field to +0.
* Adjust UDPv6 payload so checksum is +1 and set checksum field to +0.
* Set checksum field so it contains -1.
* Invert the checksum field bit values.
* Set the length field to zero.
* Set the length field so it exceeds actual length by 8.
* Set all the length field bits to one.
* Truncate the datagram so it validly contains only 6 bytes.
### Establishing a source of authority
The Maxwell Pro UDP Test Suite references the RFCs that correlate to each test area. These official IETF documents detail the Internet standards and
best current practices that can point the user toward a better understanding of the problem.
#### RFCs Referenced 
* RFC 768 User Datagram Protocol
####  Sample Test Documentation
Test documentation follows the format below:  
Purpose of the Test:  
Impairment Algorithm:  
Possible Behaviors or Outcomes:  

<p style="margin-top:2em;text-align:center;"><a href="/company/contact" class="btn btn-danger">Contact Us</a></p>

© Copyright 2018 InterWorking Labs, Inc. dba IWL. <br> 
Web: https://iwl.com <br> 
Phone: +1.831.460.7010 <br> 
Email: info@iwl.com