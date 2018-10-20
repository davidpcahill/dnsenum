# dnsenum
DNS Enumeration Script and Bruteforce Lists I've compiled by hand

Finds a shitload of hostnames and subdomains for an existing domain.

VERY noisy at the nameserver level. But your target will likely never see any of that traffic.

Whitehat and responsible penteting use only please.



Future plans:

* Expand existing script to use intellegent prefixes and word creation from list types and categories.
* Rewrite completely in python
* Add google and shodan and other database / api sources for OSINT gathering.
* Scoring and commonality in wordlists to auto update locally (or remotely if you wish to participate)
* Different search order such as most common, random, alphabetical, etc.
* Query multiple name servers
* DNS TLS/SSL


Ubuntu perl things to install:

sudo apt install libxml-writer-perl
sudo apt install libnet-netmask-perl
sudo apt install libstring-random-perl

That should do it.
