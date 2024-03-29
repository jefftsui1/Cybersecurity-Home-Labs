# Network Types

## Peer-to-peer

Messer
- All devices are both clients and servers.
  - Everyone talks to everyone.
- Advantages: Easy to deploy and low cost.
- Disadvantage: Difficult to administer and difficult to secure.

<img width="412" alt="image" src="https://github.com/jefftsui1/Cybersecurity-Home-Labs/assets/46698661/eb42915c-3417-49dd-a8d1-7b625d081658">

Dion
- Peers shares resources (files/printers) direcrtly with others.
- Advantages: Lower Cost, No dedicated resources, No specialized OS.
- Disadvantages: Decentralized management, inefficient for large networks, horrible scalability.

#

## Client Server 

Messer 
- Central server
  - Client talk to the server
- Responsiblities are split.
  - Have individual clients and a centralized server.
- Clients are not communicating with each other directory.
  - Clients talk to servers, server talks to the clients.
- Advantages: Good performance, administration.
- Disadvantages: Costly and complexity.
 
<img width="342" alt="image" src="https://github.com/jefftsui1/Cybersecurity-Home-Labs/assets/46698661/4732fee8-0195-4d00-b728-27d70ec23e81">

Dion
- Client: A device used by an end user to access the network.
  - Can be: Workstation, laptop, tablet, smartphone, smart TV, server, other terminal devices.
- Server: A device that provides resources to the rest of the network.
  - Different servers provides different functions.
- Client/Server Model: Uses a dedicated server to provide access to files, scanners, printers and other resources.
- Makes this model one of the main choices for business network.
- Advantages: Centralized administration, easy management, better scalability.
- Disadvantages: Higher Cost, Requires dedicated resources, Specialized in Different OS.


#

## LAN

Messer
-  LAN = Local Area Network
  - Local is relative
- A building or group of building (High speed connectivity)
- Uses Ethernet or 802.11 Wireless
  - Any slower is not local.

Dion
- Connects components within a limited distance. (100 meters/ 300 ft)
  - Each segement can go about 100m with CAT 5 cabling.
- Think: Small office or one floor of an office building.

Ethernet = IEEE 802.3
Wi-Fi = IEEE 802.11
 
#

## MAN

Messer 
- MAN = Metropolitan Area Network
  - A network in your city.
  - Larger than a LAN but often smaller than a WAN.
- Metro Ethernet.
- Common to see government ownership
  - They own the right of way.
 
Dion
- Connects scattered locations across a city or metro area.
- Cover up to about 25 miles.
- Example: Police departments, could have a lot of locations across cities, but all connected together to form a MAN.
 
#

## WAN

Messer 
- WAN = Wide Area Network
  - Spanning the globe
- Generally connects LANs across a distance.
  - Generally much slower than the LAN.
- Point-to-point serial, MPLs, Satellite
- Terrestrial (Earth bound) and Non-Terrestrial (Space).

Dion
- Connects grographically disparate internal networks and consists of leasesd line or VPN.
- Cover across your states, country, or even across the world.
- Example: Internet is WAN, Connecting an office at CA and NY can use WAN.

<img width="346" alt="image" src="https://github.com/jefftsui1/Cybersecurity-Home-Labs/assets/46698661/2475f29c-1ba7-4b79-9577-055a26b04e79">

#

## WLAN

Messer
- WLAN = Wireless Local Area Network
  - 802.11 Technologies
- Mobility
  - Within a building or limited geographic area.
- Expand coverage with additional access points
  - Large Campus

#

## PAN

Messer
- PAN = Personal Area Network
  - Your private network, Bluetooth, IR, NFC.
- Automobile: Audio output, integrate with phone.

Dion
- Smallest type of wired or wireless network
  - Covers the least amount of area. (10 feet or less)
  - Example: Bluetooth and USB. USB connecting to a laptop = serial connection.

#

## CAN

Messer
- CAN = Campus Area Network
  - Corporate Area Network
- Limited geographical area: Group of buildings.
- LAN Techonologies: Fiber Connect and High Speed Ethernet.
- Own Fiber: No Third-party Provider.

Dion
- Connects LANs that are building-centric across a university, industrial park or business park.
- Can go up to few miles across many different buildings.

#

## NAS vs SAN

Messer 
- NAS = Network Attached Storage
  - Connect to a shared storage device across the network.
  - File-level access: Any changes you make to this file have to be done to the entire file located on the device.
    - If you need to change a byte on the file, and the file have 1 GB, you have overwrite the whole GB.
- SAN = Storage Area Network
  - Block level access: Can change what it just needed to be changed.
  - Very efficient reading and writing.
- NAS and SAN requires a lot of bandwidth.
  - May use an isolated network and high speed network technologies.
 

#

## MPLS

Messer
- MPLS = Multiprotocol Label Switching
  - Learning from ATM and Frame Relay
    - Keep the advantages, remove the disadvantages.
  - Communication through the WAN but uses label to determine how routing and forwarding traffic thru WAN.
  - Advantage:
    - Can almost use any type of connection for MPLS.
    - Put almost any type of data inside of MPLS.
    - Meaning: we could send IP Traffic, Ethernet frames thru MPLS network.
    - Makes MPLS easy to get up and running and have data transfer between 2 locations.
   

#

## MPLS pushing and Popping

Messer 
- Labels are "pushed" onto packets as they enter the MPLS cloud.
- Labels are "popped" off on the way out


#

## mGRE

Messer 
- mGRE = Multipoint Generic Router Encapsulation
  - Used extensively for Dyanmic Multipoint VPN (DMVPN)
  - Common on Cisco Routers.
- Your VPN builds itself
  - Remote sites communicate to each other.
- Tunnels are built dynamically, on demand: Dynamic Mesh.


#

## SD-WAN

Messer
- SD-WAN = Software Defined - Wide Area Network
  - Meaning: the WAN can be defined however we would like to laid it out.
  - Good for cloud based applications and needed to know where networks are going.
  - Cloud-based applications communicate directly to the cloud, No need to hop thru a central point.
 

<img width="396" alt="image" src="https://github.com/jefftsui1/Cybersecurity-Home-Labs/assets/46698661/7eff155b-9904-4fd2-a108-0d209f814ca8">
