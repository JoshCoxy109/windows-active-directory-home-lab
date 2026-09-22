# Windows Active Directory & Systems Administration Lab

## Overview

I built a small company-style IT environment to practice Windows and Linux systems administration.

The lab used Ubuntu Server as the Active Directory domain controller and Windows 11 as a domain-joined employee computer. I used Samba to create the Active Directory environment and configured users, groups, Organizational Units (OUs), DNS, and Group Policy.

## What I Built

- Ubuntu Server configured as an Active Directory Domain Controller
- JOSHLAB.LOCAL Active Directory domain
- Users and security groups
- Users and Computers Organizational Units
- Windows 11 domain-joined computer
- Group Policy Object (GPO)
- Windows Security Baseline policy
- GPO linked to the Computers OU
- Successful Group Policy processing and verification

## Troubleshooting

- Used the wrong Ubuntu architecture initially and switched from AMD64 to ARM64 for Apple Silicon.
- Rebuilt the Samba AD configuration after the initial provisioning did not work correctly.
- Troubleshot SMB/SYSVOL access and Group Policy processing.

These issues helped me understand how Active Directory, DNS, SMB, SYSVOL, and Group Policy depend on each other.

## Tools & Technologies

- Ubuntu Server
- Windows 11
- Samba Active Directory
- Group Policy
- UTM Virtualization
- Linux
- PowerShell
- `samba-tool`
- `gpupdate`
- `gpresult`
- `nslookup`

## Documentation

See the PowerPoint presentation in this repository for a step-by-step walkthrough of the project, including screenshots, configuration steps, troubleshooting, and final verification.

## What I Learned

This project gave me hands-on experience with Active Directory administration and helped me understand how Windows and Linux systems communicate in a domain environment.

I also used documentation and AI assistance to learn commands and troubleshoot problems. I ran and verified the commands myself throughout the lab.
