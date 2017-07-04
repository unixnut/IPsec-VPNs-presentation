# VPNs with IPsec
A talk to be given at the 
[WA chapter meeting](https://www.meetup.com/SAGE-AU-WA/events/240444046) of the 
[Information Technology Professionals Association](http://itpa.org.au/)
on 4 July 2017

## Blurb

Alastair Irvine will be presenting on IPsec, which is a cross-platform, network-layer crypto facility built into the TCP/IP stack of all modern operating systems.  It was designed for IPv6 but was back-ported to IPv4 many years ago.

One of the ways in which IPsec can be used is "tunnel mode", which is indistinguishable in practice from regular VPNs provided by OpenVPN or the Cisco vpnc client for example.

This presentation will cover the use of IPsec with locally-generated X.509 certificates.  I'll describe a Makefile that I wrote that acts as a Public Key Infrastructure (a.k.a. Certificate Authority) facility, allowing a trust framework to be established without relying on passwords or external authorisation.  Only someone who has been issued a certificate can connect, and any of these certificates can be revoked on request by adding it to a list on the VPN server. 

The *strongSwan* software is used on the server, and on Linux/Unix clients, but clients on other platforms are supported. 

## Outline

## Presenter bio

Alastair is a Software Engineer and system administrator by trade.  He has a BSc in Computer Science from Curtin University.

His computer-related interests lie in various areas within his trade; suffice to say that he is a "geek of many colours". :)  Alastair is a die-hard FOSS user and Linux fan.

He is also a freelancer with his own business.  [Warpspace IT](http://www.warpspace.net/) is a consultancy with a fairly broad focus on the technical side of IT.

## Slides

**TBA**
