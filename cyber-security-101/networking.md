Good revision of Networking so far. Studied Computer Networks @ uni (Spring 2026)

Talks about ths ISO OSI (Open Systems Interconnection) model.
- learned a good way to remember it - Please Do Not Throw Spanish Pizza Away (Physical -> Data -> Network -> Transport -> Session -> Presentation -> Application layers)
- Physical: actual physical connection, Ethernet, optic, wireless etc.
- Data: On the same network using MAC addresses (6 bytes where the first three represent the vendor and the last three are the unique address on the network)
- Network: Across networks, this is where logical addressing and routing come in (IP, ICMP, VPN, IPSec etc.)
- Transport: enables connection b/w running applications on different hosts (TCP, UDP)
- Session: this layer is responsible for establishing and maintaining a connection, as well as ensuring synchronization between different hosts. This can mean establishing correct parameters and protocols prior to connection and sending bytes in the correct order to maintain data integrity
- Presentation: ensures data is delivered in a format the application can understand by handling encoding, encryption and compression
- Application: provides services like HTML, POP3, DNS

TCP/IP model (Transmission Control Protocol/Internet Protocol): developed by the Department of Defense in the 70s, it keeps the network functional even if parts of the network are down due to routing protocols implemented within the topology.
-ipconfig on Windows systems, ifconfig on Linux systems OR ip a s
reminder of IP addresses, in this case IPv4 addresses - 4 octets that each represent a decimal number b/w 0-255. And also, <ins>subnet masks</ins> that can be used to identify what part of an address is the same for all hosts on the network (255.255.255.0 can also be written as /24 indicating 24 bits of the 32 are the same(
reminder of Network Address Translation(NAT) which lends a public IP to a host from a private network (private IP)
private IPs: 
10/8 meaning 10.0.0.0
172.16/12 meaning 172.16.0.0
192.168/16 meaning 192.168.0.0

