# Security-Threat-Identification
Cybersecurity project focused on identifying, analyzing, and mitigating common security threats and vulnerabilities.

## Project Overview

This project focused on identifying security threats, performing vulnerability assessment, and analyzing network traffic in a controlled lab environment. Using Nmap, Nessus, and Wireshark, a vulnerable Metasploitable2 machine was assessed to identify exposed services, potential vulnerabilities, and suspicious network activity.

## Objectives

* Perform reconnaissance and service enumeration.
* Identify open ports and running services.
* Detect security vulnerabilities in exposed services.
* Analyze network traffic for suspicious activity.
* Recommend mitigation measures to improve security.

## Tools Used

* Nmap
* Wireshark
* Nessus
* Kali Linux
* Metasploitable2
* VirtualBox

## Environment Setup

* Operating System: Kali Linux
* Vulnerable Machine: Metasploitable2
* Virtualization Software: VirtualBox
* Network Type: NAT / Host-Only Adapter

## Activities Performed

### 1. Reconnaissance and Enumeration

* Identified active host and target IP address.
* Performed port scanning using Nmap.
* Enumerated running services and service versions.
* Collected system and network information.

### 2. Vulnerability Assessment

* Identified outdated and vulnerable services.
* Analyzed exposed network services and configurations.
* Assessed risks associated with insecure protocols and weak service configurations.

### 3. Network Traffic Analysis

* Captured and analyzed traffic using Wireshark.
* Observed TCP communication and SYN packets.
* Detected Nmap scanning activity and repeated connection attempts.
* Monitored communication between host systems and web applications.

## Key Vulnerabilities Identified

* Outdated FTP Service (vsftpd 2.3.4)
* Open Telnet Service
* Samba SMB Vulnerabilities
* Weak Remote Shell Services (rsh, rexec, rlogin)
* Exposed MySQL Database Service
* Outdated Apache Web Server
* UnrealIRCd Backdoor Vulnerability
* Apache Tomcat Configuration Risks
* Open VNC Remote Access
* Metasploitable Root Bind Shell Exposure
* NFS Misconfiguration Risks
* DNS Enumeration Risks

## Findings

* Multiple open ports and vulnerable services were identified.
* Insecure protocols such as Telnet and FTP were detected.
* Network traffic analysis revealed Nmap scanning activity and repeated TCP connection attempts.
* Several outdated services presented potential attack vectors for unauthorized access and exploitation.

## Mitigation Recommendations

* Update or disable outdated services.
* Replace Telnet with SSH.
* Implement strong authentication mechanisms.
* Secure database and remote access services.
* Apply security patches and system updates.
* Restrict unnecessary open ports and services.

## Conclusion

The assessment successfully identified multiple security threats and vulnerabilities within the target environment. Network traffic analysis highlighted suspicious activities and insecure communication methods. Proper patch management, service hardening, secure configurations, and strong authentication controls are recommended to reduce organizational risk and improve overall security posture.

[Security Threat Identification  Sneha S Internpe Project.pdf](https://github.com/user-attachments/files/28437300/Security.Threat.Identification.Sneha.S.Internpe.Project.pdf)

Internship
Organization: InternPe
Assignment: Assignment #1 – Security-Threat-Identification
Domain: Cyber Security Internship
