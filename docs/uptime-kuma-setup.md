# Uptime Kuma Setup

## Overview

Uptime Kuma is used in my home lab to monitor the availability of local devices, services, and self-hosted applications. This helps me quickly identify when something is offline or not responding as expected.

## Purpose

The goal of this setup is to practice basic service monitoring, improve visibility across my local environment, and build a foundation for future security monitoring and alerting.

## What I Monitor

* Main router
* Raspberry Pi
* NAS
* Homepage dashboard
* Local self-hosted services
* Other home lab devices

## Monitoring Methods

Current monitoring may include:

* Ping checks for network devices
* HTTP/HTTPS checks for web dashboards
* Service availability checks for local applications

## Security Considerations

* Sensitive details such as private IP addresses, hostnames, tokens, and credentials are not included in public documentation
* Friendly names are used instead of exposing detailed network information
* Monitoring is currently focused on local visibility rather than public exposure
* Public access is avoided unless a service is intentionally secured and hardened
* Future alerting should be configured carefully to avoid exposing sensitive information through notifications

## What I Learned

* How to deploy and access a self-hosted monitoring tool
* How to create basic uptime monitors
* How to use friendly names for devices and services
* How monitoring supports availability and operational awareness
* Why documentation is important for repeatable lab work

## Future Improvements

* Add alerting for service outages
* Create a public or private status page
* Add more detailed service checks
* Document backup and restore steps
* Add screenshots with sensitive information removed
* Explore security-focused monitoring and logging tools
