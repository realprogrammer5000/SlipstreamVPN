> [Go home](/)

# FAQ
## Technical & Troubleshooting
### The VPN refuses to connect or frequently disconnects.
Being disconnected once is likely due to a deploy of new server software or a temporary network disruption and should be infrequent and brief. It is also possible that our servers are blocked on your network. If the issue still occurs on a different network, our servers are probably undergoing maintenance and should be working soon. If you have further problems, [send us an email](contact-us).

### Chrome is giving me an error message: "The proxy at ... requires a username and password."
This is a temporary problem that is usually solved by dismissing the dialog, or failing that, disconnecting and reconnecting. It could also be a problem with your internet connection. If the problem persists, [send us an email](contact-us).

### Why do you need to "read and change all my data on the websites I visit"?
This is a message displayed by Chrome when we request the permissions we need for the extension to work. We have [a full explanation of the permissions we use](permissions) if you'd like to know more.

### Can someone who's snooping on my web traffic see what sites I'm accessing or that I'm using a VPN?
Nobody can see which sites you're accessing or what you're doing on them when you are connected to our VPN. We encrypt web traffic with the same protocol that encrypts HTTPS, so it looks like HTTPS traffic to most web filters and monitors. It is possible that someone would recognize the IP address of one of our servers as from us and therefore realize that you're using a VPN, so we cannot guarantee that nobody will know you are using a VPN.

### How secure are your servers? What happens if you're hacked?
We try our best to secure our servers using industry-standard technologies and best practices, although we cannot mention specifically how. All of your communications are encrypted with [Perfect Forward Secrecy](https://en.wikipedia.org/wiki/Forward_secrecy) as to ensure that even if someone records your encrypted communications and later steals a key from us, they cannot decrypt your past communications. If we become aware of a security breach, we will attempt to stop the attack as soon as possible and restore our services as soon as we can. We will inform you if such an attack occurs.

### Can I use SlipstreamVPN in Chrome's incognito mode?
Yes, but you'll need to give it permission to run in incognito mode. Click the extension icon, then click "Allow in incognito mode", and then follow the instructions shown. If no button appears, then you should already be good to go.

### Do you support IPv6?
Yes. Note that only our IPv4 address appears on the extension pop-up; this is for brevity and IPv6 is still supported if your network supports it.

### Do you leak my IP via WebRTC or DNS?
No.

### Where are your services hosted?
Our servers are hosted in New York City via DigitalOcean, with more locations coming soon!

### Can I use your VPN on Windows / MacOS / Linux / Android / iOS / whatever?
Likely not, but if you have a client that supports a PAC file / URL, you can try using the PAC URL available in the client. You will need to ensure that you have a valid token and username, and that your client supports HTTPS CONNECT proxies. Firefox works with this method.

## Throttling, Logging & Service Rules
###  Do you block or throttle traffic based on protocol or site? Are you torrent-friendly?
We don't care what you use our services for (HTTP, HTTPS, IMAP, SSH, FTP, BitTorrent, Minecraft, etc) as long as it is legal and not a violation of our [Terms of Service](tos). We will never block or throttle traffic that is not in violation of our [Terms of Service](tos), with the exception of our ad and tracker blocking and uniform throttling to the data/bandwidth limits of your plan. Note that "piracy" (infringement of copyright) is a violation of our terms of service and you assume full legal responsibility for all traffic originating from your account. 

### Do you log or sell my data? 
We do not log any traffic that follows our [Terms of Service](tos). We log how much data (in bytes) you've used every 30 seconds to enforce account data usage limits, but we do not log any other metadata about your traffic. We do not store historical data usage and your data usage counter is zeroed after the end of the month.

### Do you inject ads?
No. In fact, we block over 150,000 known ad and tracking sites. If an ad gets through, [send us an email](contact-us) with a link to the site and any other relevant information.

### Can I use your services to access illegal content?
No. See our [TOS](tos).

### Is there a limit on the number of simultaneous connections / devices per account?
No.

### I'm not getting to my plan's speed. Are your advertised speeds symmetrical?
On our end, we limit the speed of your network traffic to the speed of the plan that you have. We don't limit upload speeds differently from download speeds, although most consumer internet plans have much slower upload speeds, meaning your home internet connection might not be able to hit your plan's upload speed at all. If your internet connection is capable, you should be able to consistently hit at least your plan speeds on both upload and download tests. However, your ISP may still throttle the connection to us, and that may prevent you from reaching your plan speed. If you have specific performance concerns, [send us an email](contact-us). If you want faster plan speeds, [upgrade your plan](https://my.slipstreamvpn.tk).

## Account & Financial
### Why do you require a Google account to sign up? Can I sign up anonymously?
We require a Google account sign in to ensure that our services are not abused (eg. duplicate accounts, as burner emails are much easier to create and use than google accounts). We do not store or have access to any data associated with your google account except your name, email, and profile picture. This data is not connected with or cross-referenced with any of your web traffic.
If you would like to sign up with an email and password, [choose a paid plan](index#pricing) and [send us an email](contact-us). If you have special requirements for your account or would like an alternate or more anonymous form of login, [send us an email](contact-us).

### Can I pay with Bitcoin / Litecoin / Monero / Ethereum / gold / cattle?
[Send us an email](contact-us).

### How do you make money?
Donations, free trial credits from our webhost, and paid tiers support the free tiers entirely. Because of this, we do not attempt to make any money from our free plan. Because our free plan isn't profitable, we have to [limit them more aggressively than other plans](index#pricing) to ensure that they can stay free. If you'd like to donate to us, [send us an email](contact-us). 

### Can I get a discount?
We would love to offer you promotional / bulk discount codes. [Send us an email](contact-us).
