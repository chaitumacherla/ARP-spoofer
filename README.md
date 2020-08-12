In this project, we will try to become man in the  middle by using ARP spoofing.

Here, we will exploit the user using ARP protocol


Here we will send a fake ARP response to the router and target client by fooling them by giving our MAC addresses instead of each other MAC addresses.After becoming man in the middle, then every request sent by the target clinet to the router will pass through our computer.

After executing this attack, we will again take back all the conditions to normal by updating the ARP table using restore function. 

The second part of this project is writing an ARP spoof detector which detects the arp spoofing.

There are many ways to write the arp spoof detector. The way which is used in this project is by filtering out the all the ARP responses and analysing them whether it is prone to arp spoofing or not.

