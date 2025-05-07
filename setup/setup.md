# Lab Setup – Active Directory 2.0

This file documents the initial environment setup for AD Lab 2.0, including VM preparation, network configuration, and domain setup.

---

## Virtual Machine Overview

| VM Name           | Role                  | OS                    | IP Address     |
|------------------|-----------------------|------------------------|----------------|
| DC2               | Domain Controller     | Windows Server 2019    | 192.168.2.10    |
| Client-W10        | Domain Workstation    | Windows 10 Pro         | 192.168.2.20    |

---

## Setup Steps

### 1. Install Windows Server 2019
- [ ] Download ISO and create VM
- [ ] Assign static IP: `192.168.2.10`
- [ ] Name the computer: `DC2`
- [ ] Install Active Directory Domain Services (AD DS)

### 2. Promote to Domain Controller
- [ ] Configure new forest: `ad2.local`
- [ ] DNS role installs automatically
- [ ] Reboot after promotion

### 3. Join Client to Domain
- [ ] Create new VM for Windows 10
- [ ] Assign static IP: `192.168.2.20`
- [ ] Join domain: `ad2.local`

---

## Notes

- Use VirtualBox NAT or Internal Network with proper adapter settings
- Screenshots of each step will be added to the `screenshots/` folder
