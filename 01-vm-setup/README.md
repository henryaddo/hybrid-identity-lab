# 01 - VM Setup and Domain Controller

## Goal
set up a small Active Directory lab using VirtualBox to practice Windows Server administration and common IT support tasks.

## Environment
- **VirtualBox:** Oracle VirtualBox
- **DC01:** Windows Server 2022
- **Client:** Windows 11 (windows11-Lab)

## What I Did
1. Created a virtual machine called DC01 in VirtualBox.
2. Installed Windows Server 2022.
3. Opened Server Manager and installed the Active Directory Domain Services (AD DS) and DNS roles.
4. Promoted DC01 to a domain controller.
5. Created another virtual machine running Windows 11 to use as a client.

Document initial Active Directory lab setup
## What I Learned
I learned how to install Active Directory on Windows Server 2022 and set up a domain controller. I also got a better understanding of why DNS is important in an Active Directory environment.

## Next Steps
- Connect the Windows 11 VM to the domain.
- Create users and groups in Active Directory.
- Practice resetting passwords and unlocking accounts.
- Set up Group Policy and test it on the Windows 11 client.
- 
