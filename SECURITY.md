# Security Policy

This repository documents my personal cybersecurity home lab. Since this lab may include infrastructure notes, monitoring tools, Docker configurations, and future security tooling, sensitive information is intentionally excluded from public documentation.

## Sensitive Information Not Included

The following information should not be committed to this repository:

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

## Safe Documentation Practices

Before committing files, I review them for sensitive data and replace private values with placeholders such as:

```text
REDACTED
YOUR_TOKEN_HERE
example.local
192.168.x.x
```

## Docker and Configuration Files

Docker Compose examples and configuration files should be sanitized before being uploaded.

Real secrets should be stored outside of GitHub using local environment files or another secure method.

## Security Focus Areas

This lab is intended to help me practice:

* Secure configuration
* Secrets management awareness
* Monitoring and alerting
* Backup and recovery planning
* Network and service exposure review
* Local AI security considerations
* Cybersecurity documentation

## Reporting Issues

This is a personal learning project. If a security concern is identified in the public documentation, it should be reviewed and corrected as soon as possible.
