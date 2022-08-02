# SSH tunnels explained

Secure Shell (SSH) can be used to securely acquire and use a remote terminal session and has other uses as well. 
You can use SSH to tunnel traffic, transfer files, mount remote file systems, and more. SSH also uses strong encryption 
and you can set your SSH client to act as a Socks proxy. Once you have, you can configure applications on your 
computer – such as your web browser – to use the Socks proxy. The traffic enters the Socks proxy running on your local 
system and the SSH client forwards it through the SSH connection – this is known as SSH tunneling. This works similar 
to browsing the web over a Virtual Private Network (VPN). From a web server perspective, traffic appears to be coming 
from the SSH server. The traffic between source and the SSH server is encrypted, so you can browse over an encrypted 
connection as you could with a VPN. You must configure each application to use the SSH tunnel’s proxy.

SSH tunnels can be created in several ways using different kinds of port forwarding mechanisms. See examples in 

## Workstations and PC's

* [Linux: Use ssh tunnels](linux-pc-mitigations:docs/services/ssh)
* [macOS: Use ssh tunnels](macos-mitigations:docs/services/ssh)
* [Windows: Use ssh tunnels](windows-pc-mitigations:docs/services/ssh)

## Phones

* [Android: Use ssh tunnels](android-mitigations:docs/services/ssh)
* [iOS: Use ssh tunnels](ios-mitigations:docs/services/ssh)

 



