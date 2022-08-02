# Tunnelling 

A tunnel is a mechanism used to ship a foreign protocol across a network that normally wouldn't support it. 
Tunnelling enables the encapsulation of a packet from one type of protocol within the datagram of a different protocol. 
The complete IP packet to be sent from source to destination is encapsulated into another IP packet. This new packet 
has a legal internet IP address. For example, a VPN can use PPTP to encapsulate IP packets over a public network, 
such as the Internet. Most tunnelling protocols operate at layer 4, which means they are implemented as a protocol 
that replaces something like TCP or UDP. This concept can be used for anonymising.

Various types of tunnelling are useful for [circumventing censorship](../Circumventing-censorship.md): 

* [SSH](ssh.md) and [VPN](vpn.md), 
* [Mixnets](digital-mixing.md) like [Tor](tor.md) and [I2P](i2p.md)
* [Chaining anonymising gateways](chaining.md).

