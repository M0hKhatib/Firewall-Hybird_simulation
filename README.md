# Network Firewall Simulation

This project implements a sophisticated network firewall simulation in Python, designed to model real-world network security scenarios. The simulation processes synthetic network packets through a multi-stage pipeline: data input, rule-based inspection, anomaly detection using an Isolation Forest machine learning model, context-aware response, and final action determination. Key features include:

- **Realistic Traffic Generation**: Simulates internal, DMZ, and external network traffic with a 5% attack/anomaly rate, using realistic IP ranges and common ports.
- **Rule-Based Filtering**: Enforces security policies based on blocked IPs, sensitive server access, and protocol/port restrictions.
- **Anomaly Detection**: Leverages an Isolation Forest model to identify suspicious traffic patterns based on packet size, connection rate, and port entropy.
- **Comprehensive Logging & Visualization**: Generates detailed traffic logs, statistical reports, and visualizations (e.g., traffic distribution, anomaly scores, and temporal trends).
- **Modular Design**: Structured for easy extension, with configurable parameters for simulation duration, packet rate, and network configurations.

The project outputs detailed simulation results, including traffic statistics, top sources/destinations, and visualizations saved as PNG files. Ideal for studying network security, firewall design, or machine learning applications in cybersecurity.

**Technologies**: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, TQDM, Logging

**Usage**: Run the script to simulate 60 seconds of network traffic at 10 packets per second, generating logs and visualizations for analysis.


