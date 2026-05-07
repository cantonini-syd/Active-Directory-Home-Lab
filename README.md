# Active Directory Home Lab

A multi-part home lab project documenting the design and deployment of a functional Active Directory environment from scratch. Built end-to-end on a single laptop using Oracle VirtualBox, the lab covers the core skills including identity management, Group Policy, file share permissions, networking, and PowerShell automation.

## Lab Environment

| Component | Detail |
|-----------|--------|
| Hypervisor | Oracle VirtualBox 7.1.4 |
| Host RAM | 8 GB |
| Host CPUs | 4 cores |
| Domain Controller | Windows Server 2022 (Desktop Experience) — `SYD-DC-01` |
| Client | Windows 11 Pro — `SYD-CL-01` |
| Domain | `lab.org` |
| Network | Host-only adapter, `10.1.1.0/8` |

## Skills Demonstrated

- **Virtualization** — Oracle VirtualBox VM creation, host-only networking, snapshot management
- **Windows Server Administration** — Server 2022 install, role management, Server Manager
- **Active Directory** — Forest and domain creation, OU design, user and group management
- **Group Policy** — Default Domain Policy, password and lockout rules, targeted GPOs linked to OUs
- **Networking** — Static IP configuration, DNS, troubleshooting connectivity between VMs
- **File Services** — Shared folders, NTFS vs Share permissions, security-group based access control
- **Help Desk Scenarios** — Account lockouts, disabled accounts, expired accounts, password resets, RDP
- **PowerShell** — Bulk user creation from CSV, querying AD with `Get-ADUser`, scripting basics


   ## Parts
   - [Part 1 — Install Windows Server 2022](Part-1-Install-Server-2022.md)
   - [Part 2 - Promote to Domain Controller](Part-2-Promote-Domain-Controller.md)
   - [Part 3 - Creating User Accounts in Active Directory](Part-3-Creating-New-Users.md)
   - [Part 4 - Join Windows 11 to Domain & RDP](Part-4-Join-Windows-11-to-Domain.md)
   - [Part 5: Group Policy and Replicating Help Desk Issues](Part-5-Group-Policy-Help-Desk-Issues.md)
   - [Part 6 - Shared Folders and Permissions](Part-6-Shared-Folders-and-Permissions.md)
   - [Part 7 - OUs and Targeted GPO](Part-7-OUs-and-Targeted-GPO.md)
   - [Part 8 - PowerShell Bulk User Creation](Part-8-PowerShell-Bulk-Users.md)
