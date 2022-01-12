
# TTM4100 - Communication - Services and Networks

## 1 Computer Networks and the Internet



### 1.1 What is the Internet?

#### 1.1.1 A Nuts-and-Bolts Description

Term | Description
--- | ---
host / end system | all deviced connected to a network
communication link | connects end systems
packet switch | forwards packets from an incoming comm. link to and outgoing comm. link.
transmission rate | number of bits transmitted per second
packets | a segment of data (with a given header)
router | type of packet switch, typically used in the network core
link-layer switches | type of packet switch, typically used in access networks
route / path | the sequence of comm. links and packet switches traversed bu a packet from the sending end system to the receiving end system
ISP | Internet Service Provider, end systems access the Internet through ISPs
protocol | control the sending and receiving of information within the Internet
TCP | Transmission Control Protocol
IP | Internet Protocol, specifies the format of the packets
Internet standards | developed by the Internet Engineering Task Force, documents are called RFCs
RFC | Request For Comments to resolve network and protocol design problems, define protocols such as TCP, IP, HTTP, SMTP

#### 1.1.2 A Services Description
We can describe the Internet as done in 1.1.1 (hardware and software components), or as *an infrastructure that provides services to distributed applications*.

Term | Description
--- | ---
distributed application | involves multiple end systems that exchange data with each other
socket interface | a set of rules that specify how a program running on one end system asks the Internet infrastucture to deliver data to a specific destination program running on another end system 

#### 1.1.3 What is a Protocol?
A **protocol** defines the format and the order of messages exchanged between two or more communication entities, as well as the actions taken on the transmission and/or receipt of a message or other event.



### 1.2 The Network Edge

#### 1.2.1 Access Networks

##### Home Access: DSL, Cable, FTTH and 5G Fixed Wireless

Term | Description
--- | ---
DSL | Digital Subscriber Line, makes use of the telco's existing local telephone infrastructure
cable Internet access | makes use of the cable television company's existing cable television infrastructure
asymmetric access | has different downstream and upstream transmission rates
HFC | Hybrid Fiber Coax, a system where both fiber and coaxial cable are employed
FTTH | Fiber To The Home, provides an optical fiber path from the CO directly to the home
AON | Active Optical Network, essentially switched Ethernet
PON | Passive Optical Network
ONT | Optical Network Terminator
OLT | Optical Line Terminator

##### Access in the Enterprise (and the Home): Ethernet and Wifi

Term | Description
--- | ---
LAN | Local Area Network
Ethernet | the most prevalent (wired) access technology for LANs in corporate, universities and homes
WiFi | Wireless LAN access based on IEEE 802.11 technology

##### Wide-Area Wireless Access: 3G and LTE 4G and 5G
Mobile devices such as iPhones and Android devices employ the same wireless infrastructure used for cellular telephony to send/receive packets through a base station that is operated by the cellular network provider. Unlike WiFi, a user need only be within a few  tens of kilometers (as opposed to a few tens of meters) of the base station.

#### 1.2.2 Physical Media
Examples of physical media include twisted-pair copper wire, coaxial cable, multimode fiber-optic cable, terrestrial radio spectrum, and satellite radio spectrum.

Term | Description
--- | ---
guided media | the waves are guided along a solid medium
unguided media | the waves propagate in the atmosphere and in outer space

##### Twisted-Pair Copper Wire
The least expensive and most commonly used guided transmission medium. The wires are twisted together to reduce the electrical interference from similar pairs close by. Unshielded twisted pair (UTP) is commonly used for computer networks within a building, that is, for LANs.

##### Coaxial Cable
Like twisted pair, coaxial cable consists of two copper conductors, but the two conductors are concentric rather than parallel. With this construction and special insulation and shielding, coaxial cable can achieve high data transmission rates. Can be used as a guided *shared medium*.

##### Fiber Optics
An optical fiber is a thin, flexible medium that conducts pulses of light, with each pulse representing a bit. Can support tremendous bit rates, are immune to electromagnetic interference, have very low signal attenuation up to 100 kilometers, and are very hard to tap. Expensive.

##### Terrestrial Radio Channels
Radio channels carry signals in the electromagnetic spectrum. They are an attractive medium because they require no physical wire to be installed, can penetrate walls, provide connectivity to a mobile user, and can potentially carry a signal for long distances. Prone to shadow fading (which decrease the signal strength as the signal travels over a distance and around/through obstructing objects), multipath fading (due to signal reflection off of interfering objects), and interference (due to other transmissions and electromagnetic signals).

##### Satellite Radio Channels
A communication satellite links two or more Earth-based microwave transmitter/receivers, known as ground stations. Two types of satellites are used 
in communications: geostationary satellites (remain above the same spot on Earth) and low-earth orbiting (LEO) satellites.


### 1.3 The Network Core

#### 1.3.1 Packet Switching

### 1.4 Delay, Loss, and Throughput in Packet-Switched Networks

### 1.5 Protocol Layers and Their Service Models

### 1.6 Networks Under Attack

### 1.7 History of Computer Networking and the Internet
