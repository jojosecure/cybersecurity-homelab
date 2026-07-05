# Lessons Learned

This document tracks lessons learned while building and maintaining my cybersecurity home lab. The goal is to document challenges, mistakes, fixes, and key takeaways as the lab grows.

## General Lessons

* Documentation is easier when notes are captured during the setup process
* Screenshots should be reviewed before being uploaded publicly
* Configuration files should be checked for secrets, tokens, private IPs, hostnames, and personal file paths
* Starting with a simple lab structure makes it easier to expand later
* Separating documentation by tool helps keep the repository organized

## Docker Lessons

* Docker makes it easier to deploy and manage self-hosted services
* Docker Compose files should be sanitized before being committed to GitHub
* Named volumes are useful for keeping application data persistent
* Exposed ports should be reviewed carefully
* Logs are important for troubleshooting container issues

## Monitoring Lessons

* Uptime monitoring helps identify when devices or services are offline
* Friendly names make dashboards easier to read
* Monitoring should avoid exposing sensitive network details in public documentation
* Alerting should be configured carefully to avoid leaking sensitive information

## Security Lessons

* Secrets should never be committed to a public repository
* `.env` files should be excluded with `.gitignore`
* Public examples should use placeholders instead of real values
* Screenshots can accidentally reveal sensitive information
* Services should not be exposed to the public internet unless intentionally secured

## Future Lessons to Document

* Backup and recovery testing
* Proxmox setup and management
* NAS-based services
* Local AI agent setup
* Vulnerability scanning tools
* Log analysis or SIEM tooling
* Network segmentation
* Security lab exercises

## Notes

This document will be updated as I continue building the lab and learning from hands-on troubleshooting.
