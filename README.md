Brief Description of the Topology and Configuration of the Network 

This network is comprised of fourteen devices, including two Cisco Catalyst 
2960S switches, six Cisco routers, four computers, a firewall, and a cloud. The 
Cisco routers establish connections between the two switches, while the switches 
link to the four computers. Additionally, the switches connect to a firewall, which 
is in turn connected to a cloud. Routing information within the network is 
exchanged using both the Enhanced Interior Gateway Routing Protocol (EIGRP) 
and Open Shortest Path First (OSPF). Furthermore, the network incorporates 
Virtual LANs (VLANs) for efficient network segmentation. 

![image](https://github.com/user-attachments/assets/9081f8c2-6bc4-42af-8467-d21c03eaf50c)


Configuration Description 
• The Cisco routers are configured with EIGRP to exchange routing 
information. 
• The computers are configured with IP addresses and default gateways.
FortiGate Configuration
![image](https://github.com/user-attachments/assets/5df8a6f8-9ae5-4fdb-8ff9-5000a347d4e2)

![image](https://github.com/user-attachments/assets/857a5f98-087b-4705-b155-15e277847a76)

![image](https://github.com/user-attachments/assets/774b14fa-7c0d-426f-8027-30fb75ce5381)

![image](https://github.com/user-attachments/assets/ffcc0cee-3497-4f60-ab1d-80d1dffea452)

![image](https://github.com/user-attachments/assets/98c9485a-285e-4769-b320-478e4108faea)

Router Configuration

Router 1

![image](https://github.com/user-attachments/assets/f5078153-c6b7-4691-af91-857972b3b7b1)

![image](https://github.com/user-attachments/assets/2b7ef382-9843-483b-a411-3550690a3de3)

Router 2

![image](https://github.com/user-attachments/assets/d88b89b5-424c-484a-abad-a06156539a43)

![image](https://github.com/user-attachments/assets/7097897e-1908-42fe-aaf0-3a3eec705287)

Router 3

![image](https://github.com/user-attachments/assets/8a92076e-d3a1-4b8c-a049-411425a9344a)

![image](https://github.com/user-attachments/assets/6083cfff-5060-416c-954f-f8b9ec76637f)

Router 4

![image](https://github.com/user-attachments/assets/29285ac6-781f-4f60-a418-59bc18171e1d)

Router 5 

![image](https://github.com/user-attachments/assets/1716ef8b-78e7-46ad-92e4-c1fff4570c83)

Router 6

![image](https://github.com/user-attachments/assets/5df2777d-a7b0-409f-90b2-bfa75bb454fa)

L2 Switch 1 

![image](https://github.com/user-attachments/assets/be4d1736-ad40-4b7b-bb86-61fb6502421b)

L2 Switch 2

![image](https://github.com/user-attachments/assets/76c8a1a5-4742-481a-a3ed-fa6a0040e101)

- EIGRP routing protocol - Used between distribution routers R4/R5/R6
  
-  Route redistribution configured between EIGRP and OSPF

-  -Firewall 
- Applied a policy to allow all traffic via HTTP/HTTPS.
   
Inter-VLAN Routing: 

• Inter-VLAN routing is the ability to route traffic between virtual local area 
networks (VLANs). VLANs are used to segment a network into smaller, 
more manageable broadcast domains. This can help to improve network 
security, performance, and manageability. 

• Inter-VLAN routing typically requires a router or a Layer 3 switch. The 
router or switch acts as a gateway between the VLANs, forwarding traffic 
from one VLAN to another. This is done by assigning an IP address to 
each VLAN and configuring the router or switch with routing tables that 
map IP addresses to VLANs. 
Star Topology: 

In networking, a star topology is a configuration where all devices are connected 
to a central hub or switch. Each device in the network has its own dedicated 
connection to the central hub, forming a shape that resembles a star. 


Trunking: 

• Trunking is a method of carrying multiple VLANs over a single Ethernet 
link. This is done by using a trunking protocol, such as IEEE 802.1Q, to 
tag each frame with the VLAN ID of the VLAN to which it belongs. 


• Trunking is a popular way to connect Layer 2 switches together in a large 
network. It allows for the efficient use of bandwidth and simplifies network 
management.








