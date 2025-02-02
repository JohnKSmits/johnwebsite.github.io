---
layout: default
---
# Honeypot Lab(TPot)
[Tpot readme](https://github.com/telekom-security/tpotce/blob/master/README.md)

#What I used for this lab
For this lab I set up an account with linode, I didn't want to put a vulnerable system on my home internet.
I decided to spin up the vm in Cali as those IP's tend to get more attacks. There are multiple compatable 
linux distros to use for this lab but I chose debian 11. It's easy to set up the Tpot git hub readme
has the intructions for install installing the docker containers, sensors, and IDS. The install script
automatically sets the ssh, and web server to a different port. That way the honeypots can use the common
ports. My firewall originally had deny all except for ssh from my ip, I changed the firewall to allow
all inbound connections to the honeypot except for the ssh, and web server ports that I connect to
with my IP. Once I was finished I can now anylize and mointor all attacks on my honeypot. This was the
result just after a couple hours.

