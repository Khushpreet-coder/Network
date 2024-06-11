# Network
* OSI MODEL(Open System Interconnection)-
There are 7 layers in the OSI Model.

  1.Physical Layer 2.Data Link Layer 3.Network Layer 4.Transport Layer 5.Session Layer 6.Presentation Layer 7.Application Layer

Devices used in Layers-
 1. Phy Layer- Cable,Hub ; Data in the form of bits(0,1).
 
 2.Data Link Layer-Switches,Bridges ; Data in the form of frames.
   Here we use MAC address.
 
 3.Network Layer-Router (which find best route for transmission data) ; Data in the form of Packets.
   Here we use IP address.

 4.Transport Layer- Data in the form of Segments
 
 5.Session Layer- There are checkpoints
 
 6.Presentation Layer- Translation,Encryption, Decryption, Compression
 
 7.Application Layer- eg. email etc.


 For understanding concept of OSI- 
  
  1.https://en.wikiversity.org/wiki/Network%2B/Standards/OSI_Model/OSI_Components 
 
  2.https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/
  
* TCP/IP MODEL-
There are 4 layers in the TCP/IP Model.

1. Here Application Layer, Presentation Layer and Session Layer make one Layer called APPLICATION LAYER.

    Protocols in APP LAYER is HTTP,SMTP etc.

    HTTP- It is less secure ,mostly used.

    HTTPS-Here S for secure.eg in U Tube URL

2. Another layer is TRANSPORT LAYER-

   Protocols in TRANSPORT LAYER is TCP/UDP.

4. Another is N/W LAYER

   Protocols in N/W LAYER is ICMP/IGMP.

6. Here DATA LINK LAYER and PHY LAYER are combined.

* IP- IP address stands for internet protocol address; it is an identifying number that is associated with a specific computer or computer network.

  IP Address can be - a) Static :A static IP address is permanent address which will never change and is assigned by an administrator.

  b) Dynamic: A dynamic IP address device changes its IP address every time when accessing internet. It is assigned by the host software.

  IP TYPES- a)  Unicast IP Address: It transforms information to a specific device over a network.

     b) Broadcast IP Address: It is used to deliver information to all the computers on a given subnet at once.

  c) Multicast IP Address: These are reserved IP addresses and used only for specific group.

  d) Private IP Address: These are local addresses and one IP address can be used by more than one organization. It is absolutely free to use and can?t be routed over the network.

  e) Public IP Address: They are unique and their duplication is not possible hence they need to be bought.

  There are 2 verion of IP is IPV4 & IPV6. Now IPV6 is used because it provides a vastly expanded address space(2^128).
 
* IP Classes-https://www.geeksforgeeks.org/introduction-of-classful-ip-addressing/ 


 * What Is a Firewall?
 
 A firewall is a network security device that monitors traffic to or from your network. It allows or blocks traffic based on a defined set of security rules.(Block malicious links)

*Port-What is a port?

A port is a virtual point where network connections start and end. Ports are software-based and managed by a computer's operating system. Each port is associated with a specific process or service. Ports allow computers to easily differentiate between different kinds of traffic: emails go to a different port than webpages, for instance, even though both reach a computer over the same Internet connection.

HTTP(PORT 80),FTP(20/21),SMTP(25),DNS(53),SSH (22) ‍SSH or Secure Shell.
