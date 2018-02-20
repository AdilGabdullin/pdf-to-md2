### IWL SIP Test Suite
#### IP and MAC Layer Framing:
* Fragment packets according to MTU setting
* Remove all data from UDP packets intercepted
* Change the destination MAC address to be all ones (broadcast).
* Change the destination IP address to be all ones (broadcast).
* Change both destination MAC and IP address to be all ones
(broadcast).
* Add empty CRLF line at end of message without adjusting ContentLength.
* Add empty CRLF line at end of message and adjust Content-Length.
* Add empty CR line at end of message without adjusting ContentLength.
* Add empty CR line at end of message and adjust Content-Length.
* Add empty LF at end of message without adjusting Content-Length.
* Add empty LF line at end of message and adjust Content-Length.
* Append gibberish to the end of message without adjusting ContentLength.
* Append gibberish to the end of message and adjust Content-Length.
* Add nulls after CRLFs in request/status, header and body lines
without adjusting content length
* Add blanks before CRLFs in request/status line without adjusting
content length
* Add nulls before CRLFs in request/status line without adjusting
Content Length.
* Add blanks before CRLFs in header lines without adjusting Content
Length.
* Add nulls before CRLFs in header lines without adjusting Content
Length.
* Add blanks before CRLFs in body lines without adjusting content
length
* Add blanks before CRLFs in body lines and adjust Content Length.
* Add nulls before CRLFs in body lines without adjusting Content
Length.
* Add nulls before CRLFs in body lines and adjust Content Length.
* Remove CRLF after message body (if any) without adjusting Content
Length.
* Remove CRLF after message body (if any) and adjust Content
Length.
* Remove CR after message body (if any) without adjusting Content
Length.
* Remove CR after message body (if any) and adjust Content Length.
* Append a meaningless message body to 100/80 responses
* Insert blanks before colon on header field lines
* Insert tabs before colon on header field lines
* Insert blanks after colon on header field lines
* Insert tabs after colon on header field lines
* Remove whitespace after colon on header field lines
* Add trailing dot to DNS names found in request/status line and
message header
* Add trailing dot to DNS names found in request/status line
* Add trailing dot to DNS names found in From: header
* Add trailing dot to DNS names found in To: header
* Add trailing dot to DNS names found in Contact: header
* Remove the trailing dot (if any) in DNS names in request/status line
and message header.
* Remove the trailing dot (if any) in DNS names in request/status line.
* Remove the trailing dot (if any) in DNS names in From: header line.
* Remove the trailing dot (if any) in DNS names in To: header line.
* Remove the trailing dot (if any) in DNS names in Contact: header line.
* Insert extremely long but valid domain name in request/status line
and header lines
* Insert extremely long but valid domain name in request/status line.
* Insert extremely long but valid domain name in From: header line.
* Insert extremely long but valid domain name in To: header line.
* Insert extremely long but valid domain name in Contact: header line.
* Insert extremely long, invalid domain name in request/status line and
header lines
* Insert invalid domain name (with one extra byte ) in request/status line
* Insert invalid domain name (with one extra byte) in From: header line
* Insert invalid domain name (with one extra byte) in To: header line
* Insert invalid domain name (with one extra byte) in Contact: header
line
* Insert invalid domain name (with several extra bytes) in request/status
line and message header.
* Insert invalid domain name (with several extra bytes) in request/status
line

<p style="margin-top:2em;text-align:center;"><a href="/company/contact" class="btn btn-danger">Contact Us</a></p>

© Copyright 2018 InterWorking Labs, Inc. dba IWL. <br> 
Web: https://iwl.com <br> 
Phone: +1.831.460.7010 <br> 
Email: info@iwl.com