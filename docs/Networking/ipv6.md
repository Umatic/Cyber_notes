# Internet Protocol v6 ( IPv6 )

IPv6 is the latest version of the Internet Protocol (IP) and was designed to address the limitations of IPv4, such as the exhaustion of available IP addresses. IPv6 provides a much larger address space than IPv4, using 128-bit addresses instead of 32-bit addresses.

**Some key features of IPv6 include:**

* Larger address space: As mentioned, IPv6 uses 128-bit addresses, providing a much larger address space than IPv4.
* Simplified header: The IPv6 header is simplified compared to IPv4, with fewer fields and a fixed size of 40 bytes.
* Auto configuration: IPv6 allows for automatic address configuration using the Neighbor Discovery Protocol (NDP).
* Security: IPv6 includes support for IPSec, which provides authentication and encryption services for network traffic.
* Better support for mobile devices: IPv6 includes features such as Mobile IPv6, which enables mobile devices to m aintain a consistent IP address as they move from one network to another.

IPv6 addresses are expressed as eight groups of four hexadecimal digits, separated by colons (:). For example, an IPv6 address might look like: 2001:0db8:85a3:0000:0000:8a2e:0370:7334.
IPv6 also includes several different types of addresses, such as link-local addresses, site-local addresses, and global addresses, which are used for different purposes within a network.

### IPv6 Shortening

IPv6 addresses are expressed as eight groups of four hexadecimal digits, separated by colons, for example, "2001:0db8:0000:0000:0000:0000:0000:0001". However, this notation can be lengthy and cumbersome, especially when working with large networks. To make IPv6 addresses shorter and easier to read and type, a shorthand notation can be used.

**The shorthand notation consists of:**

* Eliminating any leading zeros in a group of four hexadecimal digits. For example, "0db8" can be shortened to "db8".
* Replacing one or more consecutive groups of zeros with a double colon "::". This can only be done once in an IPv6 address, as it would be ambiguous otherwise.

For example, consider the IPv6 address "fe80:0000:0000:0000:0202:b3ff:fe1e:0329". To shorten this address, we can use both techniques to get : "fe80::202:b3ff:fe1e:329".

Note that the shorthand notation can only be used to represent a full IPv6 address; it cannot be used for a subnet mask or any other network-related parameter.

### IPv6 address ranges

**Unicast Addresses:**

* Global Unicast Addresses: Used for communication on the global Internet. The first three bits of these addresses are set to 001, giving them a prefix of 2000::/3.
* Link-Local Unicast Addresses: Used for communication on a single network segment. These addresses have a prefix of fe80::/10.
* Unique Local Unicast Addresses: Similar to private IPv4 addresses, these addresses are used for communication within an organization or between organizations with a trusted relationship. They have a prefix of fc00::/7.
* Compatible IPv4-mapped Addresses: Used for mapping IPv4 addresses to IPv6 addresses. These addresses have a prefix of ::ffff:0:0/96.

**Multicast Addresses:**

* All-nodes multicast address: Used to send traffic to all nodes on a network segment. The address is ff01::
* Solicited-node multicast address: Used for neighbor discovery in IPv6. The last 24 bits of the address are derived from the lower 24 bits of a node's unicast address. The prefix for these addresses is ff02::1:ff00:0/104.
* Node-Information multicast address: Used for IPv6 stateless address auto configuration. The prefix for these addresses is ff02::1:ff00:2/104.
* Multicast addresses for routing protocols: Used by routing protocols for communication between routers. These addresses have a prefix of ff0X::/8 (where X represents the specific routing protocol).

**Anycast Addresses:**

* Global Anycast Addresses: Used for communication with any one of a group of nodes that share the same anycast address. These addresses have a prefix of 2000::/3.
* Link-Local Anycast Addresses: Used for communication with any one of a group of nodes on the same network segment. These addresses have a prefix of fe80::/10.

**Special Addresses:**

* Unspecified Address: Used to represent the absence of an address. This address is ::.
* Loopback Address: Used for local communication within a single node. This address is ::1.
* IPv4-mapped Addresses: Used for mapping IPv4 addresses to IPv6 addresses. These addresses have a prefix of ::ffff:0:0/96.
* IPv4-translated Addresses: Used for translating between IPv4 and IPv6 addresses. These addresses have a prefix of ::ffff:0:0:0/96
