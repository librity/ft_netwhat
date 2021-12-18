<h3 align="center">42 São Paulo - NetWhat?</h3>

<div align="center">

![42 São Paulo](https://img.shields.io/badge/42-SP-1E2952)
![License](https://img.shields.io/github/license/librity/ft_netwhat?color=yellow)
![Code size in bytes](https://img.shields.io/github/languages/code-size/librity/ft_netwhat?color=blue)
![Lines of code](https://img.shields.io/tokei/lines/github/librity/ft_netwhat?color=blueviolet)
![Top language](https://img.shields.io/github/languages/top/librity/ft_netwhat?color=ff69b4)
![Last commit](https://img.shields.io/github/last-commit/librity/ft_netwhat?color=orange)

</div>

<p align="center"> Putting the FUN in networking fundamentals.
  <br>
</p>

---

## 📜 Table of Contents

- [About](#about)
- [Notes](#notes)
- [42 São Paulo](#ft_sp)
- [References](#references)
- [Resources](#resources)

## 🧐 About <a name = "about"></a>

In this project we learn the basics of networking and th Internet Protocol.
Most of the questions use the IP calculator.

## 📝 Notes <a name = "notes"></a>

### TCP

TCP sends information to a siingle known host.
The information's integrity is pretty much guaranteed by extensive error-checking.
All packets arrive in order, and it's slower than UDP.
It's used in SMTP, HTTP, FTP and many others.

### UDP

UPD listens and broadcasts data to and from anything else that's listening.
The only error-checking it has is a checksum in each package.
It's used for DHCP (if you don't have an IP you can't use TCP), Voice over IP,
DNS, some streaming protocols, and more.

### DHCP

It's what assigns dynamic IPs to devices in a network.
Supports IPv4 and IPv6.

### ping

A common networking tool that checks if a host is online and connected. Uses ICMP.

### IP classes

Class A is the largest, with almost 17 million assignable IP addresses.
Used by very large organizations.

### Hosts in a Network

The ammount of assignable IPs in a subnet is always `pow(2, ip_bits_available) - 2`

### Network and Broadcast IPs

Network always ends with a 0.
The broadcast address is the last adressable IP.
Any package sent to the broadcast address is received by all hosts in the network.

### DNS

It's a program running on a server somewhere that tells you which IP belongs to `google.com`:

```bash
$ nslookup google.com
```

### Private IP

They all start with 192, 172 and 10.

## 🛸 42 São Paulo <a name = "ft_sp"></a>

Part of the larger [42 Network](https://www.42.fr/42-network/),
[42 São Paulo](https://www.42sp.org.br/) is a software engineering school
that offers a healthy alternative to traditional education:

- It doesn't have any teachers and classes.
- Students learn by cooperating
  and correcting each other's work (peer-to-peer learning).
- Its focus is as much on social skills as it is on technical skills.
- It's completely free to anyone that passes its selection process -
  [**The Piscine**](https://42.fr/en/admissions/42-piscine/)

It's an amazing school, and I'm grateful for the opportunity.

## 🏫 References <a name="references"></a>

- [https://en.wikipedia.org/wiki/Private_IP](https://en.wikipedia.org/wiki/Private_IP)
- [https://en.wikipedia.org/wiki/OSI_model](https://en.wikipedia.org/wiki/OSI_model)
- [https://en.wikipedia.org/wiki/User_Datagram_Protocol](https://en.wikipedia.org/wiki/User_Datagram_Protocol)
- [https://en.wikipedia.org/wiki/Transmission_Control_Protocol](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)
- [https://en.wikipedia.org/wiki/Ping\_(networking_utility)](https://en.wikipedia.org/wiki/Ping_%28networking_utility%29)
- [https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol](https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol)
- [https://www.meridianoutpost.com/resources/articles/IP-classes.php](https://www.meridianoutpost.com/resources/articles/IP-classes.php)

## 📚 Resources <a name = "resources"></a>

- [Private IP](https://whatismyipaddress.com/private-ip?__cf_chl_jschl_tk__=5b82b4f491407ec3c21c21de877c674ab747e579-1613940129-0-AWiz3zZF8QDWnRF0_vuiCAeZoCm1crquVe_N7ljLWW2854clNl-RxEzSU_HktAlZPFT4f7MValxzkzYvX3gdwa_D0-LXt5OgA56Kc7FRixHudg8ZVxZWUoKIYEEexYsZTcQrzBruxujERC-TzktMtvU3SJCbs1WRlCqSW0SfZK6Zu84i8_LdOEp5xOgHG-vYPKqLxrutUF7T2_RLiYO2IBD1VYdoKOvZ99PudLjuhV5sNbETrT7wOO4mudNyqmOK3JysgUbVs7nZh7knQKsNxnrDJgJK1GbJZPgEXfLoj5p7khCXrxqHaxA1Q8piIslMvpl08BCtm8R30iGRWG4kDiiKKuSZ9tNKqIDLSJh4XGWUSsV80g9v_6H14t3-hnVhDA)
- [https://www.lifewire.com/what-is-a-private-ip-address-2625970](https://www.lifewire.com/what-is-a-private-ip-address-2625970)
- [https://www.csestack.org/different-classes-of-ip-address/#Class_A](https://www.csestack.org/different-classes-of-ip-address/#Class_A)
- [https://www.youtube.com/c/ippsec/videos](https://www.youtube.com/c/ippsec/videos)
- [https://github.com/appinha/42cursus/tree/master/01-netwhat](https://github.com/appinha/42cursus/tree/master/01-netwhat)
- [https://github.com/lucasnfarias/42Cursus/blob/master/netwhat/NETWHAAAAAAAAAAAAAAAT\_.pdf](https://github.com/lucasnfarias/42Cursus/blob/master/netwhat/NETWHAAAAAAAAAAAAAAAT_.pdf)

### Testers

- [https://github.com/adblanc/netwhat42-train](https://github.com/adblanc/netwhat42-train)
- [https://github.com/appinha/42cursus/tree/master/01-netwhat](https://github.com/appinha/42cursus/tree/master/01-netwhat)

### IP Mask Calculators

- [http://jodies.de/ipcalc?host=192.168.0.1&mask1=24&mask2=](http://jodies.de/ipcalc?host=192.168.0.1&mask1=24&mask2=)
- [https://github.com/appinha/ip_calc-netwhat-42cursus](https://github.com/appinha/ip_calc-netwhat-42cursus)
