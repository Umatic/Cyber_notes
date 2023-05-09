# Internet Protocol v4 ( IPv4 )

IPv4, or Internet Protocol version 4, is the fourth iteration of the Internet Protocol (IP) and is still the most widely used version of the IP protocol. IPv4 uses a 32-bit address space, allowing for up to 4.3 billion unique addresses, although due to the rapid expansion of the internet, the number of available addresses is rapidly depleting.

IPv4 addresses are typically represented in dotted decimal notation, which separates the address into four 8-bit segments and represents each segment as a decimal number between 0 and 255. An example of an IPv4 address in dotted decimal notation is 192.168.0.1.

IPv4 provides the foundation for most internet communication and is used to route data packets between devices on the internet. Despite its widespread use, IPv4 is being gradually replaced by IPv6, which uses a 128-bit address space and provides a significantly larger number of unique addresses to accommodate the growing number of internet-connected devices.

### IPv4 address ranges

**Private IPv4 addresses:**

* 10.0.0.0/8, which includes all addresses from 10.0.0.0 to 10.255.255.255
* 172.16.0.0/12, which includes all addresses from 172.16.0.0 to 172.31.255.255
* 192.168.0.0/16, which includes all addresses from 192.168.0.0 to 192.168.255.255

**Public IPv4 addresses:**

* Class A: 1.0.0.0 to 126.0.0.0
* Class B: 128.0.0.0 to 191.255.0.0
* Class C: 192.0.0.0 to 223.255.255.0
* Class D: 224.0.0.0 to 239.255.255.255 (used for multicast addresses)
* Class E: 240.0.0.0 to 255.255.255.255 (reserved for future use)

**Multicast Addresses:**

* 224.0.0.0 to 239.255.255.255 are used for broadcasting to many devices on a network segment but not all.

**Broadcast Address:**

* 255.255.255.255 is used for broadcasting to all devices on a network segment.

**Invalid or Unknown Target Address:**

* 0.0.0.0 indicates the client isn't connected to a TCP/IP network or is offline.

**Loopback Address:**

* The loopback address is a special address used to test network software without actually sending data over the network. The IPv4 loopback address is 127.0.0.1, and it is reserved for internal loopback use. Any traffic sent to this address is looped back to the source computer.

**Automatic Private IP Addressing (APIPA):**

* 169.254.0.0/16 is reserved for APIPA and is used when a DHCP server is not available to assign an IP address to a device.
