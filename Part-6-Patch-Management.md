# Active Directory Home Lab - Part 6: Patch Management with Action1

This is Part 6 of my Active Directory home lab project. Up to now the lab has covered the AD basics: building a Domain Controller, joining a client, creating users, and applying Group Policy. This part shifts focus to **patch management**

I'm using **Action1**, a free patch management platform, to scan and patch the lab. Free up to 200 endpoints, which is more than enough for a home lab and small businesses too.

## Goals for Part 6

- Understand why patch management matters from a compliance perspective
- Sign up for Action1 and deploy the agent to the Domain Controller
- Scan the DC for missing updates
- Deploy patches and verify they install
- Pull a built-in report that could be handed to an auditor

---

