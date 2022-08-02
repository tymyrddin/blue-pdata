# VPN Fail open

If you simply add a VPN using common instructions, it generally "fails open". That means, if the VPN breaks down, 
because the connection is interrupted, traffic will be sent without the VPN. It is much safer when it "fails closed", 
meaning that when the VPN connection breaks down, the whole internet connection must be down as long as the VPN 
connection is not restored. 

If your [chosen VPN](linux-pc-mitigations:docs/services/vpn) does not include being able to 
set a kill switch, you can use a firewall as a VPN fail-safe mechanism, or routes.

## Workstations and PC's

* [Linux: Use a firewall as a VPN fail-safe mechanism](linux-pc-mitigations:docs/services/vpn-fail-open)
* [macOS: Use a firewall as a VPN fail-safe mechanism](macos-mitigations:docs/services/vpn-fail-open)
* [Windows: Make a VPN killswitch using routes](windows-pc-mitigations:docs/services/vpn-fail-open)

