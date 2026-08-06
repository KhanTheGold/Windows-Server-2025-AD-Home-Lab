# Domain Controller

Server DC01 (primary server) was promoted to a Domain Controller using Active Directory Domain Services.

## Configuration

* Operating system: Windows Server 2025
* Domain name: `DTech.com`
* Domain Controller hostname: `Domain-Controller`
* IPv4 address: `192.168.10.5`
* Installed roles:
  * Active Directory Domain Services
  * DNS Server

## Validation

Tests done with:

```cmd
dcdiag
nslookup DTech.com
nltest /dsgetdc:DTech.com
