# Static Routing Configuration
# Abstract

Configure Static Routing:
To configure static routing on a Cisco router, you would use the ip route command followed by the destination network, subnet mask, and either the next hop IP address or the exit interface through which the network is reached.

Example:
Router(config)# ip route 192.168.1.0 255.255.255.0 192.168.12.2
This command instructs the router that any traffic destined for the network 192.168.1.0/24 should be forwarded to the next hop IP address 192.168.12.2.

View Routing Table:
To view the routing table on a Cisco router, you would use the show ip route command. This command displays the router's current routing table, including all known networks and their associated next hops or exit interfaces.

Example:
Router# show ip route
This command displays the router's routing table, showing the list of directly connected networks as well as any networks learned through dynamic routing protocols or configured via static routes.
