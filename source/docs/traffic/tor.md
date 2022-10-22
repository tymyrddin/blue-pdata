# Using Tor

Onion routing networks like the Tor network are designed to resist a local adversary, one that can only see a subset 
of the network and the traffic on it. In a [(sort of) mixnet](digital-mixing.md) like that, each node will only know 
the relay path in which it is involved, but not the whole path from the source to destination. If being discovered 
does not have serious consequences for you, we recommend using the 
[Tor Browser Bundle](https://www.torproject.org/download/).

## Warnings taken seriously

* If a government makes their own national internet, or routes traffic through specific servers to use deep packet inspection (DPI), running Tor may not provide security if the government is able to see the entire path. 
* Sometimes the Tor network is censored, and clients can't connect to it. An increasing number of censoring countries are using Deep Packet Inspection (DPI) to classify Internet traffic flows by protocol. While Tor uses bridge relays to get around a censor that blocks by IP address, the censor can use DPI to recognize and filter Tor traffic flows even when they connect to unexpected IP addresses. With pluggable transports, censorship against Tor can be bypassed.
* Not only that. If an attacker can see your traffic, and can see the website you're visiting, even with a path outside the adversary's control - they will still be able to correlate the traffic and learn you are visiting the website.
* If the same connection (the same set of relays) were to be used for a longer period of time a Tor connection could be vulnerable to statistical analysis, which is why the client software changes the entry node every ten minutes.

## Blocking Tor

Even the introduction of Bridge nodes did not stop certain organizations and governments from trying to detect and block the usage of Tor. The usual suspects for attempts at blocking Tor are:

* Blocking of the publicly available list of Tor relays.
* Creating Application Filter Policies in firewalls where only certain approved networks (LAN Networks) will be able to use specified proxy services.
* Creating an SSL Decryption policy in firewalls. IDS/IPS can be used to decrypt SSL certificates and detect traffic related to websites hosted on Tor.
* Tor browsing involves two types of ports, ORPort and DirPort. ORPorts (port 80 and 443) are used to make connections and transmissions and DirPorts (port 9001 and 9003) are used to fetch updates from the directory servers. Firewalls and IDS filters can be configured to monitor any traffic going towards or coming from the ports 9001 and 9003.

## Pluggable transports

Pluggable transports are tools that Tor can use to disguise the traffic it sends out. This can be useful in situations where an Internet Service Provider or other authority is actively blocking connections to the Tor network.

* `obfs3` makes Tor traffic look random, so that it does not look like Tor or any other protocol. While still included by default, it is recommended to use `obfs4` instead, as it has several security improvements over obfs3.
* `obfs4` makes Tor traffic look random like `obfs3`, and also prevents censors from finding bridges by Internet scanning. obfs4 bridges are less likely to be blocked than obfs3 bridges.
* FTE (format-transforming encryption) disguises Tor traffic as ordinary web (HTTP) traffic.
* meek transports all make it look like you are browsing a major web site instead of using Tor. meek-amazon makes it look like you are using Amazon Web Services; meek-azure makes it look like you are using a Microsoft web site; and meek-google makes it look like you are using Google search.
* Snowflake is an improvement upon Flashproxy. It sends your traffic through WebRTC, a peer-to-peer protocol with built-in NAT punching.

## Workstations and PC's

* [Linux: Use a Tor proxy](blue-linux:docs/services/tor-proxy)
* [macOS: Use a Tor proxy](blue-macos:docs/services/tor-proxy)
* [Windows: Use a Tor proxy](blue-windows:docs/services/tor-proxy)

## Phones

* [Android: Use a Tor proxy](blue-android:docs/services/tor-proxy)
* [iOS: Use a Tor proxy](blue-ios:docs/services/tor-proxy)