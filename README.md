# Hybrid Identity Lab | Windows Server, Active Directory & Cloud Identity

## Project Overview

This project documents my hands-on experience building and administering a virtualized IT infrastructure environment using Windows Server, Active Directory Domain Services (AD DS), DNS, and Windows client systems.

The purpose of this lab is to develop practical skills in IT support, systems administration, identity management, networking, and troubleshooting through realistic enterprise IT scenarios.

The project will progressively incorporate Microsoft Entra ID and cloud identity technologies.

## Technologies Used

- **Virtualization:** Oracle VirtualBox
- **Server Operating System:** Windows Server 2022
- **Client Operating System:** Windows 11
- **Directory Services:** Active Directory Domain Services (AD DS)
- **Networking:** DNS, TCP/IP
- **Administration:** Windows Server Manager and Active Directory administrative tools
- **Planned Cloud Integration:** Microsoft Entra ID

## Lab Environment

The lab uses a virtualized network to simulate a small business IT infrastructure.

| Component | Configuration |
|---|---|
| Hypervisor | Oracle VirtualBox |
| Domain Controller | DC01 |
| Server OS | Windows Server 2022 |
| Client OS | Windows 11 |
| Active Directory Domain | henrylab.local |
| Directory Services | AD DS and DNS |

## Project Labs

### Lab 01 — Virtual Machine Setup and Domain Controller

**Status:** Completed

- Deployed Windows Server 2022 in Oracle VirtualBox.
- Installed Active Directory Domain Services and DNS roles.
- Created the `henrylab.local` domain forest.
- Promoted DC01 to a domain controller.
- Verified domain administrator access.

[View Lab 01 Documentation](01-vm-setup/README.md)

### Lab 02 — Active Directory User and Group Management

**Status:** Planned

- Create Organizational Units (OUs).
- Create and manage domain user accounts.
- Configure security groups.
- Practice password resets and account unlocking.
- Troubleshoot common user authentication issues.

### Lab 03 — Group Policy Administration

**Status:** Planned

- Create and link Group Policy Objects (GPOs).
- Configure workstation and user policies.
- Apply security settings.
- Troubleshoot Group Policy application.

### Lab 04 — DNS and Network Troubleshooting

**Status:** Planned

- Verify DNS name resolution.
- Troubleshoot domain connectivity.
- Diagnose DNS configuration problems.
- Practice common network troubleshooting commands.

### Lab 05 — Hybrid Identity Integration

**Status:** Planned

- Explore Microsoft Entra ID.
- Study hybrid identity architecture.
- Investigate identity synchronization and authentication.
- Document cloud identity administration scenarios.

## Technical Skills Demonstrated

- Windows Server installation and configuration
- Active Directory Domain Services deployment
- DNS server configuration
- Virtual machine administration
- Domain controller promotion
- Technical documentation

Additional skills will be documented as future labs are completed.

## Troubleshooting Approach

For each troubleshooting exercise, I aim to document:

1. **Problem:** What issue was reported?
2. **Investigation:** What information and evidence were collected?
3. **Diagnosis:** What caused the issue?
4. **Resolution:** What steps resolved the problem?
5. **Verification:** How was successful operation confirmed?

This approach reflects the structured troubleshooting and documentation practices used in IT support environments.

## Project Purpose

I created this project to strengthen my practical technical abilities and demonstrate my commitment to developing as an IT professional.

My focus is on building real-world troubleshooting, identity administration, and infrastructure support skills relevant to Help Desk, Desktop Support, Technical Support, and Junior Systems Administration positions.

---

**Project maintained by Henry Addo**

*CompTIA A+ | Red Hat Certified System Administrator (RHCSA)*
