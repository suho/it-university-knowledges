# Network Programming

- [Introduction](#introduction)
  - [Network Architecture](#network-architecture)
  - [Network Programming](#network-programming)
  - [Types of Network](#types-of-network)
  - [Operating System](#operating-system)
  - [Protocols](#protocols)
- [Models of Network](#models-of-network)
  - [OSI Model](#osi-model)
- [Server/Client Model](#serverclient-model)
- [Programming with TCP](#programming-with-tcp)
- [Programming with UDP](#programming-with-udp)
- [Programming with Multi-Thread](#programming-with-multi-thread)
- [Programming with Database](#programming-with-database)

## Introduction

### Network Architecture

Netowrk Architecture is the design of a computer network.

#### Network topology: 

The arrangement of a network which comprises of nodes and connecting lines via sender and receiver.

<p align="center">
    <img src="../img/np.network.topology.png" />
</p>

#### Layered Architecture

The basic idea of a layered architecture is to divide the design into smaill peaces.

System of network protocol consists:

- Hardwares
- Software

For example: OSI or TCP/IP Model Layers
  
### Network Programming

Network programming is create entity softwares that working on a particular layer. Using softwares of lower layer and provide services for higher layer.

People usually create entity software for `application layer`, provide services for user.

### Types of Network

#### LAN

- Bandwidth: High
- Error rate: Low
- Appropriate with applications: Email, File Transfer, Database application, Multi-media transfer.

#### WAN

- Install techniques: 
  - Lease-line, Frame-relay, ISDN, ATM...
  - Each technique have different bandwidth
- Applications: Data Communication, VoIP,...

#### Internet
- Unstable and unsafe compared with LAN and WAN
- Applications: Email, Web, E-Commerce, Game Online
- Cyber network security

### Operating System

One Network Application works on one or more computer systems.

To work, the application needs an operating environment and the most important environment is: Operating System.

- UNIX
- LINUX
- Windows
- macOS

### Protocols

- TCP/IP suite

<p align="center">
    <img src="../img/np.tcpip.suite.gif" />
</p>

## Models of Network

### OSI Model

<p align="center">
    <img src="../img/np.osi.model.png" width="50%" />
</p>

#### Physical Layer

Concerned with the transmission and reception of the unstructured raw bit stream over the physical medium.

- **Application**: 
  - **Physical structure** Cables, Hubs, ect.

- **Example**:
  - Data Encoding
  - Physical medium attachment
  - Tranmission technique
  - Baseband or Broadband
  - Physical medium transmission Bits & Volts

- **Central Device**:
  - Hub

- **Protocols**: _Not Available_

#### Data Link Layer

Provides error-free transfer of data frames from one node to another over the Physical layer

- **Application**: 
  - **Frames** ("envelopes", contains MAC address)
    [NIC card ---- Switch ---- NIC card] (end to end)

- **Example**:
  - Establishes & terminates the logical link between nodes
  - Frame traffic control
  - Frame squencing
  - Frame acknowledgment
  - Frame delimiting
  - Frame error checking
  - Media access control

- **Central Device**:
  - Switch
  - Bridge
  - WAP

- **Protocols**: 
  - PPP/SLIP

#### Network Layer

Controls the operations of the subnet, deciding which physical path the data takes.

- **Application**: 
  - **Packets** ("letter", contains IP address)

- **Example**:
  - Routing
  - Subnet traffic control
  - Frame fragmentation
  - Logical-physical addess mapping
  - Subnet usage accounting

- **Central Device**:
  - Routers

- **Protocols**: 
  - IP/IPX/ICMP

#### Transport Layer

Ensures that messages are delivered error-free, in sequence, and with no looses or duplications.

- **Application**: 
  - **TCP** Host to Host, Flow Control

- **Example**:
  - Message segmentation
  - Message acknowledgement
  - Message traffic control
  - Session multiplexing

- **Central Device**: _Not Available_

- **Protocols**: 
  - TCP/SPX/UDP

#### Session Layer

Allow session astablishment between processes running on different stations

- **Application**: 
  - **Synch & Send to Ports** (logical ports)

- **Example**:
  - Message segmentation
  - Message acknowledgement
  - Message traffic control
  - Session multiplexing

- **Central Device**: _Not Available_

- **Protocols**: 
  - TCP/SPX/UDP

## Server/Client Model

## Programming with TCP

## Programming with UDP

## Programming with Multi-Thread

## Programming with Database

[Network Topology]: ../img/np.network.topology.png
[TCP/IP Suite]: ../img/np.tcpip.suite.gif
[OSI Model]: ../img/np.osi.model.png