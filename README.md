#### Automated ELK Stack Deployment

This repository contains an ELK Stack deployment lab using Ansible, Docker, Filebeat, and Metricbeat in a controlled Azure/Linux environment.

The project documents infrastructure automation, monitoring configuration, network layout, access controls, and deployment steps for a small security-monitoring lab.

##### Project Scope

This was a controlled training environment. It was not connected to production infrastructure, customer systems, or private employer environments.

The lab demonstrates how infrastructure automation can be used to configure monitoring components and supporting Linux systems in a repeatable way.

##### Network Overview

The deployment used a small Azure-based lab network with a jump box, web servers, and an ELK server.

The network diagram included in this repository documents the intended lab structure and access relationships.

##### Included Files

* `Network Diagram.jpg`
* `ansible.cfg`
* `filebeat-config.yml`
* `filebeat-playbook.yml`
* `hosts`
* `install-elk.yml`
* `metricbeat-config.yml`
* `metricbeat-playbook.yml`
* `pentest.yml`
* `sysctl.conf`

##### Focus Areas

* Infrastructure automation
* Linux administration concepts
* Docker-based deployment
* Ansible playbook structure
* ELK Stack monitoring concepts
* Filebeat configuration
* Metricbeat configuration
* Network documentation
* Security operations concepts
* Technical documentation

##### Lab Components

###### Jump Box

The jump box was used as the administrative control point for running Ansible playbooks and managing lab configuration.

###### Web Servers

The web servers represented monitored systems in the lab environment.

###### ELK Server

The ELK server hosted the monitoring stack used to collect and review log and metric data from the lab systems.

###### Filebeat

Filebeat was used to collect and forward log data from monitored systems.

###### Metricbeat

Metricbeat was used to collect and forward system metric data from monitored systems.

##### Ansible Playbooks

The Ansible playbooks in this repository were used to automate setup tasks across the lab environment, including Docker installation, ELK deployment, Filebeat configuration, and Metricbeat configuration.

##### Security and Access Notes

The lab used controlled access rules appropriate for a training environment. Administrative access was intended to flow through the jump box rather than exposing all systems broadly.

##### Related Repositories

* cybersecurity-foundation-notes
* red-vs-blue-attack-analysis
* ai-assisted-workflow-analysis-demo

##### Current Context

This is a historical infrastructure and security-monitoring lab project. It supports my broader work in systems analysis, automation, workflow design, security-minded technical analysis, and technical documentation.
