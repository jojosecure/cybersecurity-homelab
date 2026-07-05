# cybersecurity-homelab
A documented home lab for self-hosted tools, monitoring, cybersecurity practice and infrastructure learning.

# Cybersecurity Home Lab

This repository documents my personal cybersecurity and infrastructure home lab. The goal of this lab is to build hands-on experience with self-hosted tools, system monitoring, Linux, Docker, networking, cybersecurity concepts, and local AI capabilities.

The lab is designed to help me practice deploying, securing, monitoring, and documenting systems in a controlled local environment.

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


## Current Projects

### Uptime Kuma Monitoring

Implemented Uptime Kuma to monitor devices and services in my home lab environment.

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

Set up Homepage as a central dashboard for accessing and organizing self-hosted applications.

Security considerations:

* Sensitive tokens, passwords, and API keys are not stored in public documentation
* Configuration files are reviewed before being uploaded to GitHub
* Internal service links and private network details are excluded from public screenshots

### Docker Application Hosting

Using Docker to deploy and manage local services in a repeatable way.

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

## Future Improvements

* Add network diagrams
* Add screenshots of dashboards with sensitive information removed
* Document Docker Compose files
* Add backup and restore procedures
* Build a cybersecurity practice lab
* Add vulnerability scanning tools
* Add SIEM or log analysis tooling
* Improve monitoring and alerting
* Build a local AI agent for lab automation and security workflows
* Document security lessons learned for each major lab component

## Notes

This lab is for personal learning and skill development. Sensitive details such as passwords, tokens, IP addresses, hostnames, API keys, and private configuration values are intentionally excluded.
