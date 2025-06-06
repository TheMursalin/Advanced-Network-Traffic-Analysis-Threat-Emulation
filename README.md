# 🛡️ Network Traffic Analyzer (Wireshark + TryHackMe + Python)

> **Capture. Analyze. Defend.**  
A hands-on cybersecurity project showcasing packet inspection and anomaly detection using Wireshark and Python.

---

## 🚀 Features

- Analyzes TCP/IP, HTTP, and DNS traffic from `.pcap` files.
- Detects:
  - High-frequency DNS queries (possible tunneling/exfiltration)
  - Suspicious domains and IPs
- Based on real-world CTF scenario from TryHackMe.
- Built using Python (Scapy) and Wireshark captures.

---

## 📁 Project Structure

```bash
network-traffic-analyzer/
│
├── analysis.py             # Main Python script
├── sample.pcap             # Example capture file
├── screenshots/            # Wireshark/CTF images
├── report.pdf              # Detailed technical report
└── README.md               # This file

