## IWL ARP Test Suite
### Address Resolution Protocol
The Address Resolution Protocol (ARP) maps IP network addresses to hardware addresses used by a data link protocol. The protocol operates below
the network layer.

ARP finds the MAC hardware address of a host from its known IP address. ARP maintains a cache in which MAC addresses are mapped to IP
addresses.

Note that ARP is used by IPv4; IPv6 uses Neighbor Discovery Protocol (NDP) instead of ARP.
### Test ARP with the Maxwell Pro TCP/IP Test Suite
IWL’s TCP/IP Test Suite includes fifty tests for the Address Resolution Protocol (ARP).

The tests, based on RFCs 826, 1122, and 5227, test the quality, conformance, and robustness of ARP implementations.

A summary of the ARP tests is included below:
#### New ARP Test Summary
* IPv4.ARP.001 IPv4 packet with source addresses not in DUT's ARP translation table.
* IPv4.ARP.002 ARP Request with Ethernet source different from ARP Hardware Sender.
* IPv4.ARP.003 ARP Request with Hardware type field set to unassigned type.
* IPv4.ARP.004 ARP Reply with Hardware type field set to unassigned type.
* IPv4.ARP.005 ARP Request with Protocol type field set to unassigned type.
* IPv4.ARP.006 ARP Reply with Protocol type field set to unassigned type.
* IPv4.ARP.007 ARP Request with Hardware length field set to 0.
* IPv4.ARP.008 ARP Reply with Hardware length field set to 0.
* IPv4.ARP.009 ARP Request with Hardware length field set to 4.
* IPv4.ARP.010 ARP Reply with Hardware length field set to 4.
* IPv4.ARP.011 ARP Request with Protocol length field set to 0.
* IPv4.ARP.012 ARP Reply with Protocol length field set to 0.
* IPv4.ARP.013 ARP Request with Protocol length field set to 6.
* IPv4.ARP.014 ARP Reply with Protocol length field set to 6.
* IPv4.ARP.015 ARP packet with Opcode field set to 0.
* IPv4.ARP.016 ARP packet with Opcode field set to 26.
* IPv4.ARP.017 ARP Request with Hardware Sender Address set to all bits broadcast.
* IPv4.ARP.018 ARP Request with Hardware Sender Address set to 1 bit broadcast.
* IPv4.ARP.019 ARP Request with Hardware and Protocol Sender Address set to broadcast.
* IPv4.ARP.020 ARP Request with Hardware and Protocol Sender Address set to multicast.
* IPv4.ARP.021 ARP Request with Protocol Sender Address set to all ones broadcast.
* IPv4.ARP.022 ARP Request with Protocol Sender Address set to 127.0.0.2 localhost.
* IPv4.ARP.023 Unrequested broadcast ARP Reply.
* IPv4.ARP.024 Unrequested unicast ARP Reply.
* IPv4.ARP.025 Unrequested ARP Reply with non-DUT Hardware Target Address.
* IPv4.ARP.026 Unrequested ARP Reply with new Protocol Sender Address and non-DUT Protocol Target Address.
* IPv4.ARP.027 Unrequested ARP Reply with existing Protocol Sender Address and non-DUT Protocol Target Address.
* IPv4.ARP.028 Request appears to come from DUT hardware but different protocol address.
* IPv4.ARP.029 Request appears to come from DUT hardware with same protocol address.
* IPv4.ARP.030 Reply appears to come from DUT hardware but different protocol address.
* IPv4.ARP.031 Reply appears to come from DUT hardware with same protocol address.
* IPv4.ARP.032 Opcode 26 ARP appears to come from DUT hardware but different protocol address.
* IPv4.ARP.033 Opcode 26 ARP appears to come from DUT hardware with same protocol address.
* IPv4.ARP.034 Request from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.035 Reply from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.036 Opcode 26 ARP from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.037 Using TCP; Request from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.038 Using TCP; Reply from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.039 Using TCP; Opcode 26 ARP from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.040 Using TCP; Slow Requests from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.041 Using TCP; Slow Replys from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.042 Using TCP; Slow Opcode 26 ARPs from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.043 Using TCP; Fast Requests from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.044 Using TCP; Fast Replys from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.045 Using TCP; Fast Opcode 26 ARPs from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.046 Fixed IPv4; Fast Requests from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.047 Fixed IPv4; Fast Replys from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.048 Fixed IPv4; Fast Opcode 26 ARPs from other sender hardware has DUT's Protocol Address.
* IPv4.ARP.049 Request is in a 1500 byte Ethernet frame.
* IPv4.ARP.050 Request contains non-null Ethernet frame padding.

<p style="margin-top:2em;text-align:center;"><a href="/company/contact" class="btn btn-danger">Contact Us</a></p>

© Copyright 2018 InterWorking Labs, Inc. dba IWL. <br> 
Web: https://iwl.com <br> 
Phone: +1.831.460.7010 <br> 
Email: info@iwl.com