# HomeSecurityMonitor
Essentially scans the devices on your network and performs an action when that core list changes.

I made this project because I worry that someone might brute force my home network wireless key (perfectly possible) and I want to know about it.

Plus, it was a great excuse to test .Net Core console app (using C#) running in Raspian on my older Raspberry Pi Model B.

The initial commit stores a list of devices that are known on the network and if it detecs anything odd, you provide it a thing to do in this event.

Please feel free to raise a PR.

To be continued....
