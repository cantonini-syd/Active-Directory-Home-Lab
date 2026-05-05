# Active Directory Home Lab - Part 2: Promoting the Server to a Domain Controller

This is Part 2 of my Active Directory home lab project. With the Server 2022 VM up and running from Part 1, the next step was turning it into an actual Domain Controller. That means renaming the server, installing the AD DS role, and promoting it as the first DC in a new forest.

## Goals for Part 2

- Rename the server to something meaningful
- Install the Active Directory Domain Services (AD DS) role
- Promote the server to a Domain Controller
- Create a new forest and domain
- Verify the install with a command-line check

---

## 1. Renaming the Server

By default Windows assigns a random computer name like `WIN-0907BLUE`, which is useless in a real environment. Standard practice is to name servers based on location and role, so I went with **SYD-DC-01** (location code + role + number). Sydney is the location, DC means Domain Controller, and 01 is the server number.

In Server Manager I went to **Local Server**, clicked the existing computer name, and used **Change** to rename it. A restart was required to apply the change.


