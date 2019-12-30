# NOTES

**Virtual Private Cloud (VPC):** networks connect your Google Cloud platform resources to each other and to the internet. 
- Global Scope: subnets in any GCP region worldwide and subnets can span the zones that make up a region
- Segment Network
- Firewall rules to restrict access to instances, and create static routes to forward traffic to specific destinations.
- Have resources in different zones on the same subnet.
- Dynamically increase the size of a subnet in a custom network by expanding the range of IP addresses allocated to it.
- Supports several different kinds of load balancing
- Forward traffic from one instance to another instance within the same network, even across sub-networks and even
between GCP zones without requiring an external IP address.
- VPCs routing tables are built in, you don't have to provision or manage a router.
- Routing tables are built in, you don't have to provision or manage a router
- Provides global distributed firewall

**Compute Engine:** lets you create and run virtual machines (VM) on Google infrastructure. It's advantageous to create
virtual machines from a command line when you want their configurations to be scripted and repeatable. 
- Allows to manage the VM machines by picking their own CPU, Memory and GPU
- Two type of disk memory: standard (Hard Disk) and SSD. 
- Local SSDs can be attached as well; however, ```Local SSDs content doesn't last past when the VM terminates.```
- Boot image: Linux or Windows
- 

**Cloud Load Balancing:** is a fully distributed, software-defined managed service for all your traffic.
- Load balancers don't run in VMs you have to manage, you don't have to worry about scaling or managing them
- You can put Cloud Load Balancing in front of all your traffic - HTTP and HTTPS, other TCP and SSL traffic, and UDP traffic
- User get a single anycast IP frontends all your backend instances in regions around the world.
- It provides cross-region load balancing, including automatic multi-region failover, 
which gently moves traffic in fractions if backends become unhealthy.
- Backends are selected based on load
- Only healthy backends receive traffic
- No pre-warning is required
- Reacts quickly to changes in users, traffic, backend health, network conditions, and other related conditions.

**Scale Out:** 

**Scale Up:** 

**DNS 8.8.8.8:** One of the most famous Google services that people don't pay for which provides a public domain name 
service to the world. DNS is what translates internet host names to addresses. And as you would imagine, Google has a 
highly developed DNS infrastructure. It makes 8.8.8.8 available so that everybody can take advantage of it.
- Cloud DNS is also programmable. You can publish and manage millions of DNS zones and records using the GCP console, 
the command line interface or the API.

Many customers start with a Virtual Private Network connection over the internet using the IPSEC protocol. 
To make that dynamic, they use a GCP feature called Cloud Router.

**Cloud Router:** lets your other networks and your Google VPC exchange route information over the VPN using the
Border Gateway Protocol. For instance, if you add a new subnet to your Google VPC, your on-premises network will automatically
get routes to it. But some customers don't want to use the internet, either because of security concerns or because they 
need more reliable bandwidth. They can consider peering with Google using Direct Peering.

**Peering:** means putting a router in the same public data center as a Google point of presence and exchanging traffic. 






