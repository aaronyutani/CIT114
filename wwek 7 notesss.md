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
