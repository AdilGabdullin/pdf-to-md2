## IWL ICMP Test Suite

### The Internet Control Message Protocol(ICMP)
The purpose of ICMP is to provide feedback about problems in the communication environment, such as an error in datagram processing. Typically
ICMP reports problems in the processing of datagrams.

The [Maxwell Pro ICMP Test Suite](https://iwl.com/maxwell-pro) provides a series of tests for verifying correct operation of ICMP. The tests ensure TCP/IP compliance through
vulnerability and robustness testing, with tests for ICMP in both the IPv4 and IPv6 environments.

The tests are grouped into categories as follows:
#### IPv4 ICMP 
* Change type and codes to values not assigned by IANA.
* Set the checksum to zero.
* Set unused protocol fields to non-zero values.
* Truncate messages.
* Extend messages
* Set protocol fields (including length fields) to inconsistent values.
* Set protocol address fields to unreasonable values such as
127.0.0.1 and 255.255.255.255.
* Allow user specified changes of 8, 16, and 32-bit quantities in the
packet.
#### IPv6 ICMP 
* Change type and code fields to values not assigned by IANA.
* Set the checksum to zero.
* Set unused protocol fields to non-zero values.
* Truncate messages.
* Extend messages
* Set protocol fields to inconsistent values.
* Set the Parameter Problem Pointer field to zero and 0xFFFF.
* Change the address of the appended IPv6 header to contain an
invalid or unusual address.
* Allow user specified changes of 8, 16, and 32-bit quantities in the
packet.
### Establishing a source of authority
[The Maxwell Pro TCP/IP Test Suite](https://iwl.com/maxwell-pro) references the RFCs that correlate to each test area. These official IETF documents detail the Internet standards and
best current practices that can point the user toward a better understanding of the problem.
#### TCP/IP RFCs Covered
[RFC 791](http://datatracker.ietf.org/doc/rfc791/), Internet Protocol (IP)  
[RFC 792](http://datatracker.ietf.org/doc/rfc792/) Internet Control Message Protocol (ICMP)  
[RFC 894](http://datatracker.ietf.org/doc/rfc894/) A Standard for the Transmission of IP Datagrams over Ethernet Networks  
[RFC 1042](http://datatracker.ietf.org/doc/rfc1042/) Standard for the Transmission of IP datagrams over IEEE 802 networks  
[RFC 4443](http://datatracker.ietf.org/doc/rfc4443/) Internet Control Message Protocol (ICMPv6) for the Internet Protocol Version 6 (IPv6) Specification  
#### Sample Test Documentation
Test documentation follows the format below:  
**Purpose of the Test:**  
**Impairment Algorithm:**  
**Possible Behaviors or Outcomes:**  
The ICMP Test Environment is used by design engineers, quality assurance engineers and testers to find and fix bugs in their stack or engine. The
tests help ensure that the stack is sufficiently robust so that it is not vulnerable to the wide range of attacks in today's Internet. The tests make use of
the [Maxwell Pro network emulation environment](https://iwl.com/maxwell-pro), so that each test sequence can intelligently impair all aspects of the protocol.

<p style="margin-top:2em;text-align:center;"><a href="/company/contact" class="btn btn-danger">Contact Us</a></p>

© Copyright 2018 InterWorking Labs, Inc. dba IWL. <br> 
Web: https://iwl.com <br> 
Phone: +1.831.460.7010 <br> 
Email: info@iwl.com