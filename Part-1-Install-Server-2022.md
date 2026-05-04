# Active Directory Home Lab - Part 1: Installing Windows Server 2022

This is Part 1 of my Active Directory home lab project. The goal of this series is to build a working AD environment from scratch: a Windows Server 2022 Domain Controller and a Windows 11 client joined to the domain, using VirtualBox on my laptop.

In this part, I set up the virtualization environment and installed Windows Server 2022.

## Lab Environment

| Component | Detail |
|-----------|--------|
| Host RAM | 8 GB |
| Host CPUs | 4 cores |
| Hypervisor | Oracle VirtualBox 7.1.4 |
| Server VM | Windows Server 2022 (Desktop Experience) |
| Client VM | Windows 11 (added in a later part) |

## Goals for Part 1

- Install Oracle VirtualBox
- Download the Server 2022 and Windows 11 ISOs
- Create the Server 2022 VM
- Install Server 2022 with Desktop Experience
- Initial configuration (admin password, time zone)

---

## 1. Installing VirtualBox

Downloaded Oracle VirtualBox 7.1.4 from the official site and installed it with default options.
