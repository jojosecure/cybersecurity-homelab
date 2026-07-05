# Lab Inventory

## Overview

This document tracks the major hardware, software, services, and tools used in my cybersecurity home lab. The goal is to maintain a clear inventory of lab components, their purpose, and their current status.

## Purpose

A lab inventory helps with:

* Understanding what systems are part of the lab
* Tracking current and planned services
* Supporting troubleshooting
* Planning future improvements
* Documenting security and infrastructure decisions
* Keeping the lab organized as it grows

## Hardware Inventory

| Device                   | Purpose                                          | Status              | Notes                                             |
| ------------------------ | ------------------------------------------------ | ------------------- | ------------------------------------------------- |
| Raspberry Pi 4 Model B   | Lightweight server for self-hosted services      | Active              | Used for monitoring and dashboard services        |
| UGREEN NAS               | Storage, backups, and future application hosting | Planned/In progress | Will support storage and backup workflows         |
| Windows 11 workstation   | Testing, administration, and lab access          | Active              | Used for daily access and lab interaction         |
| Small form factor PC     | Virtualization, local AI, and security workloads | Planned/In progress | May support Proxmox, VMs, and AI workloads        |
| Personal computer/laptop | Documentation and GitHub updates                 | Active              | Used for repository management and learning notes |

## Software and Platform Inventory

| Tool / Platform | Purpose                                | Status              | Notes                                               |
| --------------- | -------------------------------------- | ------------------- | --------------------------------------------------- |
| Docker          | Containerized application hosting      | Active              | Used to deploy and manage self-hosted tools         |
| Docker Compose  | Repeatable service deployment          | Active              | Used for defining containerized services            |
| Uptime Kuma     | Uptime and service monitoring          | Active              | Used to monitor devices and local services          |
| Homepage        | Home lab dashboard                     | Active              | Used as a central landing page for services         |
| Proxmox         | Virtualization platform                | Planned/In progress | Will support VMs and cybersecurity lab environments |
| GitHub          | Documentation and portfolio repository | Active              | Used to document the lab publicly                   |
| Linux           | Server and command-line learning       | Active/In progress  | Used across lab systems and services                |
| Windows 11      | Workstation environment                | Active              | Used for testing, administration, and access        |

## Planned Security Tools

| Tool Category               | Purpose                                                  | Status  | Notes                                     |
| --------------------------- | -------------------------------------------------------- | ------- | ----------------------------------------- |
| Vulnerability scanning      | Identify weaknesses and misconfigurations                | Planned | Tool selection pending                    |
| Log analysis                | Review system and application logs                       | Planned | Tool selection pending                    |
| SIEM / security monitoring  | Practice detection and monitoring workflows              | Planned | Tool selection pending                    |
| Network monitoring          | Improve visibility into lab devices and services         | Planned | Tool selection pending                    |
| Local AI security workflows | Assist with documentation, troubleshooting, and analysis | Planned | Local AI agent planned for a future phase |

## Inventory Review Checklist

When adding new tools or systems to the lab, I should document:

* What the tool or system is
* Why it was added
* Where it runs
* What data it stores
* Whether it requires credentials
* Whether it exposes any ports or services
* Whether it needs backups
* Whether screenshots or configuration files need to be sanitized before publishing

## Security Considerations

This public inventory does not include:

* Real IP addresses
* Hostnames
* Internal URLs
* Passwords
* API keys
* Tokens
* Private keys
* Personal file paths
* Sensitive screenshots
* Employer-owned or confidential information

## Future Improvements

* Add more detailed status tracking
* Add sanitized screenshots where appropriate
* Track backup requirements by service
* Track exposed ports in a private version of the inventory
* Add owner/admin notes for each system
* Add lifecycle status for active, testing, retired, or planned systems

## Notes

This inventory will be updated as new hardware, software, services, and security tools are added to the lab.
