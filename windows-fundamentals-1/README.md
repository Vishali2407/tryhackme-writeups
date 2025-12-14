# TryHackMe – Windows Fundamentals 1

## Overview
This room covers the basic building blocks of the Windows operating system. It explains how Windows is structured, how users interact with it, and how core system components work.

For a cybersecurity beginner, this room is important because Windows is the most common OS used in real-world environments. Without understanding Windows basics, it’s impossible to properly learn system security, privilege escalation, or incident response.

The room focuses on Windows fundamentals, file systems, user accounts, permissions, and essential system tools.

## What I Learned
- **Windows editions**  
  Learned that Windows comes in different editions, each offering different features depending on the user or environment.
- **Desktop and GUI**  
  Understood how users interact with Windows using the graphical interface and where common system options are located.
- **Introduction to Windows**  
  Learned how Windows manages system resources, users, and applications at a basic level.
- **NTFS file system**  
  Learned how files and folders are stored and how permissions are applied using NTFS.
- **System32 folder**  
  Understood why the `C:\Windows\System32` directory is critical and why modifying it can break the operating system.
- **User accounts and profiles**  
  Learned the difference between Administrator and Standard users and how user profiles are created under `C:\Users`.
- **User Account Control (UAC)**  
  Learned how UAC protects the system by limiting unauthorized system-level changes.
- **Settings and Control Panel**  
  Understood the difference between modern Windows Settings and the traditional Control Panel.
- **Task Manager**  
  Learned how to view running processes, system performance, and active users.

## Tools & Commands Used
- Windows graphical interface
- Run dialog (`Win + R`)
- Task Manager
- Windows Settings
- Control Panel

## Key Takeaways
- Windows security heavily depends on user roles and permissions.
- Administrator accounts have full control over the system.
- Critical system folders should never be modified casually.
- UAC adds an extra layer of protection against misuse.
- Task Manager is useful for monitoring system activity.

## How This Helps My Cybersecurity Journey
This room builds a strong foundation for working with Windows systems in cybersecurity. It helps in understanding how permissions work, how systems are structured, and how attackers might exploit misconfigurations.

This knowledge is required before learning Windows privilege escalation, malware behavior, and Active Directory concepts.

## Next Steps
- Complete Windows Fundamentals 2 and 3
- Learn basic CMD and PowerShell commands
- Practice beginner Windows privilege escalation rooms
