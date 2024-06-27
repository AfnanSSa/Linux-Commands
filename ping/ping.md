## `ping` Command
`ping` tests the reachability of a host on a network using the Internet Control Message Protocol (ICMP).
### Usage 
    $ ping [options] host_or_IP_address
### Commonly Used Options
`-c <count>`: specifies the number of ICMP echo requests to send (default is infinite until manually stopped).

`-i <interval>`: sets the interval in seconds between sending each ICMP echo request (default is 1 second).

`-w <deadline>`: specifies a timeout in seconds after which ping stops sending ICMP echo requests.

`-s <size>`: sets the size of the ICMP echo request packet (default is 56 bytes, including 8 bytes of ICMP header data).

`-q`: quiets output; only display summary statistics at the end.

`-v`: verbose output; display detailed information for each ICMP echo reply.