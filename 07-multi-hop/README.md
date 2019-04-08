Summary
=======

These tests check the multi-hop connectivity over IPv6.

Task #01 - ICMPv6 echo on iotlab-m3 with three hops (static route)
==================================================================
### Description

ICMPv6 echo request/reply exchange between two iotlab-m3 nodes over three hops
with static routes.

### Result

<20% packets lost on the pinging node.
No leaks in the packet buffer (check with `gnrc_pktbuf_cmd`).

Task #02 - UDP on iotlab-m3 with three hops (static route)
==========================================================
### Description

Sending UDP between two iotlab-m3 nodes over three hops with static routes.

### Result

<10% packets lost on the pinging node.
No leaks in the packet buffer (check with `gnrc_pktbuf_cmd`).

Task #03 - ICMPv6 echo on iotlab-m3 with three hops (RPL route)
===============================================================
### Description

ICMPv6 echo request/reply exchange between two iotlab-m3 nodes over three hops
with RPL generated routes.

### Result

<20% packets lost on the pinging node.
No leaks in the packet buffer (check with `gnrc_pktbuf_cmd`).

Task #04 - UDP on iotlab-m3 with three hops (RPL route)
=======================================================
### Description

Sending UDP between two iotlab-m3 nodes over three hops with RPL generated routes.

### Result

<10% packets lost on the pinging node.
No leaks in the packet buffer (check with `gnrc_pktbuf_cmd`).
