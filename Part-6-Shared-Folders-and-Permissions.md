# Active Directory Home Lab - Part 6: Shared Folders and NTFS Permissions

This is Part 6 of my Active Directory home lab project. Up to now the lab has been about identity and policy. This part shifts to **file sharing**.

The goal: create a shared folder, give a specific user access to a subfolder only, log in as that user to test it, map it as a network drive, and then redo it the proper way using a security group.

## Goals for Part 6

- Create a shared folder on the Domain Controller using Server Manager
- Understand the difference between Share and NTFS permissions
- Grant a single user access to a sub-folder only (not the parent)
- Test access by logging in as the user
- Map the share as a network drive
- Redo the permissions properly using an Active Directory security group

---
