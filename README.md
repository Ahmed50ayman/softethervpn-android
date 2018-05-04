# SoftEther VPN for Android
- An Open-Source Cross-platform Multi-protocol VPN Program
http://www.softether.org/

This repository is based on Softether Stable Edition Respository.

Copyright (c) SoftEther Project at University of Tsukuba, Japan.

The development of SoftEther VPN was supported by the MITOH Project,
a research and development project by Japanese Government,
subsidized by Ministry of Economy, Trade and Industry of Japan,
administrated by Information Promotion Agency.
https://www.ipa.go.jp/english/humandev/


This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License version 2
as published by the Free Software Foundation.

SoftEther VPN ("SoftEther" means "Software Ethernet") is one of the
world's most powerful and easy-to-use multi-protocol VPN software.

SoftEther VPN runs on Windows, Linux, Mac, FreeBSD and Solaris.

SoftEther VPN supports most of widely-used VPN protocols
including SSL-VPN, OpenVPN, IPsec, L2TP, MS-SSTP, L2TPv3 and EtherIP
by the single SoftEther VPN Server program.

More details on http://www.softether.org/.



# SOFTETHER VPN ADVANTAGES
- Supporting all popular VPN protocols by the single VPN server:
  SSL-VPN (HTTPS)
  OpenVPN
  IPsec
  L2TP
  MS-SSTP
  L2TPv3
  EtherIP
- Free and open-source software.
- Easy to establish both remote-access and site-to-site VPN.
- SSL-VPN Tunneling on HTTPS to pass through NATs and firewalls.
- Revolutionary VPN over ICMP and VPN over DNS features.
- Resistance to highly-restricted firewall.
- Ethernet-bridging (L2) and IP-routing (L3) over VPN.
- Embedded dynamic-DNS and NAT-traversal so that no static nor
  fixed IP address is required.
- AES 256-bit and RSA 4096-bit encryptions.
- Sufficient security features such as logging and firewall inner
  VPN tunnel.
- User authentication with RADIUS and NT domain controllers.
- User authentication with X.509 client certificate.
- Packet logging.
- 1Gbps-class high-speed throughput performance with low memory and
  CPU usage.
- Windows, Linux, Mac, Android, iPhone, iPad and Windows Phone are
  supported.
- The OpenVPN clone function supports legacy OpenVPN clients.
- IPv4 / IPv6 dual-stack.
- The VPN server runs on Windows, Linux, FreeBSD, Solaris and Mac OS X.
- Configure All settings on GUI.
- Multi-languages (English, Japanese and Simplified-Chinese).
- No memory leaks. High quality stable codes, intended for long-term runs.
  We always verify that there are no memory or resource leaks before
  releasing the build.
- More details at http://www.softether.org/.


# GETTING STARTED

##  Requirements

### Android

- ncurses5 (https://www.gnu.org/software/ncurses/)
- readline (https://tiswww.cwru.edu/php/chet/readline/rltop.html)
- openssl (https://wiki.openssl.org/index.php/Android)


## Compile and install

The download and build instruction is following:

```sh
$ git clone https://github.com/lfasmpao/softethervpn-android
$ cd softethervpn-android
$ export CROSS_PLATFORM=(android ndk gcc location) 
$ ./configure
$ make
$ make install
```

