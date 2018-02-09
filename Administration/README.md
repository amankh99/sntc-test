For the **second problem**-

**Resources** - streisand github page, http://devops.host/blog/streisand-vpn.html, and I looked up for youtube on how to use aws services?

**Learning** - In readme, I found the terms like SSL, SHA-256 checksums which looked up, I, though little bit learnt to use amazon aws, what is aws iam, and also about different vpns, more about ssh, what are certificates file while trying to connect through vpn
and ofcourse how to make our own vpn.

**How to?**

Firstly I made account on amazon aws and then I followed the installation instructions for streisand on its github page, then I totally followed on how to use aws for creating vpn tutorial by devops(resource mentioned above) and also details provided by streisand.
Then it asked for the domain name I made it default then after installation it opened the streisand.html page which gave contains the ssl certificate to download, and also gave the link to new ip address which will the ip address of our machine after setting up of vpn, and its username and password.
So I logged into it provided me with connection options of vpns -

    L2TP/IPsec
    OpenConnect / Cisco AnyConnect
    OpenVPN (direct)
    OpenVPN (stunnel)
    Shadowsocks
    SSH
    Tor
    WireGuard

L2TP/IPsec was not good for linux, so I chose Openvpn(direct) but it pose the the problem when I downloaded multiple certificates file from the instructions given for Linux(Ubuntu) os, I was using firefox, also I've to configure firefox according the instructions given on streisand.html
So I selected OpenConnect and followed the instructions given for linux and I was successfully able to connect through vpn.
