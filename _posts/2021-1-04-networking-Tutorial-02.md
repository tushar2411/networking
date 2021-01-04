---
toc: true
layout: post
categories: [releases]
comments: true
title: Networking Tutorial 2:- Network And Topology
author: Tushar Sharma
---
# Networks  
Interconnection of set of device capable of communication. The device could be a host(computer) or a router or a modem.

## Network Criteria
* Performance:   
  * Measured in transit time and response time.
  * Depends on users, factors, transmission time, capabilities of hardware and efficiency of software.
  * Often evaluted by throughput and delay.
  * If we try to send more data to the network, we may increase throughput but we increase the delay because of traffic congestion in the network.

* Reliability:  
  * Network reliability is inversely proportional to frequency of failure.

* Security:  
  * Data should be transmitted from authorized access, policies and procedures should be implemented for recovery from breaches and data loses.

## Physical Structure  
1. Point to point Connection:  
   It provides a dedicated link between two devices.  
   example: connection with controller while changing channels on t.v.

   ![P2P](https://raw.githubusercontent.com/tushar2411/networking/master/images/point-to-point.jpg)
2. Multipoint or Multidrop Connection:  
   Connection one in which more than two specific devices share a single link.  
   Capacity of the link is shared:  
   * If several devices use simultaneously it is spatially shared connection.
   * If users must take turn than it is timeshared connection.  
   example: server access by multiple people.  
   ![multipoint](https://raw.githubusercontent.com/tushar2411/networking/master/images/multipoint.jpg)
  --- ---  
## Network Topologies 
* It refer to the way in which a network is laid out physically.   
* Two or more devices connect to a link.  
* Two or more link form a topology.
  
There are four basic types of topologies:   
* mesh 
* star
* bus
* ring

### 1. Mesh Topology  
  ![mesh](https://raw.githubusercontent.com/tushar2411/networking/master/images/mesh.jpg)
* Every device has a dedicated point to point link to every other device.  
* To find number of physical links in a fully connected topology:  
  * number of links = n(n-1)/2 ; n = number of nodes or devices

Advantages:  
* Eliminates traffic problems
* Robust
* Privacy and Security
* Fault identification due to P2P(point to point) links

Disadvantages:  
* Amount of cabling and number of I/O ports
* Installation and reconnetion difficulty
* Expensive
* Space availability shortage

Example: Telephone regional offices 

### 2. Star Topology
  ![star](https://raw.githubusercontent.com/tushar2411/networking/master/images/star.jpg)
* Each device has dedicated P2P connected to a controller or hub.
* Device not directly linked to each other.
* Data transmission via hub to other devices.

Advantages:  
* Less expansive 
* Easy to install and reconfigure
* Less cabling
* Robust

Disadvantages:  
* Whole dependency on hub
* If hub goes down system is dead
* More cables required in some cases
  
Example: used on LAN

### 3. Bus Topology
  ![bus](https://raw.githubusercontent.com/tushar2411/networking/master/images/bus.jpg)   
* Bus topology is a multipoint connection.
* One long cable acts as a backbone to link to all devices in a network.
* Devices are connected to the backbone using connectors.
  
Advantages:  
* Ease of installation
* Uses less cable than others
* Main cable travels to each device

Disadvantages:  
* Difficult reconnection and fault isolation
* Difficult to add new device
* Degradation of quality 
* Break in bus cable causes noise in both direction

Example: Ethernet's LAN's

### 4. Ring Topology
  ![ring](https://raw.githubusercontent.com/tushar2411/networking/master/images/ring.jpg)
* Each device has a dedicated P2P connection.
* Connection with only the two devices on either side of it.
* Signal is passed in the ring in one direction until it reaches its destination.
* Repeater regenerates bits and passes them  along.
  
Advantages:  
* Easy to install and configure
* To add a device or remove requires changing only 2 connections
* Fault isolation is simplified 

Disadvantages:   
* Unidirectional 
* Single break in connection disrupt entire network
* Less popular
  
Example:  Used in early IBM LAN network

--- --- 
*`So here we end our tutorial for the networking tutorial series `*  
*`Please do read if you are interested in netwworking`*  
*`In next tutorial we will study about- The History of Network, The almighty Internet and Switching`*

  
