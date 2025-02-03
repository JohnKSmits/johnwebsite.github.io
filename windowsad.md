---
layout: default
---

# Windows AD lab (2 labs)

# Lab 1

One lab was done on Azure cloud and I was tasked with creating GPOs to enforce different
policies that might be used in a company environment. I also created a script to list the ACLs
of all items in a directory.


![Account Policies](./images/Account-Lockout-Policies.jpg)

![Account Policies](./images/GPOs.jpg)

![Account Policies](./images/Windows-PowerShell-Policies.jpg)

# lab 2

For this lab I used virtual box and installed windows server 2019 for the DC and Windows 10 
for the hosts. I used the Domain Contoller(Windows 2019 Server) as the default gateway for all the hosts and
set up 2 NICs on the DC. So all the hosts are assigned addresses from the DC through DHCP. All the hosts can
connect to the internet through the DC with is connected to my PC with NAT.

![Account Policies](./images/WindowsADdomain.png)

![Account Policies](./images/MachineScreenshot.png)

![Account Policies](./images/DHCP.png)



I also used this script to create 1000 users to play with.


![Account Policies](./images/RunningUserScript.png)


