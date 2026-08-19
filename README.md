# Wazuh SOC Home Lab

A hands-on Security Operations Center (SOC) home lab built using Wazuh, VMware, Ubuntu Server, Ubuntu Linux, and Windows 10.

The goal of this project is to build a small security monitoring environment and progressively practice real-world SOC activities including endpoint monitoring, security event analysis, alert investigation, detection engineering, and incident response.

---

## Lab Architecture

The lab consists of three virtual machines running in VMware.

```text
                         SOC LAB
                            │
                    ┌───────▼────────┐
                    │  Wazuh Server  │
                    │ Ubuntu Server  │
                    │                │
                    │ Wazuh Manager  │
                    │ Wazuh Indexer  │
                    │ Wazuh Dashboard│
                    └───────┬────────┘
                            │
                     VMware Network
                            │
              ┌─────────────┴─────────────┐
              │                           │
      ┌───────▼────────┐          ┌───────▼────────┐
      │ Ubuntu         │          │ Windows 10     │
      │ Endpoint       │          │ Endpoint       │
      │                │          │                │
      │ Wazuh Agent    │          │ Wazuh Agent    │
      └────────────────┘          └────────────────┘
```

## Technologies & Tools

* Wazuh
* VMware
* Ubuntu Server
* Ubuntu Linux
* Windows 10
* Wazuh Agent
* SIEM
* Security Monitoring

---
## Documentation

### Setup

| #  | Documentation                                        | 
| -- | ---------------------------------------------------- | 
| 01 | [Wazuh Server Setup](setup/01-wazuh-server-setup.md) | 

### Investigations

Security investigation write-ups will be added as detection and investigation scenarios are performed.

---

## Skills Practiced

* SIEM deployment
* Linux system administration
* VMware virtualization
* Endpoint monitoring
* Security event analysis
* Alert investigation
* Detection engineering
* Incident response
* SOC operations

---


