# Windows-Server-2025-AD-Home-Lab

+ Summary +
I will be documenting my home lab created in VMware Workstation.
My initial goal is to develop a home lab in which I can practice server admin, networking, basic cyber security and virtualization. As I go, I'd like to scale it to add more aspects that encompass different disciplines within the practices of IT.

Work commenced 26/07/2026.
Repository opened 04/08/2026. (Work to be recorded moving forward).

# Lab
+ Server | Role +

Domain Controller | Active Directory Domain Services & DNS
Server-1 | Domain member server
Server-2 | Domain member server

# Completed 4/08

* Created 3 Windows Server VMs
* Configured DC01 server as Domain Controller
* Created 'DTech.com' as Active Directory domain
* Joined Server-1 and Server-2 to domain
      * NOTE: Required troubleshooting as unable to initially join servers to domain
      * Ran CMD to diagnose and understand issue - DNS was incorrect on member servers
      * Corrected and servers joined
* Created 3 user accounts - Damian Piilua, Pamian Diilua & Finance Gai
* Created the finance-team group
* Added user 'Finance Gai' to finance-team group
* Created a share folder
* Given specific access and permissions to finance-team group

# Skills utilized

* Windows Server 2025
* Active Directory Domain Services
* DNS configuration
* Domain links
* NTFS permissions & SMB file sharing
* Virtual Network
* Command prompt diagnostics and troubleshooting

# What to do next

* Add Powershell automation, potentially
* Group policies
* Possibly configure 
* Complete set up and prepare for configuration into cloud


04/08/2026
