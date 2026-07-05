# Cybersecurity Home Lab

A documented cybersecurity home lab for self-hosted tools, monitoring, infrastructure learning, security practice, automation, and local AI experimentation.

## Overview

This repository documents my personal cybersecurity and infrastructure home lab. The goal of this lab is to build hands-on experience with self-hosted tools, system monitoring, Linux, Docker, networking, cybersecurity concepts, and local AI capabilities.

The lab is designed to help me practice deploying, securing, monitoring, and documenting systems in a controlled local environment.

## Documentation Index

This repository includes supporting documentation for the major tools, concepts, and design decisions used in my home lab.

| Document                                                   | Description                                                                                            |
| ---------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| [Uptime Kuma Setup](docs/uptime-kuma-setup.md)             | Documents how Uptime Kuma is used for monitoring devices, services, and uptime in the lab              |
| [Homepage Setup](docs/homepage-setup.md)                   | Explains how Homepage is used as a central dashboard for self-hosted services                          |
| [Docker Basics](docs/docker-basics.md)                     | Covers basic Docker concepts and why Docker is used in the lab                                         |
| [Security Considerations](docs/security-considerations.md) | Outlines security principles, secrets management, exposure risks, and local AI security considerations |
| [Network Overview](docs/network-overview.md)               | Provides a high-level overview of the home lab network without exposing sensitive details              |
| [Home Lab Diagram](docs/lab-diagram.md)                    | Shows a sanitized visual architecture of the home lab using placeholder names                          |
| [Home Lab Roadmap](notes/lab-roadmap.md)                   | Outlines planned phases for infrastructure, security tooling, local AI, and future improvements        |
| [Docker Compose Examples](docker-compose/README.md)        | Explains how sanitized Docker Compose examples will be documented                                      |
| [Screenshots](screenshots/README.md)                       | Describes how screenshots should be reviewed and sanitized before upload                               |
| [Common Docker Commands](docs/common-docker-commands.md) | Lists common Docker and Docker Compose commands used to manage home lab services |
| [Local AI Agent Plan](docs/local-ai-agent-plan.md) | Outlines future plans for building a local AI agent for automation, documentation, troubleshooting, and security workflows |

## Lab Goals

* Learn how to deploy and manage local applications
* Practice Linux, Docker, and basic infrastructure administration
* Monitor devices, services, and uptime across my home network
* Build a foundation for cybersecurity labs and future security tooling
* Improve my understanding of secure configuration, access control, and system hardening
* Practice documenting technical work in a clear and repeatable way
* Build and experiment with a local AI agent for automation, research, and security-focused workflows

## Security Goals

* Practice securing self-hosted applications and local services
* Learn how to manage secrets, tokens, and configuration files safely
* Understand basic network segmentation and service exposure risks
* Monitor system availability and identify service outages
* Build repeatable backup and recovery processes
* Practice least-privilege access where possible
* Document security considerations for each deployed tool
* Avoid exposing sensitive services directly to the public internet
* Improve awareness of logging, monitoring, and alerting concepts

## Current Environment

### Hardware

* Raspberry Pi 4 Model B
* UGREEN NAS
* Windows 11 workstation
* Small form factor PC
* Personal computer/laptop

### Software & Platforms

* Docker
* Docker Compose
* Uptime Kuma
* Homepage
* Proxmox
* Linux
* Windows 11
* GitHub

### Planned / Future Tools

* Local AI agent
* SIEM or log analysis tooling
* Vulnerability scanning tools
* Backup and recovery tooling
* Additional cybersecurity lab tools

## Project Status

| Area                    | Status              | Notes                                                                           |
| ----------------------- | ------------------- | ------------------------------------------------------------------------------- |
| GitHub repository setup | In progress         | Repository structure and documentation are being built out                      |
| Uptime Kuma monitoring  | Started             | Used to monitor devices and services in the lab                                 |
| Homepage dashboard      | Started             | Used as a central dashboard for self-hosted services                            |
| Docker documentation    | Started             | Basic Docker concepts and future Compose examples are documented                |
| Security documentation  | Started             | Security policy and security considerations are included                        |
| Network documentation   | Planned/In progress | High-level network overview and sanitized diagrams are being documented         |
| Local AI agent          | Planned             | Future goal for automation, research, documentation, and security workflows     |
| Security tooling        | Planned             | Future tools may include vulnerability scanning, logging, and SIEM capabilities |

## Repository Structure

```text
cybersecurity-homelab/
├── README.md
├── SECURITY.md
├── .gitignore
├── docs/
│   ├── uptime-kuma-setup.md
│   ├── homepage-setup.md
│   ├── docker-basics.md
│   ├── security-considerations.md
│   ├── network-overview.md
│   └── lab-diagram.md
├── notes/
│   └── lab-roadmap.md
├── docker-compose/
│   └── README.md
└── screenshots/
    └── README.md
```

## Folder Overview

| Folder/File       | Purpose                                                                       |
| ----------------- | ----------------------------------------------------------------------------- |
| `README.md`       | Main overview of the home lab, goals, tools, and current projects             |
| `SECURITY.md`     | Security policy and safe documentation practices                              |
| `.gitignore`      | Prevents local files, secrets, logs, and environment files from being tracked |
| `docs/`           | Setup guides, walkthroughs, diagrams, and technical documentation             |
| `notes/`          | Roadmaps, planning notes, lessons learned, and lab ideas                      |
| `docker-compose/` | Sanitized Docker Compose examples and Docker-related documentation            |
| `screenshots/`    | Sanitized screenshots of dashboards, tools, and lab visuals                   |

## Documentation Index

This repository includes supporting documentation for the major tools, concepts, and design decisions used in my home lab.

| Document                                                   | Description                                                                                            |
| ---------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| [Uptime Kuma Setup](docs/uptime-kuma-setup.md)             | Documents how Uptime Kuma is used for monitoring devices, services, and uptime in the lab              |
| [Homepage Setup](docs/homepage-setup.md)                   | Explains how Homepage is used as a central dashboard for self-hosted services                          |
| [Docker Basics](docs/docker-basics.md)                     | Covers basic Docker concepts and why Docker is used in the lab                                         |
| [Security Considerations](docs/security-considerations.md) | Outlines security principles, secrets management, exposure risks, and local AI security considerations |
| [Network Overview](docs/network-overview.md)               | Provides a high-level overview of the home lab network without exposing sensitive details              |
| [Home Lab Diagram](docs/lab-diagram.md)                    | Shows a sanitized visual architecture of the home lab using placeholder names                          |
| [Home Lab Roadmap](notes/lab-roadmap.md)                   | Outlines planned phases for infrastructure, security tooling, local AI, and future improvements        |
| [Docker Compose Examples](docker-compose/README.md)        | Explains how sanitized Docker Compose examples will be documented                                      |
| [Screenshots](screenshots/README.md)                       | Describes how screenshots should be reviewed and sanitized before upload                               |

## Current Projects

### Uptime Kuma Monitoring

Uptime Kuma is used to monitor devices and services in my home lab environment.

Monitored items may include:

* Main router
* Raspberry Pi
* NAS
* Local applications
* Other network devices

Security considerations:

* Monitoring helps identify unexpected downtime or service failures
* Friendly names are used instead of exposing sensitive host details
* Public exposure is avoided unless intentionally configured and secured

### Homepage Dashboard

Homepage is used as a central dashboard for accessing and organizing self-hosted applications.

Security considerations:

* Sensitive tokens, passwords, and API keys are not stored in public documentation
* Configuration files are reviewed before being uploaded to GitHub
* Internal service links and private network details are excluded from public screenshots

### Docker Application Hosting

Docker is used to deploy and manage local services in a repeatable way.

Security considerations:

* Docker Compose files are reviewed before publishing
* Secrets and environment variables are excluded from public repositories
* Containers are kept organized by application and purpose
* Future improvements may include container update management, vulnerability scanning, and backup procedures

### Local AI Agent

A future goal of this lab is to build and experiment with a local AI agent that can assist with automation, documentation, research, and security-focused workflows.

Potential use cases include:

* Summarizing security notes and lab documentation
* Assisting with troubleshooting local services
* Helping generate reports from local data
* Reviewing configuration files for potential issues
* Supporting cybersecurity learning and research
* Exploring private/local AI workflows without relying entirely on cloud-based tools

## Skills Practiced

* Linux command line basics
* Docker container management
* Network monitoring
* Service availability monitoring
* YAML configuration
* Self-hosted application deployment
* Secure configuration practices
* Secrets management awareness
* Backup and recovery planning
* Technical documentation
* Local AI experimentation

## Security and Privacy Notice

This repository is intended for personal learning and portfolio documentation. Sensitive information is intentionally excluded from public files.

The following should not be committed to this repository:

* Passwords
* API keys
* Tokens
* Private keys
* `.env` files
* Real internal IP addresses
* Hostnames
* Internal URLs
* Personal file paths
* Screenshots with sensitive information
* Employer-owned or confidential information

Public examples should use placeholder values such as:

```text
REDACTED
YOUR_TOKEN_HERE
example.local
192.168.x.x
```

## Future Improvements

* Add sanitized screenshots of dashboards
* Add more detailed network diagrams
* Document Docker Compose files
* Add backup and restore procedures
* Build a cybersecurity practice lab
* Add vulnerability scanning tools
* Add SIEM or log analysis tooling
* Improve monitoring and alerting
* Build a local AI agent for lab automation and security workflows
* Document security lessons learned for each major lab component

## Notes

This lab is for personal learning, skill development, and cybersecurity practice. Security is treated as an ongoing process, and documentation will be updated as the lab grows.
