# Ports and Protocols

Ports (also known as sockets) are address numbers that are used to establish a communication link between two systems for the transfer of data. They enable a single IP address to support multiple simultaneous communications each using a different port number.

### Port Types

**There are three types of ports in the TCP/IP model:**

* Well-known ports (0-1023): are used for common protocols such as DNS and SMTP.
* Registered ports (1024-49151):  are associated with proprietary applications and are officially approved by IANA, but vendors may implement their own port numbers.
* Dynamic or private ports (49152-65535): are used for session-specific services and are assigned dynamically by the system.

### Insecure Protocol Ports

These ports are referred to as insecure because the protocols that use them transmit data in plain text by default. In other words, anyone who can intercept the network traffic can read and modify the data that is transmitted over these ports.

### Secure Protocol Ports

These protocols use encryption to protect the data transmitted over the network, making it much more difficult for an attacker to intercept and read the data.

<div style="display: flex;">
    <div style="flex: 1; margin-right: 20px;">
        <p><b>Most Common Insecure Protocol Ports:</b></p>
        <table>
    <tr>
        <td><b>Protocol</b></td>
        <td><b>Port</b></td>
    </tr>
    <tr>
        <td>FTP (File Transfer Protocol)</td>
        <td>Port 20 (data) &lt;br&gt; Port 21 (control)</td>
    </tr>
    <tr>
        <td>Telnet</td>
        <td>Port 23</td>
    </tr>
    <tr>
        <td>SMTP (Simple Mail Transfer Protocol)</td>
        <td>Port 25</td>
    </tr>
    <tr>
        <td>HTTP (Hypertext Transfer Protocol)</td>
        <td>Port 80</td>
    </tr>
    <tr>
        <td>POP3 (Post Office Protocol version 3)</td>
        <td>Port 110</td>
    </tr>
    <tr>
        <td>IMAP (Internet Message Access Protocol)</td>
        <td>Port 143</td>
    </tr>
    <tr>
        <td>SNMP (Simple Network Management Protocol)</td>
        <td>Port 161</td>
    </tr>
    <tr>
        <td>NetBIOS (Network Basic Input/Output System)</td>
        <td>Ports 137-139</td>
    </tr>
    <tr>
        <td>SMB (Server Message Block)</td>
        <td>Port 445</td>
    </tr>
    <tr>
        <td>RDP (Remote Desktop Protocol)</td>
        <td>Port 3389</td>
    </tr>
    <tr>
        <td>DNS (Domain Name System)</td>
        <td>Port 53</td>
    </tr>
    <tr>
        <td>LDAP (Lightweight Directory Access Protocol)</td>
        <td>Port  389</td>
    </tr>
</table>
    </div>
    <div style="flex: 1; margin-left: 20px;">
        <p><b>Most Common Secure Protocol Ports:</b></p>
        <table>
    <tr>
        <td><b>Protocol<b></td>
        <td><b>Port</b></td>
    </tr>
    <tr>
        <td>SSH (Secure Shell)</td>
        <td>port 22</td>
    </tr>
    <tr>
        <td>HTTPS (HTTP over SSL/TLS)</td>
        <td>port 443</td>
    </tr>
    <tr>
        <td>FTPS (FTP over SSL/TLS)</td>
        <td>port 990</td>
    </tr>
    <tr>
        <td>SMTPS (SMTP over SSL/TLS)</td>
        <td>port 465</td>
    </tr>
    <tr>
        <td>IMAPS (IMAP over SSL/TLS)</td>
        <td>port 993</td>
    </tr>
    <tr>
        <td>POP3S (POP3 over SSL/TLS)</td>
        <td>port 995</td>
    </tr>
    <tr>
        <td>LDAPS (LDAP over SSL/TLS)</td>
        <td>port 636</td>
    </tr>
    <tr>
        <td>SFTP (Secure FTP)</td>
        <td>port 22 (uses SSH)</td>
    </tr>
    <tr>
        <td>NFS (Network File System)</td>
        <td>Port 2049</td>
    </tr>
    <tr>
        <td>NTP (Network Time Protocol)</td>
        <td>Port 123</td>
    </tr>
    <tr>
        <td>DOT (DNS Over TLS)</td>
        <td>Port 853</td>
    </tr>
</table>
    </div>
</div>