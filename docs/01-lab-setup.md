# Lab

# Virtual Machines

For this lab, I created three Windows Server 2025 virtual machines in VMware:

* Domain Controller
* Server-1
* Server-2

# Network Configuration

| Server | IPv4 Address | DNS Server |
|---|---:|---:|
| Domain Controller | 192.168.10.5 | 127.0.0.1 |
| Server-1 | 192.168.10.6 | 192.168.10.5 |
| Server-2 | 192.168.10.7 | 192.168.10.5 |

The Domain Controller is running DNS, so both member servers are configured to use its IP address as their DNS server. This allows them to locate the Active Directory domain and successfully join it
All three servers are connected to the same VMware NAT network so they can communicate with each other
