# Change MAC address

A MAC address identifies the device connected to a network and allows the network to track, restrict or allow access 
based on it. Routers identify and assign static IP addresses based on the MAC addresses of devices. Before you try to 
change the MAC address, you need to know the value that you want to use.

Set the 2's place bit (the "locally administered" bit) in the first byte, to differentiate it from a guaranteed 
globally unique MAC address. Usually the first three bytes an unicast MAC address is an 
"Organizationally Unique Identifier" (OUI) that the IEEE assigned to the manufacturer of your Ethernet device. 
Manufacturers are required to make sure they keep the last 3 bytes unique. 

Avoiding all of that knowledge, the [MAC address generator tool](https://miniwebtool.com/mac-address-generator/) can 
generate a valid address for you.

## Workstations and PC's

* [Linux: Change MAC Address](linux-pc-mitigations:docs/services/change-mac)
* [macOS: Change MAC Address](macos-mitigations:docs/services/change-mac)
* [Windows: Change MAC Address](windows-pc-mitigations:docs/services/change-mac)

## Phones

* [Android: Change MAC Address](android-mitigations:docs/services/change-mac)
* [iOS: Change MAC Address](ios-mitigations:docs/services/change-mac)