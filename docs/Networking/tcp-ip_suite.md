# TCP/IP Protocol Suite

### Application Layer

* **Hypertext Transfer Protocol (HTTP):** This is the protocol used for transmitting data over the World Wide Web. It enables web browsers and servers to communicate with each other. HTTP is used to request web pages, images, and other resources from servers, and to send data to servers.
* **File Transfer Protocol (FTP):** FTP is a protocol used for transferring files between computers. It allows users to upload and download files to and from remote servers. FTP uses two separate channels for communication: a control channel for sending commands and responses, and a data channel for transmitting files.
* **Simple Mail Transfer Protocol (SMTP):** SMTP is a protocol used for sending email. It defines the way email clients and servers communicate with each other. SMTP is used to send email messages from clients to servers, and from servers to other servers.
* **Domain Name System (DNS):** DNS is a protocol used to convert domain names into IP addresses. It enables clients to resolve domain names to IP addresses. DNS servers maintain a database of domain names and IP addresses, and respond to queries from clients to resolve domain names.
* **Telnet:** Telnet is a protocol used for remote terminal access. It allows users to connect to remote servers and access their command line interface. Telnet transmits commands and responses between the client and server in plain text.

### Transport Layer

* **Transmission Control Protocol (TCP):** TCP is a full-duplex connection-oriented protocol that provides reliable and ordered delivery of data between applications. It ensures that data is received in the correct order and retransmits any lost or corrupted packets. TCP uses a three-way handshake to establish a connection and a four-way handshake to terminate a connection. It also provides flow control by regulating the rate at which data is sent.
* **User Datagram Protocol (UDP):** UDP is a connectionless protocol that provides unreliable and unordered delivery of data between applications. It does not guarantee delivery of data or check for errors. UDP is used when speed is more important than reliability, such as in streaming audio or video. Applications that use UDP must implement their own error checking and retransmission mechanisms.

### Internet Layer

* **Internet Protocol (IP):** IP is a connectionless protocol that provides unreliable delivery of data between hosts. It is responsible for routing packets from the source to the destination using the best available path. IP addresses are used to identify hosts on a network and determine the routing path for data transmission.
* **Internet Control Message Protocol (ICMP):** ICMP is used by network devices to communicate error messages, such as when a packet cannot reach its destination. ICMP messages are also used for troubleshooting purposes, such as testing connectivity between two hosts or determining the path that packets take between hosts.
* **Internet Group Management Protocol (IGMP):** IGMP is used by hosts to report their multicast group membership to multicast routers. Multicast allows one-to-many communication, where a single packet can be sent to multiple hosts at the same time. IGMP ensures that multicast packets are delivered only to hosts that have requested them.

### Network Access Layer

* **Ethernet:** Ethernet is a widely used LAN technology that provides a common standard for transmitting data over a wired network. It defines the format of the data frame, including the source and destination MAC addresses, the length of the data, and the type of protocol being used.
* **Wi-Fi:** Wi-Fi is a wireless networking technology that provides access to the physical transmission medium for wireless devices. It defines the format of the data frame, including the source and destination MAC addresses, the length of the data, and the type of protocol being used.
* **Token Ring:** Token Ring is a LAN technology that uses a token-passing mechanism to control access to the transmission medium. It defines the format of the data frame, including the source and destination MAC addresses, the length of the data, and the type of protocol being used.
* **FDDI:** Fiber Distributed Data Interface (FDDI) is a LAN technology that uses a dual-ring architecture to provide high-speed data transmission over optical fiber cables. It defines the format of the data frame, including the source and destination MAC addresses, the length of the data, and the type of protocol being used.
* **Point-to-Point Protocol (PPP):** PPP is a protocol used to establish a direct connection between two nodes over a serial connection. It defines the format of the data frame, including the source and destination MAC addresses, the length of the data, and the type of protocol being used.
* **Asynchronous Transfer Mode (ATM):** ATM is a WAN technology that uses a cell-based architecture to provide high-speed data transmission over a network. It defines the format of the data cell, including the source and destination addresses, the length of the data, and the type of protocol being used.
