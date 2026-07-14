# Wazuh Infrastructure Automation

Project for automating and configuring a security infrastructure based on **Wazuh**, managed via **Ansible**. The project documents the creation of a secure environment, handling system issues, and proactive monitoring.

Project Goal

The goal is the automated deployment of a Wazuh agent on a target machine (Web), tackling connectivity challenges, cryptographic authentication (GPG/SSH), and system resource management.

Technologies Used
- **Wazuh**: SIEM/XDR for security.
- **Ansible**: Configuration automation.
- **SSH/GPG**: Management of security and package authenticity.
- **Linux (Debian/Ubuntu)**: Reference operating system.

Workflow and Troubleshooting
The documentation follows the project lifecycle, from initial setup to anomaly resolution:

1. **SSH Configuration**: Creating the secure channel between Manager and Agent
2. **Automation**: Deployment via Ansible.
3. **Issue Management**: - Fixing GPG error (`NO_PUBKEY`). - Handling storage saturation on `/var`.
4. **Validation**: Monitoring system logs and detecting threats via *Rootcheck*.
  
Conclusions

   The project showed the ability to manage a real security environment, turning blocking errors into opportunities to harden the system. The system can now actively detect anomalies (Rootcheck) and tampering attempts, confirming the integrity of the infrastructure.
