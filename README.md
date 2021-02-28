# ft_netwhat

42 Sao Paulo project - Net WHat?

## Notes

It's a really good brush up on networking.
Most of the questions use the IP calculator.

### TCP

TCP sends information to a single known host.
The information's integrity is pretty much guaranteed by extensive error-checking.
All packets arrive in order, and it's slower than UDP.
It's used by SMTP, HTTP, FTP and many others.

### UDP

UPD listens and broadcasts data to and from anything else that's broadcasting and listening.
The only error-checking it has is a checksum in each package.
It's used by DHCP (if you don't have an IP you can't use TCP), Voice over IP,
DNS, some streaming protocols, and more.

### DHCP

It's what assigns dynamic IPs to devices in a network.
Supports IPv4 and IPv6.

### ping

A common networking tool that checks if a host is turned on and connected. Uses ICMP.

### IP classes

Class A is the largest, with almost 17 million assignable IP addresses.
Used by very large organizations.

### Hosts in a Network

The ammount of assignable IPs in a subnet is always `pow(2, ip_bits_available) - 2`

### Network and Broadcast IPs

The Network IP address always ends with a 0.
The Broadcast IP address is always the last IP in the subnet.
Any package sent to the broadcast address relayed to all hosts in the subnet.

### DNS

It's a program running on a server somewhere that tells you which IP belongs to `google.com`.
You can talk to those servers with `nslookup`:

```bash
$ nslookup google.com
```

### Private IP

They all start with 192, 172 and 10.

## Testers

- [https://github.com/adblanc/netwhat42-train](https://github.com/adblanc/netwhat42-train)
- [https://github.com/appinha/42cursus/tree/master/01-netwhat](https://github.com/appinha/42cursus/tree/master/01-netwhat)

## Resources

- [https://en.wikipedia.org/wiki/Private_IP](https://en.wikipedia.org/wiki/Private_IP)
- [https://en.wikipedia.org/wiki/OSI_model](https://en.wikipedia.org/wiki/OSI_model)
- [https://en.wikipedia.org/wiki/User_Datagram_Protocol](https://en.wikipedia.org/wiki/User_Datagram_Protocol)
- [https://en.wikipedia.org/wiki/Transmission_Control_Protocol](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)
- [https://en.wikipedia.org/wiki/Ping\_(networking_utility)](https://en.wikipedia.org/wiki/Ping_%28networking_utility%29)
- [https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol](https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol)
- [https://www.meridianoutpost.com/resources/articles/IP-classes.php](https://www.meridianoutpost.com/resources/articles/IP-classes.php)

- [Private IP](https://whatismyipaddress.com/private-ip?__cf_chl_jschl_tk__=5b82b4f491407ec3c21c21de877c674ab747e579-1613940129-0-AWiz3zZF8QDWnRF0_vuiCAeZoCm1crquVe_N7ljLWW2854clNl-RxEzSU_HktAlZPFT4f7MValxzkzYvX3gdwa_D0-LXt5OgA56Kc7FRixHudg8ZVxZWUoKIYEEexYsZTcQrzBruxujERC-TzktMtvU3SJCbs1WRlCqSW0SfZK6Zu84i8_LdOEp5xOgHG-vYPKqLxrutUF7T2_RLiYO2IBD1VYdoKOvZ99PudLjuhV5sNbETrT7wOO4mudNyqmOK3JysgUbVs7nZh7knQKsNxnrDJgJK1GbJZPgEXfLoj5p7khCXrxqHaxA1Q8piIslMvpl08BCtm8R30iGRWG4kDiiKKuSZ9tNKqIDLSJh4XGWUSsV80g9v_6H14t3-hnVhDA)
- [https://www.lifewire.com/what-is-a-private-ip-address-2625970](https://www.lifewire.com/what-is-a-private-ip-address-2625970)
- [https://www.csestack.org/different-classes-of-ip-address/#Class_A](https://www.csestack.org/different-classes-of-ip-address/#Class_A)
- [https://www.youtube.com/c/ippsec/videos](https://www.youtube.com/c/ippsec/videos)
- [https://github.com/appinha/42cursus/tree/master/01-netwhat](https://github.com/appinha/42cursus/tree/master/01-netwhat)
- [https://github.com/lucasnfarias/42Cursus/blob/master/netwhat/NETWHAAAAAAAAAAAAAAAT\_.pdf](https://github.com/lucasnfarias/42Cursus/blob/master/netwhat/NETWHAAAAAAAAAAAAAAAT_.pdf)

## IP Mask Calculators

- [http://jodies.de/ipcalc?host=192.168.0.1&mask1=24&mask2=](http://jodies.de/ipcalc?host=192.168.0.1&mask1=24&mask2=)
- [https://github.com/appinha/ip_calc-netwhat-42cursus](https://github.com/appinha/ip_calc-netwhat-42cursus)
