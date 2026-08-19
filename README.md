<h1>
Below are the Labs Carried out for my Work with Active Directory, Linux and Windows 11 Inside VirtualBox</h1>

<h2> Active Directory, Linux and Windows 11 Inside VirtualBox 💿</h2>

Three operating system environments built and administered inside VirtualBox — a Windows Server domain controller with a domain-joined client, an Ubuntu desktop, and a Windows 11 workstation. 25 labs covering installation, user and permission management, policy enforcement, scripting and scheduled automation across all three.

- <b>1. Active Directory 💿</b>
  - [9 Labs - Domain Controller Setup, Users and OUs, Group Policy, File Shares, PowerShell Automation, Account Lockouts](https://github.com/wahidonchain/AD-Inside-Virtualbox)
- <b>2. Linux 🐧</b>
  - [9 Labs - Ubuntu Install, Terminal, User Levels, File System Hierarchy, Permissions, Bash Scripting, Cron Jobs](https://github.com/wahidonchain/Linux-Inside-Virtualbox)
- <b>3. Windows 11 🪟</b>
  - [7 Labs - VM Setup and Snapshots, Local Users and Groups, NTFS Permissions, Event Viewer, Registry, CMD, Task Scheduler](https://github.com/wahidonchain/Windows-11-Inside-Virtualbox)

<h2>Recurring Themes Across the Three Sections</h2>

The same problems appear in all three environments with different tooling, which is what makes them worth doing together:

- **Access control** — AD security groups and NTFS permissions, Linux groups and chmod, Windows local groups and NTFS
- **Least privilege** — sudo and root in Linux, UAC and elevated Command Prompt in Windows, deliberately exempting the admin account from AD lockout policy
- **Forcing password changes at first login** — implemented three different ways
- **Automation** — PowerShell scripting in AD, Bash scripting in Linux, then scheduling both with cron and Task Scheduler
- **Verifying rather than assuming** — every access control lab tests from both sides, with a user who should have access and one who should not

<h2>Environments and Technologies Used</h2>

- Lenovo IdeaPad 5 Pro 16" AMD Ryzen 7, 16GB RAM
- Oracle VirtualBox with NAT Networking, Guest Additions and Snapshots
- Windows Server 2022, Windows 11 Enterprise, Ubuntu Desktop
- Active Directory Domain Services, DNS, AD Certificate Services, Group Policy
- PowerShell with the RSAT Active Directory module, Bash, Command Prompt
- Visual Studio Code

<h2>Connect With Me 🤳</h2>

[<img align="left" alt="LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]

[linkedin]: https://linkedin.com/in/awahid01
