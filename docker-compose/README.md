# Docker Compose Examples

This folder will contain sanitized Docker Compose examples used in my home lab.

The goal is to document how self-hosted services are deployed while making sure sensitive information is not uploaded publicly.

## Purpose

Docker Compose is used in this lab to define, deploy, and manage self-hosted applications in a repeatable way.

## Security Notes

Before uploading any Docker Compose file, I will review it for sensitive information, including:

* Passwords
* API keys
* Tokens
* Private IP addresses
* Hostnames
* Environment variables
* Internal URLs
* Volume paths that reveal personal information

## Planned Examples

* Uptime Kuma
* Homepage
* Local AI tools
* Future cybersecurity tools
* Monitoring and logging tools

## Best Practices

* Use placeholder values instead of real secrets
* Store sensitive values in `.env` files when appropriate
* Do not upload real `.env` files to GitHub
* Review files before committing changes
* Keep public examples simple and safe
