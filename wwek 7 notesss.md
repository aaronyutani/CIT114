## CIT week 7 

## 7.01 What is a Network?
_the internet is tens of thousands kilometres of fiber optic cable, hundreds of thousands to millions of kilometres of copper wire, and hardware and software connecting them all together in a redundant, fast, and self-sufficient network._

_At its core, a computer network is just two or more client machines that are connected together, using a network device, to share resources._

_A network can be logically partitioned to create subnets._

_A router or switch are used to connect the clients together and enable communications._

## 7.02 Definitions for Computer Networking

_Computer Network_
* It is the interconnection of multiple devices, generally termed as Hosts connected using multiple paths for the purpose of sending/receiving data or media.

_OSI_
* OSI stands for Open Systems Interconnection. It is a reference model that specifies standards for communications protocols and also the functionalities of each layer.

_Protocol_
* Protocol is the set of rules or algorithms which define the way how two entities can communicate across the network and there exists different protocol defined at each layer of OSI model. Few of such protocols are TCP, IP, UDP, ARP, DHCP, FTP and so on.

## 7.03 Introduction to IP Addresses & Binary Math


_Two important components to networking are how you know where to go on a network (IP Address) and how the computer translates the number into something it can understand (Binary)._

## 7.05 Microsoft: Understanding TCP/IP addressing and subnetting basics

_Introduction_
* When you configure the TCP/IP protocol on a Microsoft Windows computer, an IP address, subnet mask, and usually a default gateway are required in the TCP/IP configuration settings.
* The success of TCP/IP as the network protocol of the Internet is largely because of its ability to connect together networks of different sizes and systems of different types

## 7.07 Introducing Amazon VPC

_Amazon Virtual Private Cloud (Amazon VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define._

_You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways._

_You can use both IPv4 and IPv6 in your VPC for secure and easy access to resources and applications._

_This enables you to provision logically isolated sections of the AWS Cloud where you can launch AWS resources in your virtual network. You have control over your virtual networking resources including:_
* Selection of IP address ranges
* Creation of Subnets
* Configuration of route tables and network gateways

## 7.08 VPCs and Subnets
_A virtual private cloud (VPC) is a virtual network dedicated to your AWS account. It is logically isolated from other virtual networks in the AWS Cloud._

_When you create a VPC, you must specify a range of IPv4 addresses for the VPC in the form of a Classless Inter-Domain Routing (CIDR) block; for example, 10.0.0.0/16_

_A VPC spans all of the Availability Zones in the Region. After creating a VPC, you can add one or more subnets in each Availability Zone._

## 7.09 IP Addressing in your VPC

_IP addresses enable resources in your VPC to communicate with each other, and with resources over the Internet. Amazon EC2 and Amazon VPC support the IPv4 and IPv6 addressing protocols._

_By default, Amazon EC2 and Amazon VPC use the IPv4 addressing protocol._

_You can optionally associate an IPv6 CIDR block with your VPC and subnets, and assign IPv6 addresses from that block to the resources in your VPC. IPv6 addresses are public and reachable over the Internet._

## 7.10 Elastic Network Interfaces

_An elastic network interface (referred to as a network interface in this documentation) is a virtual network interface that can include the following attributes:_
* a primary private IPv4 address
* one or more secondary private IPv4 addresses
* one Elastic IP address per private IPv4 address
* one public IPv4 address, which can be auto-assigned to the network interface for eth0 when you launch an instance
* one or more IPv6 addresses
* one or more security groups
* a MAC address
* a source/destination check flag
* a description

_You can create a network interface, attach it to an instance, detach it from an instance, and attach it to another instance. A network interface's attributes follow it as it is attached or detached from an instance and reattached to another instance._

## 7.11 VPC Route Tables

_A route table contains a set of rules, called routes, that are used to determine where network traffic from your subnet or gateway is directed. Each route specifies a destination and a target._

_Each subnet in your VPC must be associated with a route table. The main route table is the route table is automatically assigned to your VPC._

## 7.12 Internet Gateway

_An internet gateway is a horizontally scaled, redundant, and highly available VPC component that allows communication between your VPC and the internet._

_An internet gateway serves two purposes: to provide a target in your VPC route tables for internet-routable traffic, and to perform network address translation (NAT) for instances that have been assigned public IPv4 addresses_

_An internet gateway supports IPv4 and IPv6 traffic. It does not cause availability risks or bandwidth constraints on your network traffic._

_To enable access to or from the internet for instances in a subnet in a VPC, you must do the following:_
* Attach an internet gateway to your VPC.
* Add a route to your subnet's route table that directs internet-bound traffic to the internet gateway. If a subnet is associated with a route table that has a route to an internet gateway, it's known as a public subnet. If a subnet is associated with a route table that does not have a route to an internet gateway, it's known as a private subnet.
* Ensure that instances in your subnet have a globally unique IP address (public IPv4 address, Elastic IP address, or IPv6 address).
* Ensure that your network access control lists and security group rules allow the relevant traffic to flow to and from your instance.

## 7.13 Network Address Translation (NAT)

_You can use a NAT device to enable instances in a private subnet to connect to the internet (for example, for software updates) or other AWS services, but prevent the internet from initiating connections with the instances_

_A NAT device forwards traffic from the instances in the private subnet to the internet or other AWS services, and then sends the response back to the instances._

_When traffic goes to the internet, the source IPv4 address is replaced with the NAT device’s address and similarly, when the response traffic goes to those instances, the NAT device translates the address back to those instances’ private IPv4 addresses._

1. Summarize a few key points made in the readings or videos.
_networking is used in differntent ways but the internet is in a copper fiber optic cables._
2. Identify two quotes that were made, that you found interesting.
_when 7.05 started talkibg about microsoft i kept thinking minecraft and how it runs java._
3. What new facts did you learn from this section?
_there are a lot of IP addresses like huh?_
4. What questions remain in your mind after reading this section?
_what is a network?_
