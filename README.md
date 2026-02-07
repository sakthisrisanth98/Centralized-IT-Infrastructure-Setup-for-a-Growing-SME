# Centralized-IT-Infrastructure-Setup-for-a-Growing-SME
Centralized cloud infrastructure built using AWS EC2. Includes manual VM provisioning, secure SSH access, centralized storage, user management, and snapshot-based backup &amp; recovery. Designed using AWS Free Tier to simulate real-world IT administration tasks.

This project demonstrates the design and implementation of a centralized IT infrastructure for a small enterprise using Amazon Web Services (AWS). The goal of the project is to replace decentralized, employee-based systems with a single cloud-hosted server that is secure, manageable, and scalable.

An AWS EC2 virtual machine running Ubuntu Server was manually provisioned using free-tier resources. Secure remote access was configured using SSH with key-based authentication. A centralized storage directory was created on the server, and multiple employee user accounts were added to simulate controlled access. System maintenance was performed by updating the operating system packages.

To ensure data safety and business continuity, a snapshot-based backup and recovery mechanism was implemented using AWS AMI. The entire setup was performed manually without automation tools to simulate real-world system administration tasks.

This project highlights practical cloud computing skills, including virtual machine management, server administration, security configuration, and disaster recovery planning, making it suitable for small and growing enterprises.

