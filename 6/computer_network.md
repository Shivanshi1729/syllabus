---
layout: default
title: Computer Networks
parent: 6
---

# Computer Networks

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Course Outcomes

1. Characterize and appreciate computer networks from the view point of 
   components and from the view point of services
2. Display good understanding of the flow of a protocol in general and a 
   network protocol in particular
3. Model a problem or situation in terms of layering concept and map it 
   to the TCI/IP stack
4. Select the most suitable Application Layer protocol (such as HTTP, FTP,
   SMTP, DNS, Bittorrent) as per the requirements of the network application 
   and work with available tools to demonstrate the working of these protocols.
5. Design a Reliable Data Transfer Protocol and incrementally develop solutions
   for the requirements of Transport Layer
6. Describe the essential principles of Network Layers and use IP addressing
   to create subnets for any specific requirements.

## Unit I

- Introduction: 
  - Computer Networks and the Internet, 
  - Overall view: 
    - As components and as services; 
    - What is a protocol, 
    - what is a network protocol,
    - Access Networks and Physical Media, 
    - Circuit and Packet Switching,
    - Internet Backbone, 
    - Delays: 
      - Processing, 
      - Queing, 
      - Transmission and 
      - Propagation delays
  - The Layered Architecture: 
    - Protocol Layering, 
    - The OSI Reference Model and 
    - the TCP/IP protocol stack, 
  - History of Computer Networking and the Internet

## Unit II

- Application Layer: 
  - Principles and Architectures of Network Applications, 
  - Client and Server processes, 
  - the idea of socket, 
  - Transport services available to Application Layer especially in the internet.
- Application Layer Protocols: 
  - The Web and http: 
  - Persistent and Non-persistent connections, 
  - http message format, 
  - cookies, 
  - proxy server,
  - conditional GET
  - File Transfer Protocol
  - Email: 
    - smtp, 
    - mail message formats, 
    - mail access protocols: 
      - pop3, 
      - imap,
      - MIME
- DNS: 
  - Services, 
  - How it works, 
  - Root, 
  - Top-Level and Authoritative DNS servers, 
  - Resource Records, 
  - DNS messages 
- A simple introduction to p2p file distribution: 
  - BitTorrent

## Unit III

- Transport Layer: 
  - Introduction and Services, 
  - The Transport layer in internet, 
  - Difference between Connection Oriented and Connectionless services
- UDP: 
  - Segment structure, 
  - checksum in UDP

## Unit IV

- Transport Layer2:
  - The principles behind connection oriented data transfer, 
  - designing a connection oriented protocol, 
  - stop-and-wait, 
  - Go Back N, 
  - Selective Repeat
- TCP: 
  - Connection Establishment, 
  - TCP header, 
  - Sequence and 6 acknowledgement numbers, 
  - Round Trip Time, 
  - Flow Control, 
  - Congestion Control

## Unit V

- Network Layer I: 
  - Introduction, 
  - Packet Forwarding and Routing, 
  - Difference between Virtual Circuits and Datagram networks, 
- The internals of a router: 
  - Input ports, 
  - output ports, 
  - switching architecture
- The Internet Protocol(IP), 
- Datagram format, 
- IP fragmentation, 
- IPv4 addressing, 
- subnets, 
- CIDR, 
- classful addressing, 
- DHCP, 
- Network Address Translation(NAT), 
- Universal Plug and Play as a provider of NAT, 
- Internet Control Message Protocol(ICMP), 
- IPv6 Header, 
- Moving from IPv4 to IPv6: 
  - tunnelling, 
- A brief discussion on IP security

> Note: Network Layer will continue with Routing Algorithms in Computer
> Networks II in the next semester

## Text Books

- Computer Networking: 
  **"A Top Down Approach (5th edition)"**, 
  Ross and Kurose, Pearson/Addison-Wesley

## Reference Books

- Andrew Tanenbaum and David Wetherhall, 
  **"Computer Networks(5 th edition)"**,
  Prentice Hall
- Peterson and Davie, 
  **"Computer Networks: A System Approach (4th edition)"**,
  Elsevier
- Forouzan, 
  **"Data Communication and Networking (4th edition)"**,
  McGraw Hill
- William Stallings: 
  **"Data and Computer Communication (8th Edition)"**,
  Pearson Education, 2007
- Nader F. Mir
  **"Computer and Communication Networks"**,
  Pearson Education, 2007.