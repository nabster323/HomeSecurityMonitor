# HomeSecurityMonitor
Essentially scans the devices on your network and performs an action when that core list changes.

I made this project because I worry that someone might brute force my home network wireless key (perfectly possible) and I want to know about it.

**I am aware that if the clients (hackers in my scenario) are running a good firewall then the packets will be dropped. I hope to upgrade this in the future with something clever.**

I did consider automatically logging into to the router admin page and asking for the list of connected clients, but as my home router does not support HTTPS I don't want to risk a bearer token floating across in plain text. Or even worse the admin password during a request for the token being intercepted.

Plus, it was a great excuse to test .Net Core console app (using C#) running in Raspian on my older Raspberry Pi Model B.

The initial commit stores a list of devices that are known on the network and if it detecs anything odd, you provide it a thing to do in this event.

Please feel free to raise a PR.

To be continued....
