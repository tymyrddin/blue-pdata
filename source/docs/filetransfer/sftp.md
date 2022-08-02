# Uploading files to a server

FTP is an insecure protocol in the sense that it sends your credentials in plain text to the server. Do not use.

Secure File Transfer Protocol (SFTP) solves this problem by using the underlying [SSH tunnel](../traffic/ssh.md) to 
transfer files. This ensures that all the traffic - credentials, server commands and files - are encrypted before 
sending. Since an intercepting computer hasn't got the encryption key, it can know nothing about the data transferred. 
But, your ssh host key can be used to fingerprint you by connecting to port 22 of your IP to verify that you are using 
the same machine as some other previous IP, either at your ISP or over VPN, so do not use it for distributing 
unauthorised content.

And, you can additionally, protect SSH with MFA.

* [How To Set Up Multi-Factor Authentication for SSH on Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-multi-factor-authentication-for-ssh-on-ubuntu-20-04)
* [SSH but make it Tailscale](https://tailscale.com/tailscale-ssh/) - Mac, iOS, Windows, Android or Linux, Raspberry Pi. Free for personal use on up to 20 devices.


