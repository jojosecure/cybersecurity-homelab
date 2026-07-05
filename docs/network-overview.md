# Network Overview

## Overview

This document provides a high-level overview of my home lab network. The goal is to document how major devices and services are organized while avoiding sensitive details such as real IP addresses, hostnames, or internal URLs.

## Purpose

The purpose of this network overview is to:

* Understand how home lab devices connect
* Document key systems and their roles
* Support future troubleshooting
* Plan for security improvements
* Prepare for future network diagrams
* Avoid exposing sensitive network information publicly

## High-Level Lab Layout

The home lab currently includes:

* Main router
* Raspberry Pi
* UGREEN NAS
* Windows 11 workstation
* Small form factor PC
* Personal computer/laptop
* Docker-hosted services
* Monitoring tools
* Future local AI tools
* Future cybersecurity lab tools

## Device Roles

| Device                   | General Role                                                |
| ------------------------ | ----------------------------------------------------------- |
| Main Router              | Provides network connectivity for the home lab              |
| Raspberry Pi             | Lightweight server for self-hosted services                 |
| UGREEN NAS               | Local storage and future application hosting                |
| Windows 11 Workstation   | Daily use, testing, and lab access                          |
| Small Form Factor PC     | Future virtualization, local AI, or cybersecurity workloads |
| Personal Computer/Laptop | Administration, documentation, and GitHub updates           |

## Services

Current or planned services may include:

* Uptime Kuma for monitoring
* Homepage for dashboard access
* Docker for containerized applications
* Proxmox for virtualization
* Local AI agent tooling
* Future vulnerability scanning tools
* Future log analysis or SIEM tools

## Security Considerations

This public documentation does not include:

* Real private IP addresses
* Real hostnames
* Internal URLs
* Router details
* Wi-Fi information
* Passwords
* Tokens
* API keys
* Screenshots with sensitive information

Public examples should use placeholder values such as:

```text
192.168.x.x
example.local
REDACTED
```

## Future Improvements

* Add a sanitized network diagram
* Document VLAN or network segmentation plans
* Identify which services should remain local only
* Review exposed ports and services
* Document VPN or remote access options
* Add logging and monitoring design notes
* Document backup and recovery paths

## Notes

This document is intended to provide a safe, high-level view of the lab environment. More detailed technical notes should be kept private if they include sensitive network information.
