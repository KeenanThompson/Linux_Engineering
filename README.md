Project Summary

This repository contains a structured set of security engineering artifacts demonstrating practical capability in Linux system hardening, host-based detection engineering, secure configuration enforcement, and defensive control implementation. The contents reflect the type of technical work performed by security engineers responsible for securing production workloads, validating host security posture, and supporting incident response and audit programs.

The environment was configured and hardened using industry-standard controls spanning authentication, access control, network boundary protection, intrusion prevention, kernel-level hardening, and audit instrumentation. All changes were executed on a live Ubuntu system, with each configuration validated through command outputs, log review, audit records, and functional testing. The repository includes both the applied configurations and the resulting evidence, aligning with expectations for verifiable security engineering work.

The technical scope includes:

- Establishment of a secure host baseline enabling configuration drift detection and forensic comparison

- Hardening of remote access pathways using SSH policy controls, key-based authentication, and session visibility

- Enforcement of least-privilege network access through UFW with rate-limited ingress and controlled service exposure

- Deployment and tuning of Fail2Ban for host-based intrusion prevention and early brute-force detection

- Development of a comprehensive auditd policy covering privileged operations, configuration changes, authentication behavior, and command execution

- Kernel-level security enhancements via sysctl, including address space layout randomization, packet filtering, ICMP hardening, and anti-tampering measures

- Documentation of procedures, evidence, and validation steps in a repeatable and reviewable format


The material demonstrates capabilities relevant to roles focused on securing and validating Linux-based systems, such as:

- Security Engineer

- Detection Engineer

- Cloud Security Engineer

- SOC Engineer or Analyst III

- IAM Engineer (host-level access control foundations)

- Infrastructure Security Engineer

The repository’s modular structure sets the foundation for subsequent phases involving centralized logging architectures, network telemetry enrichment, IAM and privilege modeling, and cloud security controls across AWS environments. The work emphasizes disciplined configuration practices, traceable evidence, and technical depth consistent with enterprise security engineering expectations.
