## Network
I get start with CompTia Network+.

#### 1. Network Model (Just sth in general)
###### OSI 7-layers model
Physical - Data link - Network - Transport - Session - Presentation - Application.
###### Frame
Devices send and receive data in network in discreet chunks call frames (or packets).
Frames are 1500 maximun bytes.
NIC (network interface card) create and destroy frames.
###### MAC address (or Physical Adress)
MAC adress is a unique 48-bit identifier for a NIC (exe: 40-8D-1C-5A-50).
NICs use MAC address to decide whether or not to process a frame *(frames have "from" and "to" addresses)*.
###### Broadcast and unicast
Unicast transmission: addressed to a single device on a network.
Broadcast: to all the device in a broadcast network.
###### IP address
IP address: a logic address when a device connect to internet through a router by LAN(Local area network).
###### Packets and Ports
Ports: to tell the computer what data is used for(ex: 80 is for a webpage//http).
Packets have sequence numbers so sw can reassemble the file correctly.
Protocol: TCP and UDP.