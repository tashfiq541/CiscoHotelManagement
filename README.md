
# Hotel System Network

Cisco Packet Tracer is used to build the whole network of this project.

## Case Study and Requirements

As a part of your end year networking project, you are required to design and implement Vic Modern Hotel network. The hotel has three floors; in the first floor there three departments (Reception, store and Logistics), in the second floor there are three departments (Finance, HR and Sales/Marketing), while the third floor hosts the IT and Admin. Therefore, the following are part of the considerations during the design and implementation;
There should be three routers connecting each floor (all placed in the server room in IT department).
All routers should be connected to each other using serial DCE cable.
The network between the routers should be 10.10.10.0/30,10.10.10.4/30 and 10.10.10.8/30.
Each floor is expected to have one switch (placed in the respective floor).
Each floor is expected to have WIFI networks connected to laptops and phones.
Each department is expected to have a printer.
Each department is expected to be in different VLAN with the following details;
1st Floor;
- Reception- VLAN 80, Network of 192.168.8.0/24
- Store- VLAN 70, Network of 192.168.7.0/24
- Logistics- VLAN 60, Network of 192.168.6.0/24
2nd Floor;
- Finance- VLAN 50, Network of 192.168.5.0/24
- HR- VLAN 40, Network of 192.168.4.0/24
- Sales- VLAN 30, Network of 192.168.3.0/24
3rd Floor;
- Admin- VLAN 20, Network of 192.168.2.0/24
- IT- VLAN 10, Network of 192.168.1.0/24

Use OSPF as the routing protocol to advertise routes.
All devices in the network are expected to obtain IP address dynamically with their respective router configured as the DHCP server.
All the devices in the network are expected to communicate with each other.
Configure SSH in all the routers for remote login.
In IT department, add PC called Test-PC to port fa0/1 and use it to test remote login.
Configure port security to IT-dept switch to allow only Test-PC to access port fa0/1 (use sticky method to obtain mac-address with violation mode of shutdown.)
## Technologies Implemented

1. Creating a network topology using Cisco Packet Tracer.
2. Hierarchical Network Design.
3. onnecting Networking devices with Correct cabling.
4. Creating VLANs and assigning ports VLAN numbers.
5. Subnetting and IP Addressing.
6. Configuring Inter-VLAN Routing (Router on a stick).
7. Configuring DHCP Server (Router as the DHCP Server).
8. Configuring WLAN or wireless network (Cisco Access Point).
9. Configuring OSPF as the routing protocol.
10. Host Device Configurations.
11. Test and Verifying Network Communication.
## Network Topology Created
![CiscoHotel](https://user-images.githubusercontent.com/69791359/233853733-91660b32-28bb-4eb5-8826-8cbc65eb3f6e.png)

