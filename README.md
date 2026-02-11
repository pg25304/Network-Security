Network Security Labs

This repository contains practical exercises, lab work, and documentation completed for a Network Security course. The labs focus on understanding and applying cybersecurity principles, network scanning, vulnerability assessment, and safe lab practices.

Overview

The goal of this repository is to demonstrate:

Core network security concepts and techniques

Hands-on experience with vulnerability scanning and assessment

Safe and controlled lab setups for testing network and system security

Analysis, reporting, and mitigation of identified vulnerabilities

The activities are designed to provide a practical understanding of network security, supplementing theoretical coursework.

Lab Environment

Lab exercises are conducted using virtual machines (VMs) to simulate real-world network environments. Typical setups include:

Kali Linux VM: used as the attacker/scanning machine

Target VMs: intentionally vulnerable systems such as Metasploitable for testing security tools

Virtual Network Configuration: isolated networks ensure safe testing without affecting external networks

Tools: Nessus, Nmap, Wireshark, and other network security utilities

Network configurations often include:

Internal Network Adapter: for isolated lab communication

NAT Adapter (optional): to provide internet access for tool updates and plugin downloads

Key Activities

Vulnerability Scanning: Identifying weaknesses in target systems using automated tools such as Nessus Essentials

Port and Service Analysis: Detecting open ports, running services, and potential misconfigurations

Risk Categorization: Classifying vulnerabilities by severity (Critical, High, Medium, Low, Informational)

Reporting and Documentation: Producing structured reports with recommendations for mitigation

Network Security Concepts: Practical application of firewalls, access controls, encryption, and safe lab practices

Repository Structure
Network-Security/
│
├─ Lab Reports/             # Documentation of lab activities and scan results
├─ Configs/                 # Configuration files for tools or virtual lab setups
├─ Scripts/                 # Scripts used during exercises (e.g., scans or automations)
├─ README.md                # Overview and course documentation


Learning Outcomes

Practical experience with automated vulnerability scanning and network analysis

Understanding vulnerability risk assessment and mitigation strategies

Knowledge of virtualization and lab network configuration for cybersecurity testing

Ability to document and communicate findings professionally

Notes

All activities were conducted in an isolated lab environment to ensure safety and prevent interference with real networks

This repository serves as a learning resource for Network Security concepts and practical exercises

Tools and configurations are chosen to reflect real-world cybersecurity practices
