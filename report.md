# Incident Response Report

## 1. Introduction

This report documents the simulation and analysis of a security incident on a Linux system. The purpose of the exercise was to demonstrate how incident response teams detect, analyze, contain, and mitigate security threats.

Incident response is a critical component of cybersecurity operations that ensures organizations can quickly respond to and recover from security incidents.

## 2. Incident Description

A simulated brute force login attack was performed by generating repeated failed login attempts using a test user account.

These login attempts created authentication logs that were analyzed to identify suspicious activity.

## 3. Detection

The incident was detected by analyzing system authentication logs.

Linux stores authentication events in system logs, which contain information about login attempts, authentication failures, and privilege escalations.

Multiple failed login attempts were identified, indicating a possible brute force attack.

## 4. Incident Classification

Incident Type: Brute Force Login Attempt
Attack Target: Linux Authentication System
Severity Level: Medium

Repeated login failures are a common indicator of unauthorized access attempts.

## 5. Containment

The suspicious account used in the attack simulation was locked to prevent further login attempts.

This containment step helps prevent attackers from gaining unauthorized access to the system.

## 6. Eradication

The malicious or test account used during the simulation was removed from the system to eliminate the threat source.

Removing compromised accounts ensures that attackers cannot continue their activities.

## 7. Recovery

System updates and security checks were performed to ensure that the system remained secure after the incident.

Updating system packages helps patch known vulnerabilities and strengthens system security.

## 8. Incident Timeline

1. Failed login attempts generated
2. Authentication logs analyzed
3. Suspicious activity detected
4. Incident classified as brute force attack
5. Suspicious account locked
6. Threat source removed
7. System security restored

## 9. Preventive Measures

To prevent similar incidents in the future, the following security measures are recommended:

* Implement account lockout policies
* Enforce strong password policies
* Enable multi-factor authentication
* Monitor system logs regularly
* Deploy intrusion detection systems
* Restrict unnecessary user accounts

## 10. Conclusion

The simulation successfully demonstrated the incident response process using system log analysis. Although the incident was simulated, it illustrates how security teams identify suspicious activity and implement mitigation strategies to protect systems from potential attacks.
