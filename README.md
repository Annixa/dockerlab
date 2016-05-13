# dockerlab 
# 🐳⚗=❤️
An easier way to develop and test your docker stacks.

# Purpose
If you have two stacks with similar configurations, chances are the port mappings will be the same as well. You *could* configure each stack to map to different ports on your host, but that would take a code change. If you didn't change the ports, you'd have a port collision on your host.

Dockerlab allows you to use the same host (or cluster of hosts) to spin up mini docker-in-docker environments for:
- Testing multiple versions of the same software stack
- Giving users the ability to spin up their own stack that don't normally have to ability to spin up new servers
- Cultivating your own private environment for testing the compatbility of different software stacks.


# Setup
TBD
