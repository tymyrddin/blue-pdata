# DNS leaks

![Leaky boat](../../_static/images/leaky-boat.png)

When you don’t set up DNS servers on your computer or router, your DNS queries will run on your ISP’s DNS servers. Without VPN (or [VPN Fails Open](vpn-fail-open.md)), DNS requests are most likely sent unencrypted, which can lead to many different types of common DNS attacks. 

* Domain hijacking (Redirection)
* DNS flood attack (a type of DDoS attack) 
* DNS spoofing or DNS cache poisoning
* DNS hijacking (malware infection on a local device to hijack DNS to redirect traffic to a phishing site)

And any man in the middle of your traffic can see your online behaviour and the websites you visit. Your ISP’s DNS servers see every search you make in your browser. 

Using your ISP’s DNS servers as default DNS servers doesn’t do anything for security or privacy.

## Workstations and PC's

* [Linux: Use alternative DNS servers](blue-linux:docs/services/dns-servers)
* [Windows:Use alternative DNS servers](blue-windows:docs/services/dns-servers)
* [macOS: Use alternative DNS servers](blue-macos:docs/services/dns-servers)


