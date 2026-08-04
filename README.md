# Windows Server 2025 Active Directory Home Lab

## Summary

This repository documents my Windows Server 2025 home lab built in VMware Workstation.

The goal of this project is to develop practical experience with Windows Server administration, networking, Active Directory, virtualization and basic cybersecurity. As the lab grows, I plan to expand it into other areas of IT infrastructure and cloud computing.

- **Lab started:** 26/07/2026
- **GitHub repository created:** 04/08/2026

---

## Lab Environment

| Server | Role |
|---------|------|
| DC01 | Domain Controller (Active Directory Domain Services & DNS) |
| Server-1 | Domain Member Server |
| Server-2 | Domain Member Server |

---

## Completed (04/08/2026)

- Created three Windows Server 2025 virtual machines in VMware.
- Promoted **DC01** to a Domain Controller.
- Created the **DTech.com** Active Directory domain.
- Successfully joined **Server-1** and **Server-2** to the domain.
    - Initial attempts failed due to incorrect DNS configuration.
    - Used Command Prompt tools (`ping`, `nslookup`, and `nltest`) to troubleshoot the issue.
    - Corrected the DNS configuration and successfully joined both servers.
- Created three Active Directory user accounts:
    - Damian Piilua
    - Pamian Diilua
    - Finance Gai
- Created the **finance-team** security group.
- Added **Finance Gai** to the **finance-team** group.
- Created a shared folder.
- Assigned NTFS and share permissions to the **finance-team** security group.

---

## Skills Used

- Windows Server 2025
- Active Directory Domain Services (AD DS)
- DNS configuration
- Domain administration
- User and security group management
- NTFS permissions
- SMB file sharing
- VMware Workstation
- Virtual networking
- Command Prompt diagnostics and troubleshooting

---

## Next Steps

- Create Organizational Units (OUs)
- Configure Group Policy
- Configure DHCP
- Automate common administration tasks with PowerShell
- Expand the lab into a cloud environment (Azure)

---

### Progress Log

**04/08/2026**

Initial Active Directory environment completed with a functioning Domain Controller, two domain member servers, user management, security groups and file permissions.

