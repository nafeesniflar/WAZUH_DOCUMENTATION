## What is Wazuh?

Wazuh is a free, open-source security platform that acts like a central security control room for your infrastructure, watching endpoints and servers for risky or malicious activity and giving you dashboards and reports about what’s going on. [page:1]  
It began as an endpoint detection and response (EDR) tool but has evolved into a unified security solution that combines endpoint detection, event management, vulnerability assessment, and cloud security monitoring in one place. [page:1]

## Key Capabilities

- Scans devices for common vulnerabilities such as missing patches and misconfigurations. [page:1]  
- Monitors endpoints for suspicious activity, including unusual processes and logins. [page:1]  
- Ingests raw logs and visualises them as clear dashboards and graphs. [page:1]  
- Provides compliance reporting for frameworks like PCI DSS, HIPAA, and NIST. [page:1]

## Where Wazuh Is Used

Wazuh was released in 2015 and is used by organisations of all sizes, from small businesses to large enterprises and government institutions. [page:1]  
Security teams use it to centralise monitoring of on-premises servers, workstations, and cloud workloads instead of checking each system individually. [page:1]

## Architecture: Manager–Agent Model

Wazuh uses a manager–agent architecture: [page:1]

- **Agents** are lightweight programs installed on the devices you want to monitor; they collect logs and security events and send them to the manager. [page:1]  
- **Manager** is the central Wazuh server responsible for receiving, storing, and processing this data, applying rules, and generating alerts and dashboards. [page:1]

You can think of it like this: every PC or server has a security sensor (agent), and all those sensors report back to one security HQ (manager) that gives you a unified view of what is happening in your environment. [page:1]
